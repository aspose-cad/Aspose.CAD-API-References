---
title: "DgnImage.Width"
linktitle: "宽度"
articleTitle: "宽度"
second_title: "Aspose.CAD for .NET API 参考"
description: "DgnImage 属性。获取图像宽度。定义图像中所有图形对象左侧最点与右侧最点之间的 X 轴距离..."
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.dgn/dgnimage/width/"
product_version: "26.9"
---
## DgnImage.Width property

获取图像宽度。
定义图像中所有图形对象最左点与最右点之间的 X 轴距离。
距离的单位对应属性 [`UnitType`](../../../aspose.cad/image/unittype/) 的值。

```csharp
public override int Width { get; }
```

### Property Value

图像宽度。

## 示例

使用图像宽度值设置光栅化选项。

```csharp
string fileName = "ExampleFile; 
string file = string.Format("{0}.dgn", fileName);
string outPath = string.Format("{0}.pdf", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DgnImage image = (DgnImage) Image.Load(inStream))
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

* class [DgnImage](../)
* namespace [Aspose.CAD.FileFormats.Dgn](../../../aspose.cad.fileformats.dgn/)
* assembly [Aspose.CAD](../../../)

