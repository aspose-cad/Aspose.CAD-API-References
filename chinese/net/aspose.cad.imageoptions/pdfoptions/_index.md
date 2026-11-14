---
title: "PdfOptions 类"
linktitle: "PdfOptions"
articleTitle: "PdfOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.PdfOptions 类。PDF 选项。"
type: docs
weight: 390
url: "/net/aspose.cad.imageoptions/pdfoptions/"
keywords: "PdfOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PdfOptions class

PDF 选项。

```csharp
public class PdfOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfOptions](pdfoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [CorePdfOptions](../../aspose.cad.imageoptions/pdfoptions/corepdfoptions/) { get; set; } | 获取或设置核心 PDF 选项。 |
| [Is3DContent](../../aspose.cad.imageoptions/pdfoptions/is3dcontent/) { get; set; } | 获取或设置文档内容是否应表示为 3D 模型。允许将 U3D 内容直接导出为 PDF，以交互式 3D 注释对象的形式。生成的 PDF 文件将包含占据整个页面（含边距）的单个 3D 模型对象。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [PdfDocumentInfo](../../aspose.cad.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | 获取或设置文档的元数据。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/pdfoptions/targetformat/) { get; } |  |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

### 另请参阅

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

