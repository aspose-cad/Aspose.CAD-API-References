---
title: "RadialGradientBrush 类"
linktitle: "RadialGradientBrush"
articleTitle: "RadialGradientBrush"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.RadialGradientBrush 类。径向渐变画笔。"
type: docs
weight: 260
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/"
keywords: "RadialGradientBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## RadialGradientBrush class

径向渐变画刷。

```csharp
public class RadialGradientBrush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RadialGradientBrush](radialgradientbrush/)() | 初始化 `RadialGradientBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Center](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/center/) { get; set; } | 获取或设置中心。指定径向渐变的中心点（即椭圆的中心）。径向渐变画笔在渐变起点和椭圆周长之间插值颜色。周长由中心和半径决定。 |
| [ColorInterpolationMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/colorinterpolationmode/) { get; set; } | 获取或设置颜色插值模式。指定颜色插值的伽马函数。如果指定了 alpha 分量，则不应对其进行伽马调整。 |
| [GradientOrigin](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/gradientorigin/) { get; set; } | 获取或设置渐变起点。指定径向渐变的起始点。 |
| [MappingMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/mappingmode/) { get; set; } | 获取或设置映射模式。指定中心、x 半径和 y 半径在有效坐标空间中定义（包括画笔的 Transform 属性）。 |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/opacity/) { get; set; } | 获取或设置不透明度。定义径向渐变的统一透明度。取值范围为 0（完全透明）到 1（完全不透明），包括两端。超出此范围的值无效。 |
| [RadialGradientBrushGradientStops](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radialgradientbrushgradientstops/) { get; set; } | 获取或设置径向渐变画笔的渐变停止点。保存一系列 GradientStop 元素。 |
| [RadialGradientBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radialgradientbrushtransform/) { get; set; } | 获取或设置径向渐变画笔的变换。描述应用于画笔坐标空间的矩阵变换。Transform 属性与当前有效渲染变换连接，以产生相对于画笔的有效渲染变换。中心、渐变起点、x 半径和 y 半径使用本地有效渲染变换进行变换。 |
| [RadiusX](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radiusx/) { get; set; } | 获取或设置 x 方向半径。指定定义径向渐变的椭圆在 x 维度上的半径。 |
| [RadiusY](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radiusy/) { get; set; } | 获取或设置 y 方向半径。指定定义径向渐变的椭圆在 y 维度上的半径。 |
| [SpreadMethod](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/spreadmethod/) { get; set; } | 获取或设置扩散方式。描述画笔应如何填充主初始渐变区域之外的内容区域。有效值为 Pad、Reflect 和 Repeat。 |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/transform/) { get; set; } | 获取或设置变换。描述应用于画笔坐标空间的矩阵变换。Transform 属性与当前有效渲染变换连接，以产生相对于画笔的有效渲染变换。由中心、渐变起点、x 半径和 y 半径值定义的椭圆使用本地有效渲染变换进行变换。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

