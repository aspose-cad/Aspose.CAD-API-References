---
title: "Polygons 类"
linktitle: "Polygons"
articleTitle: "Polygons"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Polygons 类。多边形。多边形元素提供绑定顶点属性所需的信息..."
type: docs
weight: 950
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/polygons/"
keywords: "Polygons, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Polygons class

多边形。
多边形元素提供绑定顶点属性所需的信息
先将它们组合在一起，然后将这些顶点组织成单独的多边形。
所描述的多边形可以包含任意数量的顶点。
这些多边形可能自相交，也可能包含孔洞。

```csharp
public class Polygons : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Polygons](polygons/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/count/) { get; set; } | 获取或设置计数。count 属性指示多边形基元的数量。必需属性。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/extra/) { get; set; } | 获取或设置额外内容。 |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/input/) { get; set; } | 获取或设置 input。input 元素可以出现任意次数。此 input 是具有 offset 和 set 属性的本地输入。 |
| [Items](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/items/) { get; set; } | 获取或设置项目。 |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/material/) { get; set; } | 获取或设置材质。material 属性声明一个材质的符号。该符号在实例化时绑定到材质。如果未指定 material 属性，则光照和着色结果由应用程序定义。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/polygons/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

