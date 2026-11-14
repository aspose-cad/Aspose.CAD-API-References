---
title: "DwfImage.Pages"
linktitle: "Pages"
articleTitle: "Pages"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 属性。获取 DWF 页面。返回包含在 DWF 图像中的所有 DWF 页面数组。每个 DWF 页面定义其所有可用的图形..."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.dwf/dwfimage/pages/"
product_version: "26.9"
---
## DwfImage.Pages property

获取 DWF 页面。
返回包含在 DWF 图像中的所有 DWF 页面数组。
每个 DWF 页面定义其所有可用的图形参数以及绘制在其上的所有对象。

```csharp
public DwfPage[] Pages { get; }
```

## 示例

检索图像页面并更改其属性。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage) Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    DwfWhipDrawable[] entities = image.Pages[0].Entities;
    foreach(DwfWhipDrawable drawable in entities)
    {
        if(drawable is DwfWhipPolyline)
        {
            ((DwfWhipPolyline) drawable).Points[0].X = -50;
            ((DwfWhipPolyline) drawable).Points[0].Y = -50;
            break;
        }
    }  

    image.UpdateSize();

    foreach (DwfWhipDrawable drawable in entities)
    {
        if (drawable is DwfWhipText)
        {
            ((DwfWhipText)drawable).Font.Name.Value.AsciiString = "Arial";
        }
    }

    ImageOptionsBase options = new PngOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
    {
        PageWidth = (float)image.Pages[0].PaperWidth,
        PageHeight = (float)image.Pages[0].PaperHeight,
        DrawType = CadDrawTypeMode.UseObjectColor,
    };

    image.Save(stream, options);
}
```

### 另请参阅

* class [DwfPage](../../dwfpage/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

