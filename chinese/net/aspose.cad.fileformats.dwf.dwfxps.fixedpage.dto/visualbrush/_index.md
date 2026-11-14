---
title: "VisualBrush 类"
linktitle: "VisualBrush"
articleTitle: "VisualBrush"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.VisualBrush class. 视觉画刷。VisualBrush 元素用于用绘图填充区域。绘图..."
type: docs
weight: 370
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/"
keywords: "VisualBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## VisualBrush class

视觉画刷。
VisualBrush 元素用于用绘图填充区域。
绘图可以指定为 VisualBrush 的 [Visual](../visual/) 属性元素，或作为资源引用。
绘图内容可以恰好包含一个 [Canvas](../canvas/)、[Path](../path/) 或 [Glyphs](../glyphs/) 元素，以及该元素的子元素和后代元素。

```csharp
public class VisualBrush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VisualBrush](visualbrush/)() | 初始化 `VisualBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/opacity/) { get; set; } | 获取或设置不透明度。定义画刷填充的统一透明度。值的范围为 0（完全透明）到 1（完全不透明），包括端点。超出此范围的值无效。 |
| [TileMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/tilemode/) { get; set; } | 获取或设置平铺模式。指定内容在填充区域中的平铺方式。有效值为 None、Tile、FlipX、FlipY 和 FlipXY。 |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/transform/) { get; set; } | 获取或设置变换。描述应用于画刷坐标空间的矩阵变换。Transform 属性与当前有效渲染变换连接，以产生相对于画刷的有效渲染变换。画刷的视口使用该局部有效渲染变换进行转换。 |
| [Viewbox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewbox/) { get; set; } | 获取或设置视图框。指定画刷源内容的位置和尺寸。指定四个用逗号分隔的实数 (x, y, Width, Height)，其中宽度和高度为非负数。视图框定义了在 VisualBrush.Visual 属性元素中指定的元素的默认坐标系。视图框的四角映射到视口的四角，从而为画刷的源内容提供默认的裁剪和变换。 |
| [ViewboxUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewboxunits/) { get; set; } | 获取或设置视图框单位。指定视图框坐标与其所在坐标空间的关系。 |
| [Viewport](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewport/) { get; set; } | 获取或设置视口。指定在包含坐标空间中，主画刷平铺的区域（可能会重复）用于填充画刷所应用的区域。指定四个用逗号分隔的实数 (x, y, Width, Height)，其中宽度和高度为非负数。通过调整 x 和 y 值来控制画刷图案的对齐方式。 |
| [ViewportUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewportunits/) { get; set; } | 获取或设置视口单位。指定视口坐标与其所在坐标空间的关系。 |
| [Visual](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visual/) { get; set; } | 获取或设置 visual。指定对在资源字典中定义的 Path、Glyphs 或 Canvas 元素的资源引用，用于绘制画刷的源内容。 |
| [VisualBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visualbrushtransform/) { get; set; } | 获取或设置 visual brush 变换。描述应用于画刷坐标空间的矩阵变换。Transform 属性与当前有效渲染变换连接，以产生相对于画刷的有效渲染变换。画刷的视口使用该局部有效渲染变换进行转换。 |
| [VisualBrushVisual](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visualbrushvisual/) { get; set; } | 获取或设置 visual brush visual。指定用于绘制画刷源内容的 Path 元素、Glyphs 元素或 Canvas 元素。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

