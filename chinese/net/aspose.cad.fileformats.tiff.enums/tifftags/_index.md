---
title: "TiffTags 枚举"
linktitle: "TiffTags"
articleTitle: "TiffTags"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Tiff.Enums.TiffTags 枚举。tiff 标签枚举。"
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.tiff.enums/tifftags/"
product_version: "26.9"
---
## TiffTags enumeration

tiff 标记枚举。

```csharp
public enum TiffTags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SubFileType | `254` | 子文件数据描述符。 |
| OsubfileType | `255` | [已被 TIFF rev. 5.0 废弃] |
| ImageWidth | `256` | 图像宽度（像素）。 |
| ImageLength | `257` | 图像高度（像素）。 |
| BitsPerSample | `258` | 每通道位数（样本）。 |
| Compression | `259` | 数据压缩技术。 |
| Photometric | `262` | 光度解释。 |
| Thresholding | `263` | [已被 TIFF rev. 5.0 废弃] |
| CellWidth | `264` | [已被 TIFF rev. 5.0 废弃] |
| CellLength | `265` | [已被 TIFF rev. 5.0 废弃] |
| FillOrder | `266` | 字节内的数据顺序。 |
| DocumentName | `269` | 保存图像的文档名称。 |
| ImageDescription | `270` | 图像信息。 |
| Make | `271` | 扫描仪制造商名称。 |
| Model | `272` | 扫描仪型号名称/编号。 |
| StripOffsets | `273` | 数据条带的偏移量。 |
| Orientation | `274` | [已被 TIFF rev. 5.0 废弃] |
| SamplesPerPixel | `277` | 每像素样本数。 |
| RowsPerStrip | `278` | 每条数据的行数。 |
| StripByteCounts | `279` | 条带的字节计数。 |
| MinSampleValue | `280` | [已被 TIFF rev. 5.0 废弃] |
| MaxSampleValue | `281` | [已被 TIFF rev. 5.0 废弃] |
| Xresolution | `282` | X 方向像素/分辨率。 |
| Yresolution | `283` | Y 方向像素/分辨率。 |
| PlanarConfig | `284` | 存储组织。 |
| PageName | `285` | 图像来源的页面名称。 |
| Xposition | `286` | 图像左侧的 X 页面偏移。 |
| Yposition | `287` | 图像左侧的 Y 页面偏移。 |
| FreeOffsets | `288` | [已被 TIFF rev. 5.0 废弃] |
| FreeByteCounts | `289` | [已被 TIFF rev. 5.0 废弃] |
| GrayResponseUnit | `290` | [已被 TIFF rev. 6.0 弃用] |
| GrayResponseCurve | `291` | [已被 TIFF rev. 6.0 弃用] |
| T4Options | `292` | TIFF 6.0 正式名称别名为 GROUP3OPTIONS。CCITT Group 3 传真编码的选项。32 标志位。 |
| T6Options | `293` | CCITT Group 4 传真编码的选项。32 标志位。TIFF 6.0 正式名称别名为 GROUP4OPTIONS。 |
| ResolutionUnit | `296` | 分辨率的单位。 |
| PageNumber | `297` | 多页的页码。 |
| ColorResponseUnit | `300` | [已被 TIFF rev. 6.0 弃用] |
| TransferFunction | `301` | 色度信息。 |
| Software | `305` | 名称 &amp; 发行。 |
| DateTime | `306` | 创建日期和时间。 |
| Artist | `315` | 图像的创建者。 |
| HostComputer | `316` | 创建时使用的机器。 |
| Predictor | `317` | 使用 LZW 的预测方案。 |
| WhitePoint | `318` | 图像白点。 |
| PrimaryChromaticities | `319` | 主要色度。 |
| ColorMap | `320` | 调色板图像的 RGB 映射。 |
| HalftoneHints | `321` | 高光和阴影信息。 |
| TileWidth | `322` | 瓦片宽度（像素）。 |
| TileLength | `323` | 瓦片高度（像素）。 |
| TileOffsets | `324` | 数据瓦片的偏移量。 |
| TileByteCounts | `325` | 瓦片的字节计数。 |
| BadFaxLines | `326` | 像素计数错误的行。 |
| CleanFaxData | `327` | 重新生成的行信息。 |
| ConsecutiveBadFaxLines | `328` | 最大连续错误行数。 |
| SubIfd | `330` | 子图像描述符。 |
| InkSet | `332` | 分离图像中的墨水。 |
| InkNames | `333` | 墨水的 ASCII 名称。 |
| NumberOfInks | `334` | 墨水数量。 |
| DotRange | `336` | 0% 和 100% 点代码。 |
| TargetPrinter | `337` | 分离目标。 |
| ExtraSamples | `338` | 关于额外样本的信息。 |
| SampleFormat | `339` | 数据样本格式。 |
| SminSampleValue | `340` | 变量 MinSampleValue。 |
| SmaxSampleValue | `341` | 变量 MaxSampleValue。 |
| TransferRange | `342` | 变量 TransferRange。 |
| ClipPath | `343` | ClipPath。由 Adobe TIFF 技术说明 2 在 TIFF rev 6.0 之后引入。 |
| Xclippathunits | `344` | XClipPathUnits。由 Adobe TIFF 技术说明 2 在 TIFF rev 6.0 之后引入。 |
| Yclippathunits | `345` | YClipPathUnits。由 Adobe TIFF 技术说明 2 在 TIFF rev 6.0 之后引入。 |
| Indexed | `346` | Indexed。由 Adobe TIFF 技术说明 3 在 TIFF rev 6.0 之后引入。 |
| JpegTables | `347` | JPEG table stream。由 TIFF rev 6.0 之后引入。 |
| OpiProxy | `351` | OPI Proxy。由 Adobe TIFF 技术说明在 TIFF rev 6.0 之后引入。 |
| JpegProc | `512` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegInerchangeFormat | `513` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegInterchangeFormatLength | `514` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegRestartInterval | `515` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegLosslessPredictors | `517` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegPointTransform | `518` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegQTables | `519` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegDCtables | `520` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| JpegACtables | `521` | [已被技术说明 #2 废弃，该说明指定了修订后的 JPEG-in-TIFF 方案] |
| YcbcrCoefficients | `529` | RGB -> YCbCr 转换。 |
| YcbcrSubSampling | `530` | YCbCr 子采样因子。 |
| YcbcrPositioning | `531` | 子采样定位。 |
| ReferenceBlackWhite | `532` | 色度信息。 |
| XmlPacket | `700` | XML packet。由 Adobe XMP 规范（2004 年 1 月）在 TIFF rev 6.0 之后引入。 |
| OpiImageid | `32781` | OPI ImageID。由 Adobe TIFF 技术说明在 TIFF rev 6.0 之后引入。 |
| Refpts | `32953` | 图像参考点。私有标签已注册至 Island Graphics。 |
| Copyright | `33432` | 版权字符串。此标签列在 TIFF rev. 6.0 中，所有权未知。 |
| PhotoshopResources | `34377` | Photoshop 图像资源。 |
| IccProfile | `34675` | 嵌入的 ICC 设备配置文件 |
| ExifIfdPointer | `34665` | 指向 Exif IFD 的指针。 |
| XPTitle | `40091` | 关于图像的信息，供 Windows Explorer 使用。如果存在 ImageDescription 标签，Windows Explorer 将忽略 XPTitle。 |
| XPComment | `40092` | 图像注释，供 Windows Explorer 使用。 |
| XPAuthor | `40093` | 图像作者，供 Windows Explorer 使用。如果存在 Artist 标签，Windows Explorer 将忽略 XPAuthor。 |
| XPKeywords | `40094` | 图像关键字，供 Windows Explorer 使用。 |
| XPSubject | `40095` | 主题图像，供 Windows Explorer 使用。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Tiff.Enums](../../aspose.cad.fileformats.tiff.enums/)
* assembly [Aspose.CAD](../../)

