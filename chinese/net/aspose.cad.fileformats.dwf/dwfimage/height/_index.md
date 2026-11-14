---
title: "DwfImage.Height"
linktitle: "高度"
articleTitle: "高度"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 属性。获取图像高度。定义图像中所有图形对象的最低点与最高点之间的 Y 轴距离，..."
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.dwf/dwfimage/height/"
product_version: "26.9"
---
## DwfImage.Height property

获取图像高度。
定义图像中所有图形对象的最低点与最高点之间的 Y 轴距离。
距离的单位对应属性 [`UnitType`](../../../aspose.cad/image/unittype/) 的值。

```csharp
public override int Height { get; }
```

### Property Value

图像高度。

## 示例

使用图像高度值来设置光栅化选项。

```csharp
string fileName = "ExampleFile; 
string file = string.Format("{0}.dwf", fileName);
string outPath = string.Format("{0}.pdf", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage) Image.Load(inStream))
{
    CadRasterizationOptions rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PageSize = new SizeF(image.Width, image.Height);
    rasterizationOptions.PageHeight = image.Height;
    rasterizationOptions.PageWidth = image.Width;
    rasterizationOptions.UnitType = image.UnitType;
    PdfOptions pdfOptions = new PdfOptions { VectorRasterizationOptions = rasterizationOptions };
    image.Save(outPath, pdfOptions);
}
```

### 另请参阅

* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

