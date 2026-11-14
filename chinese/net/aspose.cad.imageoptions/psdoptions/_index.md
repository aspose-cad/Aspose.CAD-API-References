---
title: "PsdOptions 类"
linktitle: "PsdOptions"
articleTitle: "PsdOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.PsdOptions 类。psd 文件格式创建选项。"
type: docs
weight: 420
url: "/net/aspose.cad.imageoptions/psdoptions/"
keywords: "PsdOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PsdOptions class

psd 文件格式创建选项。

```csharp
public class PsdOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | 初始化 `PsdOptions` 类的新实例。 |
| [PsdOptions](psdoptions/#constructor_1)(PsdOptions) | 初始化 `PsdOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [ChannelBitsCount](../../aspose.cad.imageoptions/psdoptions/channelbitscount/) { get; set; } | 获取或设置每个颜色通道的位数。 |
| [ChannelsCount](../../aspose.cad.imageoptions/psdoptions/channelscount/) { get; set; } | 获取或设置颜色通道计数。 |
| [ColorMode](../../aspose.cad.imageoptions/psdoptions/colormode/) { get; set; } | 获取或设置 PSD 颜色模式。 |
| [CompressionMethod](../../aspose.cad.imageoptions/psdoptions/compressionmethod/) { get; set; } | 获取或设置 PSD 压缩方法。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/psdoptions/targetformat/) { get; } |  |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| [Version](../../aspose.cad.imageoptions/psdoptions/version/) { get; set; } | 获取或设置 PSD 文件版本。 |
| override [XmpData](../../aspose.cad.imageoptions/psdoptions/xmpdata/) { get; set; } | 获取或设置 XMP 数据容器 |

### 另请参阅

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

