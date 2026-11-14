---
title: "LinearGradientBrush 类"
linktitle: "LinearGradientBrush"
articleTitle: "LinearGradientBrush"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.LinearGradientBrush 类。线性渐变画刷。LinearGradientBrush 元素用于指定一个线性渐变..."
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/"
keywords: "LinearGradientBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## LinearGradientBrush class

线性渐变画刷。
LinearGradientBrush 元素用于沿向量指定线性渐变画刷。
使用线性渐变填充区域。

```csharp
public class LinearGradientBrush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/)() | 初始化 `LinearGradientBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorInterpolationMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/colorinterpolationmode/) { get; set; } | 获取或设置颜色插值模式。指定颜色插值的伽马函数。如果指定了 alpha 分量，则不应对其进行伽马调整。 |
| [EndPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/endpoint/) { get; set; } | 获取或设置结束点。指定线性渐变的结束点。线性渐变画刷在起始点和结束点之间插值颜色，其中起始点表示偏移量 0，结束点（EndPoint）表示偏移量 1。在 GradientStop 元素中指定的 Offset 属性值与起始点和结束点定义的 0 与 1 偏移量相关。 |
| [LinearGradientBrushGradientStops](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/lineargradientbrushgradientstops/) { get; set; } | 获取或设置线性渐变画刷的渐变停止点。保存一系列 GradientStop 元素。 |
| [LinearGradientBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/lineargradientbrushtransform/) { get; set; } | 获取或设置线性渐变画刷的变换。描述应用于画刷坐标空间的矩阵变换。Transform 属性与当前有效渲染变换串联，以产生相对于画刷的有效渲染变换。起始点和结束点使用本地有效渲染变换进行变换。 |
| [MappingMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/mappingmode/) { get; set; } | 获取或设置映射模式。指定起始点和结束点在有效坐标空间中定义（包括画刷的 Transform 属性）。 |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/opacity/) { get; set; } | 获取或设置不透明度。定义线性渐变的统一透明度。取值范围为 0（完全透明）到 1（完全不透明），包括端点。超出此范围的值无效。 |
| [SpreadMethod](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/spreadmethod/) { get; set; } | 获取或设置扩散方式。描述画笔应如何填充主初始渐变区域之外的内容区域。有效值为 Pad、Reflect 和 Repeat。 |
| [StartPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/startpoint/) { get; set; } | 获取或设置起始点。指定线性渐变的起始点。 |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/transform/) { get; set; } | 获取或设置变换。描述应用于画刷坐标空间的矩阵变换。画刷上的 Transform 属性与当前有效渲染变换串联，以产生相对于画刷的有效渲染变换。起始点和结束点使用本地有效渲染变换进行变换。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

