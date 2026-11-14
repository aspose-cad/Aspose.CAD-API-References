---
title: "TiffExpectedFormat 枚举"
linktitle: "TiffExpectedFormat"
articleTitle: "TiffExpectedFormat"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Tiff.Enums.TiffExpectedFormat enum。预期的 tiff 文件格式。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.tiff.enums/tiffexpectedformat/"
product_version: "26.9"
---
## TiffExpectedFormat enumeration

预期的 tiff 文件格式。

```csharp
public enum TiffExpectedFormat
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 默认的 tiff 格式是不压缩，仅支持 B/W 1 bit per pixel 格式。您也可以使用此设置获取空选项，并使用您的标签或其他设置进行初始化。 |
| TiffLzwBw | `1` | 该 tiff 使用 LZW 压缩，仅支持 B/W 1 bit per pixel 格式。 |
| TiffLzwRgb | `2` | 该 tiff 使用 LZW 压缩，RGB 彩色格式。 |
| TiffLzwRgba | `3` | 该 tiff 使用 LZW 压缩，RGBA 带透明度的彩色格式。 |
| TiffLzwCmyk | `4` | 该 tiff LZW cmyk |
| TiffCcittFax3 | `5` | 该 tiff 使用 CCITT FAX3 编码。仅支持 B/W 1 bit per pixel 的该方案。 |
| TiffCcittFax4 | `6` | 该 tiff 使用 CCITT FAX4 编码。仅支持 B/W 1 bit per pixel 的该方案。 |
| TiffDeflateBw | `7` | 该 tiff 使用 deflate 压缩，仅支持 B/W 1 bit per pixel 格式。 |
| TiffDeflateRgb | `8` | 该 tiff 使用 deflate 压缩，RGB 彩色格式。 |
| TiffDeflateRgba | `9` | 该 tiff 使用 deflate 压缩，RGBA 彩色格式。 |
| TiffCcitRle | `10` | 该 tiff 使用 CCITT RLE 编码。仅支持 B/W 1 bit per pixel 的该方案。 |
| TiffJpegRgb | `11` | 该 tiff 使用 Jpeg 压缩，RGB 彩色格式。 |
| TiffJpegYCbCr | `12` | 该 tiff 使用 Jpeg 压缩，YCBCR 彩色格式。 |
| TiffNoCompressionBw | `13` | 未压缩的 tiff，仅支持 B/W 1 bit per pixel 格式。 |
| TiffNoCompressionRgb | `14` | 未压缩的 tiff，RGB 彩色格式。 |
| TiffNoCompressionRgba | `15` | 未压缩的 tiff，RGBA 带透明度的彩色格式。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Tiff.Enums](../../aspose.cad.fileformats.tiff.enums/)
* assembly [Aspose.CAD](../../)

