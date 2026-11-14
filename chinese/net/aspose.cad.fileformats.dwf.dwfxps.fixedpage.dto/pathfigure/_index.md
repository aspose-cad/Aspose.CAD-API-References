---
title: "PathFigure 类"
linktitle: "PathFigure"
articleTitle: "PathFigure"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.PathFigure 类。路径图形。一个 PathFigure 元素由一个或多个直线或曲线段组成。"
type: docs
weight: 210
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/"
keywords: "PathFigure, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PathFigure class

路径图形。
一个 PathFigure 元素由一个或多个直线或曲线段组成。
段元素定义路径图形的形状。
第一个段元素的起始点在路径图形的 StartPoint 属性中指定。
每个段元素的终点是下一个段元素的起始点。

```csharp
public class PathFigure
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PathFigure](pathfigure/)() | 初始化 `PathFigure` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsClosed](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isclosed/) { get; set; } | 获取或设置一个值，指示是否闭合。指定路径是否闭合。如果设置为 true，则描边被绘制为"closed"，即路径图形最后一个段的最后一点与 StartPoint 属性指定的点相连；否则描边被绘制为"open"，最后一点不与起始点相连。仅在路径图形用于指定描边的 Path 元素时适用。 |
| [IsFilled](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isfilled/) { get; set; } | 获取或设置一个值，指示是否填充。指定路径图形是否用于计算包含路径几何体的面积。可以为 true 或 false。当设置为 false 时，路径图形仅用于描边。 |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/items/) { get; set; } | 获取或设置段元素。段元素包括：• ArcSegment。• PolyBezierSegment。• PolyLineSegment。• PolyQuadraticBezierSegment。 |
| [StartPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/startpoint/) { get; set; } | 获取或设置起始点。指定路径图形第一个段的起始点。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

