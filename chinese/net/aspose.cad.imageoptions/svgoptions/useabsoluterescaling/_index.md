---
title: "SvgOptions.UseAbsoluteRescaling"
linktitle: "UseAbsoluteRescaling"
articleTitle: "UseAbsoluteRescaling"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。是否应将最小未重新缩放的线宽相对于整个图像大小（如果为 false）或以像素为单位（如果为 true）进行定义。如果为 false，使用来..."
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions/svgoptions/useabsoluterescaling/"
product_version: "26.9"
---
## SvgOptions.UseAbsoluteRescaling property

是否应将最小未重新缩放的线宽相对于整个图像大小（如果为 false）或以像素为单位（如果为 true）进行定义。
如果为 false，使用它来指定图像大小与线宽的最大比例，当线条尚未被放大重新缩放时。
如果为 true，使用它来指定以像素为单位的最小未缩放宽度。

```csharp
public bool UseAbsoluteRescaling { get; set; }
```

## 示例

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();

    cadRasterizationOptions.PageWidth = 1000;
    cadRasterizationOptions.PageHeight = 1000; // as units are not set, the size is in pixels

    SvgOptions opt = new SvgOptions();
    opt.UseAbsoluteRescaling = false; //using relative rescaling treshold
    opt.MinimumRelativeLinewidthRatio = 5000; //As result, lines thinner than 1/5th of a pixel would be made thicker, approaching the thickness of 1/5th of a pixel
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
} 


using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();

    cadRasterizationOptions.PageWidth = 1000;
    cadRasterizationOptions.PageHeight = 1000; // as units are not set, the size is in pixels

    SvgOptions opt = new SvgOptions();
    opt.UseAbsoluteRescaling = true; //using absolute rescaling treshold
    opt.MinimumAbsoluteNonscaledLinewidth = 5; //As result, lines thinner than 5 pixels wide would be made thicker, approaching the thickness of 5 pixels
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
}
```

### 另请参阅

* [MinimumRelativeLinewidthRatio](../minimumrelativelinewidthratio/)
* [MinimumAbsoluteNonscaledLinewidth](../minimumabsolutenonscaledlinewidth/)
* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

