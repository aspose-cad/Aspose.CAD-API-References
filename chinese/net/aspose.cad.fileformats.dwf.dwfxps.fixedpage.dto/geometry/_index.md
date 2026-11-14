---
title: "Geometry 类"
linktitle: "Geometry"
articleTitle: "Geometry"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Geometry 类。几何体。几何体用于构建几何形状的可视化表示。"
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/geometry/"
keywords: "Geometry, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Geometry class

几何体。
几何体用于构建几何形状的可视化表示。
几何体中最小的原子单位是段。
段可以是直线或曲线。
一个或多个段被组合成路径图形定义。
路径图形是由连续段组成的单一形状。
一个或多个路径图形共同定义整个路径几何体。
路径几何体可能会定义用于组件路径图形的填充算法。

```csharp
public class Geometry
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Geometry](geometry/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PathGeometry](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/geometry/pathgeometry/) { get; set; } | 获取或设置路径几何体。PathGeometry 元素构成完整的几何定义。PathGeometry 元素包含一组路径图形，这些图形可以通过 Figures 属性或子 PathFigure 元素指定。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

