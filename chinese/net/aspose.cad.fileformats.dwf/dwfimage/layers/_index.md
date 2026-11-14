---
title: "DwfImage.Layers"
linktitle: "图层"
articleTitle: "图层"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 属性。获取 DWF 页面图层。返回 DWF 图层的可枚举集合。DWF 数据可以分配给特定的 DWF 图层，该图层是一个 g..."
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.dwf/dwfimage/layers/"
product_version: "26.9"
---
## DwfImage.Layers property

获取 DWF 页面图层。
返回 DWF 图层的可枚举集合。
DWF 数据可以分配给特定的 DWF 图层，该图层是一个分组绘图对象。

```csharp
public DwfLayersList Layers { get; }
```

## 示例

导出指定的图层。

```csharp
string file = "ExampleFile.dwf";
using (DwfImage image = (DwfImage) Aspose.CAD.Image.Load(file))
{
    foreach (var layer in image.Layers)
    {
        string outFile = "ExampleFile_" + layer + ".jpg";
        using (FileStream fs = new FileStream(outFile, FileMode.Create))
        {
            JpegOptions jpegOptions = new JpegOptions();
            CadRasterizationOptions options = new CadRasterizationOptions();
            options.Layouts = new string[] { image.Pages[0].Name };
            options.Layers = new[] { layer.Name.AsciiString };
            options.DrawType = CadDrawTypeMode.UseObjectColor;
            jpegOptions.VectorRasterizationOptions = options;
            image.Save(fs, jpegOptions);
        }
    }
}
```

### 另请参阅

* class [DwfLayersList](../../dwflayerslist/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

