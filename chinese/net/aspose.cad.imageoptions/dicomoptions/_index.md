---
title: "DicomOptions 类"
linktitle: "DicomOptions"
articleTitle: "DicomOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.DicomOptions 类。DICOM 文件格式创建选项。"
type: docs
weight: 90
url: "/net/aspose.cad.imageoptions/dicomoptions/"
keywords: "DicomOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DicomOptions class

DICOM 文件格式创建选项。

```csharp
public class DicomOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DicomOptions](dicomoptions/)() | 初始化 `DicomOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [ColorType](../../aspose.cad.imageoptions/dicomoptions/colortype/) { get; set; } | 获取或设置颜色的类型。 |
| [Compression](../../aspose.cad.imageoptions/dicomoptions/compression/) { get; set; } | 获取或设置压缩。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/dicomoptions/targetformat/) { get; } |  |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

### 另请参阅

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

