---
title: "DwfImage.UpdateSize"
linktitle: "UpdateSize"
articleTitle: "UpdateSize"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。更新图像尺寸。提供对图像尺寸参数的强制计算。此计算必须在使用图像尺寸...之前执行。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.dwf/dwfimage/updatesize/"
product_version: "26.9"
---
## DwfImage.UpdateSize method

更新图像尺寸。
提供对图像尺寸参数的强制计算。此计算必须执行
在更改图像的图形内容后使用图像尺寸参数之前
这会影响图像尺寸参数。

```csharp
public void UpdateSize()
```

## 示例

检索图像页面，修改其属性并更新图像尺寸参数。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (var image = (DwfImage) Image.Load(inStream))
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

* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

