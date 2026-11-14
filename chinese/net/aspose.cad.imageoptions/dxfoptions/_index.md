---
title: "DxfOptions 类"
linktitle: "DxfOptions"
articleTitle: "DxfOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.DxfOptions 类。DXF 格式输出创建选项的类"
type: docs
weight: 140
url: "/net/aspose.cad.imageoptions/dxfoptions/"
keywords: "DxfOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DxfOptions class

DXF 格式输出创建选项的类

```csharp
public class DxfOptions : ImageOptionsBase, ITextAsLinesOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DxfOptions](dxfoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BezierPointCount](../../aspose.cad.imageoptions/dxfoptions/bezierpointcount/) { get; set; } | 如果 OutputMode 为 Render，将贝塞尔曲线转换为折线时生成多少点 |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [ConvertMeshToLines](../../aspose.cad.imageoptions/dxfoptions/convertmeshtolines/) { get; set; } | 获取或设置一个值，指示是否应将网格几何（例如来自 DWF 的 3D 外壳）导出为线（线框），而不是 MESH 实体，从而生成的 DXF 仅包含线。默认启用：除非将此设置为 `false`，否则 DWF 到 DXF 的转换永不生成网格。 |
| [ConvertTextBeziers](../../aspose.cad.imageoptions/dxfoptions/converttextbeziers/) { get; set; } | 是否在 OutputMode 为 Render 时将文本轮廓中的贝塞尔曲线转换为多点折线（如果为 false 则转换为 4 点） |
| [DxfFileFormat](../../aspose.cad.imageoptions/dxfoptions/dxffileformat/) { get; set; } | 获取或设置 DXF 文件格式。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [MergeLinesInsideContour](../../aspose.cad.imageoptions/dxfoptions/mergelinesinsidecontour/) { get; set; } | 获取或设置是否应将形成轮廓的折线序列合并为单个折线。 |
| [OriginPosition](../../aspose.cad.imageoptions/dxfoptions/originposition/) { get; set; } | 获取或设置原点位置。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [PrettyFormatting](../../aspose.cad.imageoptions/dxfoptions/prettyformatting/) { get; set; } |  |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/dxfoptions/targetformat/) { get; } |  |
| [TextAsLines](../../aspose.cad.imageoptions/dxfoptions/textaslines/) { get; set; } | 获取或设置一个值，指示在 OutputMode 为 Render 时是否将 [text as lines]。 |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [TryConvertToMesh](../../aspose.cad.imageoptions/dxfoptions/tryconverttomesh/) { get; set; } | 获取或设置一个值，指示是否尝试将文件格式转换为 MESH。 |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| [Version](../../aspose.cad.imageoptions/dxfoptions/version/) { get; set; } | 输出 DXF 格式的版本 |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

### 另请参阅

* [ImageOptionsBase](../imageoptionsbase/)
* class [ImageOptionsBase](../imageoptionsbase/)
* interface [ITextAsLinesOptions](../itextaslinesoptions/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

