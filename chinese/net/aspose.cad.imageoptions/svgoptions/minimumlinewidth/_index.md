---
title: "SvgOptions.MinimumLinewidth"
linktitle: "MinimumLinewidth"
articleTitle: "MinimumLinewidth"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。相对于最小未重新缩放线宽的线的最小宽度。如果重新缩放，宽度为 0 的线将使用此宽度绘制..."
type: docs
weight: 80
url: "/net/aspose.cad.imageoptions/svgoptions/minimumlinewidth/"
product_version: "26.9"
---
## SvgOptions.MinimumLinewidth property

相对于最小未重新缩放线宽的线的最小宽度。
如果使用重新缩放（默认情况下即使用），宽度为 0 的线将以此宽度绘制；比该宽度更粗的线会被绘制得更粗，直到达到重新缩放阈值；超过该阈值的更粗线将不再重新缩放。

```csharp
public float MinimumLinewidth { get; set; }
```

## 示例

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();

    cadRasterizationOptions.PageWidth = 1000;
    cadRasterizationOptions.PageHeight = 1000; // as units are not set, the size is in pixels

    SvgOptions opt = new SvgOptions();
    opt.UseAbsoluteRescaling = true; //using absolute rescaling limit
    opt.MinimumAbsoluteNonscaledLinewidth = 5; //As result, lines thinner than 5 pixels wide would be made thicker, approaching the thickness of 5 pixels
    opt.MinimumLinewidth = 0.2f; // As result, lines with width of 0 will be drawn with width of 1 pixel. A line with source width of 1 pixel would be rescaled to be 1.8 pixels wide
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
}
```

### 另请参阅

* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

