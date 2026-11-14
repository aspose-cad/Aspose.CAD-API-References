---
title: "JpegOptions 类"
linktitle: "JpegOptions"
articleTitle: "JpegOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.JpegOptions 类。jpeg 文件格式创建选项。"
type: docs
weight: 290
url: "/net/aspose.cad.imageoptions/jpegoptions/"
keywords: "JpegOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## JpegOptions class

jpeg 文件格式创建选项。

```csharp
public class JpegOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | 初始化 `JpegOptions` 类的新实例。 |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | 初始化 `JpegOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [CmykColorProfile](../../aspose.cad.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg 图像的目标 CMYK 色彩配置文件。用于保存图像。必须与 RGBColorProfile 配对以实现正确的颜色转换。 |
| [ColorType](../../aspose.cad.imageoptions/jpegoptions/colortype/) { get; set; } | 获取或设置 jpeg 图像的颜色类型。 |
| [Comment](../../aspose.cad.imageoptions/jpegoptions/comment/) { get; set; } | 获取或设置 jpeg 文件注释。 |
| [CompressionType](../../aspose.cad.imageoptions/jpegoptions/compressiontype/) { get; set; } | 获取或设置压缩类型。 |
| [ExifData](../../aspose.cad.imageoptions/jpegoptions/exifdata/) { get; set; } | 获取或设置 exif 数据容器 |
| [Jfif](../../aspose.cad.imageoptions/jpegoptions/jfif/) { get; set; } | 获取或设置 jfif。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [Quality](../../aspose.cad.imageoptions/jpegoptions/quality/) { get; set; } | 获取或设置图像质量。 |
| [RdOptSettings](../../aspose.cad.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | 获取或设置 RD 优化器设置。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [RgbColorProfile](../../aspose.cad.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg 图像的目标 RGB 色彩配置文件。用于保存图像。必须与 CMYKColorProfile 配对以实现正确的颜色转换。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [ScaledQuality](../../aspose.cad.imageoptions/jpegoptions/scaledquality/) { get; } | 缩放质量。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/jpegoptions/targetformat/) { get; } |  |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.cad.imageoptions/jpegoptions/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

### 另请参阅

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

