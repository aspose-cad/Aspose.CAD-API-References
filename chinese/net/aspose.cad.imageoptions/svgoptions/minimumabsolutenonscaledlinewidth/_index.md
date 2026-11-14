---
title: "SvgOptions.MinimumAbsoluteNonscaledLinewidth"
linktitle: "MinimumAbsoluteNonscaledLinewidth"
articleTitle: "MinimumAbsoluteNonscaledLinewidth"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。像素宽度小于此值的线将在绝对重新缩放阈值下被重新缩放。"
type: docs
weight: 70
url: "/net/aspose.cad.imageoptions/svgoptions/minimumabsolutenonscaledlinewidth/"
product_version: "26.9"
---
## SvgOptions.MinimumAbsoluteNonscaledLinewidth property

像素宽度小于此值的线将在绝对重新缩放阈值下被重新缩放

```csharp
public float MinimumAbsoluteNonscaledLinewidth { get; set; }
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
    opt.VectorRasterizationOptions = cadRasterizationOptions;
    img.Save(outFile, opt);
}
```

### 另请参阅

* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

