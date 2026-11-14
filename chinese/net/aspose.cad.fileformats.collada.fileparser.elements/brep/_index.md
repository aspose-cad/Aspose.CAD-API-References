---
title: "Brep 类"
linktitle: "Brep"
articleTitle: "Brep"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Brep 类。该 BREP。描述边界表示 (BREP) 结构。"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/brep/"
keywords: "Brep, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Brep class

该 BREP。
描述边界表示 (BREP) 结构。

```csharp
public class Brep : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Brep](brep/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Curves](../../aspose.cad.fileformats.collada.fileparser.elements/brep/curves/) { get; set; } | 获取或设置曲线。curves 元素保存 BREP 结构所需的所有曲线。这里的曲线描述边的类型，同时也有用于创建表面挤出的曲线。如果存在 edges 元素，则需要此元素。 |
| [Edges](../../aspose.cad.fileformats.collada.fileparser.elements/brep/edges/) { get; set; } | 获取或设置边。此元素定义 BREP 结构的所有边。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/brep/extra/) { get; set; } | 获取或设置额外内容。 |
| [Faces](../../aspose.cad.fileformats.collada.fileparser.elements/brep/faces/) { get; set; } | 获取或设置面。此元素定义 BREP 结构的所有面。 |
| [ParametricCurves](../../aspose.cad.fileformats.collada.fileparser.elements/brep/parametriccurves/) { get; set; } | 获取或设置参数曲线。 |
| [Shells](../../aspose.cad.fileformats.collada.fileparser.elements/brep/shells/) { get; set; } | 获取或设置壳体。此元素定义 BREP 结构的所有壳体。 |
| [Solids](../../aspose.cad.fileformats.collada.fileparser.elements/brep/solids/) { get; set; } | 获取或设置实体。此元素定义 BREP 结构的所有实体。 |
| [Source](../../aspose.cad.fileformats.collada.fileparser.elements/brep/source/) { get; set; } | 获取或设置源。source 元素定义顶点、边和面的几何实体的访问方式。顶点至少需要一个 source 元素。如果存在 edges，则需要第二个 source 元素通过 IDREF_array 访问 curve 元素中的曲线。如果存在 faces，则需要第三个 source 元素通过 IDREF_array 访问 surface 元素中的曲面。 |
| [SurfaceCurves](../../aspose.cad.fileformats.collada.fileparser.elements/brep/surfacecurves/) { get; set; } | 获取或设置表面曲线。包含此 B-rep 中使用的所有 2D 曲线。包括描述面类型的曲面。如果存在 faces 元素，则此元素是必需的。 |
| [Surfaces](../../aspose.cad.fileformats.collada.fileparser.elements/brep/surfaces/) { get; set; } | 获取或设置表面。surfaces 元素保存 BREP 结构所需的所有表面。这里的表面描述了面的类型。如果存在 faces 元素，则需要此元素。 |
| [Vertices](../../aspose.cad.fileformats.collada.fileparser.elements/brep/vertices/) { get; set; } | 获取或设置顶点。此元素定义 BREP 结构的所有顶点。顶点是所有 BREP 结构的基础拓扑实体，因此此元素始终是必需的。 |
| [Wires](../../aspose.cad.fileformats.collada.fileparser.elements/brep/wires/) { get; set; } | 获取或设置线。此元素定义 BREP 结构的所有线。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

