---
title: "ThumbnailResource 类"
linktitle: "ThumbnailResource"
articleTitle: "ThumbnailResource"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Psd.Resources.ThumbnailResource 类. 缩略图资源块。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.psd.resources/thumbnailresource/"
keywords: "ThumbnailResource, Aspose.CAD.FileFormats.Psd.Resources, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ThumbnailResource class

缩略图资源块。

```csharp
public class ThumbnailResource : ResourceBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | 初始化 `ThumbnailResource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsPixel](../../aspose.cad.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | 获取或设置位像素。 |
| override [DataSize](../../aspose.cad.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | 获取资源数据的字节大小。 |
| [Height](../../aspose.cad.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | 获取或设置缩略图的高度（像素）。 |
| [ID](../../aspose.cad.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| [JpegOptions](../../aspose.cad.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | 获取或设置 JPEG 选项。仅在缩略图资源保存为 JPEG 文件格式时适用。当定义为 RAW 格式时此选项无效。 |
| override [MinimalVersion](../../aspose.cad.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.cad.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。 |
| [PlanesCount](../../aspose.cad.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | 获取或设置平面计数。 |
| [Signature](../../aspose.cad.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为 '8BIM'。 |
| [Size](../../aspose.cad.fileformats.psd/resourceblock/size/) { get; } | 获取资源块的字节大小（包括其数据）。 |
| [SizeAfterCompression](../../aspose.cad.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | 获取或设置压缩后的大小。用于一致性检查。 |
| [ThumbnailArgb32Data](../../aspose.cad.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | 获取或设置 32 位 ARGB 缩略图数据。 |
| [ThumbnailData](../../aspose.cad.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | 获取或设置缩略图数据。 |
| [TotalSize](../../aspose.cad.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | 获取总数据大小。 |
| [Width](../../aspose.cad.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | 获取或设置缩略图的宽度（像素）。 |
| [WidthBytes](../../aspose.cad.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | 获取行宽（字节）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Save](../../aspose.cad.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| override [ValidateValues](../../aspose.cad.fileformats.psd.resources/thumbnailresource/validatevalues/)() | 验证资源值。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ResouceBlockSignature](../../aspose.cad.fileformats.psd/resourceblock/resouceblocksignature/) | 资源签名。 |

### 另请参阅

* class [ResourceBlock](../../aspose.cad.fileformats.psd/resourceblock/)
* namespace [Aspose.CAD.FileFormats.Psd.Resources](../../aspose.cad.fileformats.psd.resources/)
* assembly [Aspose.CAD](../../)

