---
title: "TiffOptions.ColorMap"
linktitle: "ColorMap"
articleTitle: "ColorMap"
second_title: "Aspose.CAD for .NET API 参考"
description: "TiffOptions 属性。获取或设置颜色映射。"
type: docs
weight: 220
url: "/net/aspose.cad.imageoptions/tiffoptions/colormap/"
product_version: "26.9"
---
## TiffOptions.ColorMap property

获取或设置颜色映射表。

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

颜色映射。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | value |
| [TiffImageException](../../../aspose.cad.cadexceptions.imageformats/tiffimageexception/) | 颜色映射只能在每像素样本数等于 1 时定义。或 未定义每样本位数。 |
| ArgumentOutOfRangeException | value;数组长度必须符合以下公式：3 * (2**BitsPerSample)。 |

### 另请参阅

* class [TiffOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

