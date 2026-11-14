---
title: "SvgOptions.RescaleSubpixelLinewidths"
linktitle: "RescaleSubpixelLinewidths"
articleTitle: "RescaleSubpixelLinewidths"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。是否应重新缩放子像素线宽。如果设置为 true，则比其他选项指定的宽度更细的线将被绘制得更粗，..."
type: docs
weight: 40
url: "/net/aspose.cad.imageoptions/svgoptions/rescalesubpixellinewidths/"
product_version: "26.9"
---
## SvgOptions.RescaleSubpixelLinewidths property

是否应重新缩放子像素线宽。
如果设置为 true，则比其他选项指定的宽度更细的线将被绘制得更粗，逐渐逼近最小宽度。

```csharp
public bool RescaleSubpixelLinewidths { get; set; }
```

## 示例

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
    SvgOptions opt = new SvgOptions();
    opt.RescaleSubpixelLinewidths = false; //now lines with width in source file == 0 will not be visible
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
}
```

### 另请参阅

* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

