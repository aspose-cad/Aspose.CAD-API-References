---
title: "SvgOptions.MinimumRelativeLinewidthRatio"
linktitle: "MinimumRelativeLinewidthRatio"
articleTitle: "MinimumRelativeLinewidthRatio"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。宽度小于图像大小\\minimumRelativeLinewidthRatio 的线条将在使用相对重新缩放阈值时被重新缩放。更小的..."
type: docs
weight: 60
url: "/net/aspose.cad.imageoptions/svgoptions/minimumrelativelinewidthratio/"
product_version: "26.9"
---
## SvgOptions.MinimumRelativeLinewidthRatio property

如果使用相对重新缩放阈值，宽度小于 image's size\\minimumRelativeLinewidthRatio 的线将被重新缩放。较小的维度被选为图像尺寸。

```csharp
public float MinimumRelativeLinewidthRatio { get; set; }
```

## 示例

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();

    cadRasterizationOptions.PageWidth = 1000;
    cadRasterizationOptions.PageHeight = 1000; // as units are not set, the size is in pixels

    SvgOptions opt = new SvgOptions();
    opt.UseAbsoluteRescaling = false; //using relative rescaling limit
    opt.MinimumRelativeLinewidthRatio = 5000; //As result, lines thinner than 1/5th of a pixel would be made thicker, approaching the thickness of 1/5th of a pixel
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
}
```

### 另请参阅

* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

