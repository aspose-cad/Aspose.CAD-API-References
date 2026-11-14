---
title: "PathGeometry 类"
linktitle: "PathGeometry"
articleTitle: "PathGeometry"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.PathGeometry 类. 路径几何。PathGeometry 元素包含一组路径图形，指定为..."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/"
keywords: "PathGeometry, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PathGeometry class

路径几何。
PathGeometry 元素包含一组路径图形，指定为任意
使用 Figures 属性或使用子 [PathFigure](../pathfigure/) 元素。
生产者不得同时使用 Figures 属性和子 [PathFigure](../pathfigure/) 元素来指定几何体的路径图形。

```csharp
public class PathGeometry
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PathGeometry](pathgeometry/)() | 初始化 `PathGeometry` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Figures](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/figures/) { get; set; } | 获取或设置图形。描述路径的几何形状。 |
| [FillRule](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/fillrule/) { get; set; } | 获取或设置填充规则。指定几何形状的交叉区域如何组合成一个区域。有效值为 EvenOdd 和 NonZero。 |
| [PathFigure](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/pathfigure/) { get; set; } | 获取或设置路径图形。指定一个或多个段元素的集合，用于定义闭合区域。 |
| [PathGeometryTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/pathgeometrytransform/) { get; set; } | 获取或设置路径几何变换。指定在路径几何用于填充、裁剪或描边之前，应用于所有子级和后代元素的本地矩阵变换。 |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/transform/) { get; set; } | 获取或设置变换。指定在路径几何用于填充、裁剪或描边之前，应用于所有子级和后代元素的本地矩阵变换。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

