---
title: "Polylist 类"
linktitle: "Polylist"
articleTitle: "Polylist"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Polylist 类。POLYLIST。POLYLIST 元素提供绑定顶点属性所需的信息..."
type: docs
weight: 960
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/polylist/"
keywords: "Polylist, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Polylist class

POLYLIST。
POLYLIST 元素提供绑定顶点属性并将这些顶点组织成单个多边形所需的信息。
POLYLIST 中描述的多边形可以包含任意数量的顶点。
与 polygons 元素不同，POLYLIST 元素不能包含带孔的多边形。

```csharp
public class Polylist : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Polylist](polylist/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/count/) { get; set; } | 获取或设置计数。count 属性指示多边形基元的数量。必需属性。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/extra/) { get; set; } | 获取或设置 extra。extra 元素可以出现任意次数。 |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/input/) { get; set; } | 获取或设置 input。input 元素可以出现任意次数。此 input 是具有 offset 和 set 属性的本地输入。 |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/material/) { get; set; } | 获取或设置材质。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Primitives](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/primitives/) { get; set; } | 获取或设置基元。POLYLIST 元素可能有零个或一个 primitives 元素。 |
| [VerticesCount](../../aspose.cad.fileformats.collada.fileparser.elements/polylist/verticescount/) { get; set; } | 获取或设置顶点计数。vertices count 元素包含一个整数列表，描述 POLYLIST 元素中每个多边形的边数。vertices count 元素可能出现一次。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

