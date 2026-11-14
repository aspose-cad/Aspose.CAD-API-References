---
title: "SvgOptions 类"
linktitle: "SvgOptions"
articleTitle: "SvgOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.SvgOptions 类。SVG 文件格式创建选项。"
type: docs
weight: 520
url: "/net/aspose.cad.imageoptions/svgoptions/"
keywords: "SvgOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SvgOptions class

SVG 文件格式创建选项。

```csharp
public class SvgOptions : ImageOptionsBase, ITextAsShapesOptions
```

## 示例

// 渲染已加载的文件并保存为 SVG

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
    SvgOptions opt = new SvgOptions();

    opt.VectorRasterizationOptions = cadRasterizationOptions;
    cadRasterizationOptions.DrawType = CadDrawTypeMode.UseObjectColor;
    img.Save(outSvg, opt);
}
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgOptions](svgoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Callback](../../aspose.cad.imageoptions/svgoptions/callback/) { get; set; } | 获取或设置回调，可用于根据用户需求存储图像和字体的二进制数据 |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [ExportEntityIDs](../../aspose.cad.imageoptions/svgoptions/exportentityids/) { get; set; } | 是否在输出中包含源文件实体 ID - 需要针对每种源格式的特定支持 |
| [ExportLayers](../../aspose.cad.imageoptions/svgoptions/exportlayers/) { get; set; } | 是否向导出实体添加图层信息 - 需要针对每种源格式的特定支持 |
| [GroupingMode](../../aspose.cad.imageoptions/svgoptions/groupingmode/) { get; set; } | 是否对对象进行分组 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [MinimumAbsoluteNonscaledLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumabsolutenonscaledlinewidth/) { get; set; } | 像素宽度小于此值的线将在绝对重新缩放阈值下被重新缩放 |
| [MinimumLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumlinewidth/) { get; set; } | 相对于最小未重新缩放线宽的线的最小宽度。如果使用重新缩放（默认情况下），宽度为 0 的线将以此宽度绘制，线条宽度超过该值时会加粗绘制，直至达到重新缩放阈值，超过阈值的线条则不会被重新缩放。 |
| [MinimumRelativeLinewidthRatio](../../aspose.cad.imageoptions/svgoptions/minimumrelativelinewidthratio/) { get; set; } | 如果使用相对重新缩放阈值，宽度小于 image's size\\minimumRelativeLinewidthRatio 的线将被重新缩放。较小的维度被选为图像尺寸。 |
| [OmitDeclaration](../../aspose.cad.imageoptions/svgoptions/omitdeclaration/) { get; set; } | 是否省略 DOCTYPE 声明 - 嵌入式 SVG 不需要它。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| [RescaleSubpixelLinewidths](../../aspose.cad.imageoptions/svgoptions/rescalesubpixellinewidths/) { get; set; } | 是否应重新缩放子像素线宽。如果设置为 true，宽度小于其他选项指定的线将被加粗绘制，逐渐逼近最小宽度。 |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| override [TargetFormat](../../aspose.cad.imageoptions/svgoptions/targetformat/) { get; } |  |
| [TextAsShapes](../../aspose.cad.imageoptions/svgoptions/textasshapes/) { get; set; } | 获取或设置一个值，指示文本是否必须转换为形状。默认情况下，文本会被转换为形状，从而不可选择。 |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [UseAbsoluteRescaling](../../aspose.cad.imageoptions/svgoptions/useabsoluterescaling/) { get; set; } | 是否应将最小未重新缩放的线宽相对于整个图像尺寸定义（false）或以像素定义（true）。如果为 false，用于指定当线尚未被放大重新缩放时图像尺寸与线宽的最大比例。如果为 true，用于指定以像素为单位的最小未缩放宽度。 |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

### 另请参阅

* [ImageOptionsBase](../imageoptionsbase/)
* class [ImageOptionsBase](../imageoptionsbase/)
* interface [ITextAsShapesOptions](../itextasshapesoptions/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

