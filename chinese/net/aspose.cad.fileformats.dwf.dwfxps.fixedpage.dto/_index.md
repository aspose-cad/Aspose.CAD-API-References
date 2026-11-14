---
title: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO"
linktitle: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO"
articleTitle: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO"
second_title: "Aspose.CAD for .NET API 参考"
description: "该命名空间包含 FixedPage DTO 模型的实体。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/"
keywords: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Overview

该命名空间包含 [FixedPage](./fixedpage/) DTO 模型的实体。

是 [Aspose.CAD for .NET](../) API 参考的一部分。

## 类

| 类 | 描述 |
| --- | --- |
| [ArcSegment](./arcsegment/) | 弧段。表示两个点之间的椭圆弧。 |
| [Brush](./brush/) | 画笔。Brush 用于绘制由 Path 元素定义的几何形状内部以及由 Glyphs 元素渲染的字符。它们还用于在 Canvas.OpacityMask、Path.OpacityMask 和 Glyphs.OpacityMask 属性元素中定义 alpha 透明度遮罩。 |
| [Canvas](./canvas/) | 画布。Canvas 元素将元素组合在一起。Glyphs 和 Path 元素可以在画布中分组，以便被识别为一个单元（如超链接目标），或对每个子元素和祖先元素应用组合属性值。 |
| [FixedPage](./fixedpage/) | 固定页面。FixedPage 元素包含页面的内容，并且是 FixedPage 部分的根元素。固定页面包含共同构成页面上所有标记渲染基础的元素：Paths、Glyphs 以及可选的 Canvas 分组元素。 |
| [FixedPageFileParser](./fixedpagefileparser/) | 固定页面文件解析器。将 XML FixedPage 文件中的 DTO 对象反序列化。 |
| [Geometry](./geometry/) | 几何体。几何体用于构建几何形状的可视化表示。几何体中最小的原子单位是段（segment）。段可以是直线或曲线。一个或多个段组合成路径图形（path figure）定义。路径图形是由连续段组成的单一形状。一个或多个路径图形共同定义整个路径几何体。路径几何体可以定义用于其组成路径图形的填充算法。 |
| [Glyphs](./glyphs/) | 字形。Glyphs 元素表示来自单一字体的统一格式文本序列。它提供准确渲染所需的信息，并支持查看器中的搜索和选择功能。 |
| [GradientStop](./gradientstop/) | 渐变停止点。GradientStop 元素被 LinearGradientBrush 和 RadialGradientBrush 元素共同使用，用于定义渲染渐变时颜色渐进的位置和范围。对于线性渐变画笔，偏移值 0.0 映射到渐变的起始点，偏移值 1.0 映射到结束点。介于两者之间的偏移值在这两个点之间进行插值以确定其位置。对于径向渐变画笔，偏移值 0.0 映射到渐变的起点位置，偏移值 1.0 映射到由中心、x 半径和 y 半径决定的椭圆周界。0.0 到 1.0 之间的偏移值位于这些点之间的插值位置。 |
| [ImageBrush](./imagebrush/) | 图像画笔。ImageBrush 元素用于用图像填充区域。图像在由图像分辨率指定的坐标空间中定义。图像必须引用文档包内的 JPEG、PNG、TIFF 或 JPEG XR 图像部件。 |
| [LinearGradientBrush](./lineargradientbrush/) | 线性渐变画笔。LinearGradientBrush 元素用于沿向量指定线性渐变画笔。用线性渐变填充区域。 |
| [MatrixTransform](./matrixtransform/) | 矩阵变换。创建任意仿射矩阵变换，以在二维平面中操作对象或坐标系。 |
| [Path](./path/) | 路径。定义将在页面上渲染的单个图形效果。它使用画笔绘制几何体并在其周围绘制描边。 |
| [PathFigure](./pathfigure/) | 路径图形。PathFigure 元素由一个或多个直线或曲线段组成。段元素定义路径图形的形状。第一个段元素的起始点在路径图形的 StartPoint 属性中指定。每个段元素的终点是下一个段元素的起始点。 |
| [PathGeometry](./pathgeometry/) | 路径几何体。PathGeometry 元素包含一组路径图形，可通过 Figures 属性或子 PathFigure 元素指定。生产者不得同时使用 Figures 属性和子 PathFigure 元素来指定几何体的路径图形。 |
| [PolyBezierSegment](./polybeziersegment/) | 多段贝塞尔段。由一系列 BÉZIER 段组成。 |
| [PolyLineSegment](./polylinesegment/) | 多段折线段。指定一组点，在这些点之间绘制直线。 |
| [PolyQuadraticBezierSegment](./polyquadraticbeziersegment/) | 多项式二次贝塞尔段。由一系列二次 BÉZIER 段组成。 |
| [RadialGradientBrush](./radialgradientbrush/) | 径向渐变画刷。 |
| [ResourceDictionary](./resourcedictionary/) | 资源字典。FixedPage.Resources 和 Canvas.Resources 属性元素恰好包含一个 ResourceDictionary 元素。资源字典包含资源定义元素条目。每个资源定义在 x:Key 属性中指定键，该键在资源字典的作用域内是唯一的。x:Key 属性包含在资源字典中。 |
| [Resources](./resources/) | 资源。Canvas 和 FixedPage 元素可以携带资源字典。资源字典通过 FixedPage.Resources 或 Canvas.Resources 属性元素在标记中表达。必须在资源字典中指定各个资源值。 |
| [SolidColorBrush](./solidcolorbrush/) | 实色画刷。SolidColorBrush 元素用于用纯色填充已定义的几何区域。如果颜色包含 alpha 分量，它会以乘法方式与相应的 Opacity 属性相结合。 |
| [Transform](./transform/) | 变换。OpenXPS 文档标记支持通过 RenderTransform 和 Transform 属性表达的仿射变换。仿射变换表示为六个实数的列表：m11、m12、m21、m22、OffsetX、OffsetY。RenderTransform 和 Transform 属性均使用 MatrixTransform 元素作为其值，指定对本地坐标空间的仿射矩阵变换。可以使用简写的矩阵变换语法来指定 RenderTransform 或 Transform 属性值。 |
| [Visual](./visual/) | 视觉。指定用于绘制视觉内容的 Path 元素、Glyphs 元素或 Canvas 元素。 |
| [VisualBrush](./visualbrush/) | 视觉画刷。VisualBrush 元素用于用绘图填充区域。绘图可以指定为 VisualBrush.Visual 属性元素或资源引用。绘图内容可以恰好包含一个 Canvas、Path 或 Glyphs 元素及其子元素和后代元素。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ClrIntMode](./clrintmode/) | CLR INT 模式。指定用于颜色插值的伽马函数。如果指定了 alpha 分量，则不应对其应用伽马调整。 |
| [DashCap](./dashcap/) | 虚线端帽。被描边的路径的有效渲染变换用于变换虚线轮廓的控制点。 |
| [EdgeMode](./edgemode/) | 边缘模式。EdgeMode 可以指示在不执行抗锯齿的情况下渲染元素及其所有子元素和后代元素的内容，包括子画刷及其内容以及通过资源字典引用包含的内容。 |
| [FillRule](./fillrule/) | 填充规则。FillRule 属性指定填充算法。几何体的填充区域通过获取所有包含的路径图形并应用填充算法来确定封闭区域。填充算法决定几何形状的交叉区域如何组合形成一个区域。 |
| [LineCap](./linecap/) | 线端帽。指定线端帽的外观。 |
| [LineJoin](./linejoin/) | 线连接。指定线连接的外观。 |
| [MappingMode](./mappingmode/) | 映射模式。指定中心、x 半径和 y 半径在有效坐标空间中定义（包括画刷的 Transform 属性）。 |
| [SpreadMethod](./spreadmethod/) | 扩展方式。描述画刷应如何填充主初始渐变区域之外的内容区域。 |
| [StyleSimulations](./stylesimulations/) | 样式模拟。可以使用 StyleSimulations 属性对字形的形状应用合成样式模拟。样式模拟可以在字体的设计样式之外额外应用。StyleSimulations 属性的默认值为 None，此时字形的形状不会被修改，保持原始设计。 |
| [SweepDirection](./sweepdirection/) | 扫掠方向。决定在两条可能的弧线（由 Large Arc Flag 选择）中使用哪一条。从起始点开始，一条弧线沿正向（顺时针）方向绘制，另一条沿负向（逆时针）方向绘制。 |
| [TileMode](./tilemode/) | 平铺模式。指定在填充几何体时如何执行平铺。 |
| [ViewUnits](./viewunits/) | 视图单位。指定视图坐标与包含坐标空间之间的关系。 |

