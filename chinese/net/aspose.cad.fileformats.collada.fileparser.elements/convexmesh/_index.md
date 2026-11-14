---
title: "ConvexMesh 类"
linktitle: "ConvexMesh"
articleTitle: "ConvexMesh"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.ConvexMesh 类。凸面网格。convex_mesh 元素的定义与 mesh 元素完全相同..."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/convexmesh/"
keywords: "ConvexMesh, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ConvexMesh class

凸面网格。
convex_mesh 元素的定义与 mesh 元素相同，唯一例外是
它不是提供完整的描述（源、顶点、多边形等），而是可以简单地指向另一个几何体以获取其形状。
后一种情况意味着应计算该几何体的凸包，并通过可选的 \"convex_hull_of\" 属性指示。

```csharp
public class ConvexMesh : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ConvexMesh](convexmesh/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvexHullOf](../../aspose.cad.fileformats.collada.fileparser.elements/convexmesh/convexhullof/) { get; set; } | 获取或设置凸包。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/convexmesh/extra/) { get; set; } | 获取或设置额外内容。 |
| [Items](../../aspose.cad.fileformats.collada.fileparser.elements/convexmesh/items/) { get; set; } | 获取或设置项目。 |
| [Source](../../aspose.cad.fileformats.collada.fileparser.elements/convexmesh/source/) { get; set; } | 获取或设置源。 |
| [Vertices](../../aspose.cad.fileformats.collada.fileparser.elements/convexmesh/vertices/) { get; set; } | 获取或设置顶点。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

