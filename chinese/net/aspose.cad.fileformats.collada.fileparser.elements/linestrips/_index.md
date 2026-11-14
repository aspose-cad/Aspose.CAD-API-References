---
title: "Linestrips 类"
linktitle: "Linestrips"
articleTitle: "Linestrips"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Linestrips 类。LINESTRIPS。linEStrips 元素提供绑定顶点所需的信息……"
type: docs
weight: 800
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/linestrips/"
keywords: "Linestrips, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Linestrips class

该 LINESTRIPS。
linEStrips 元素提供将顶点属性绑定在一起并将这些顶点组织成连接的线段（line-strips）所需的信息。
网格描述的每个 line-strip 拥有任意数量的顶点。
line-strip 中的每个线段由当前顶点和前一个顶点组成。

```csharp
public class Linestrips : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Linestrips](linestrips/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/count/) { get; set; } | 获取或设置计数。count 属性指示 LINESTRIP 基元的数量。必需属性。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/extra/) { get; set; } | 获取或设置额外内容。 |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/input/) { get; set; } | 获取或设置 input。input 元素可以出现任意次数。此 input 是具有 offset 和 set 属性的本地输入。 |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/material/) { get; set; } | 获取或设置材质。material 属性声明一个材质的符号。该符号在实例化时绑定到材质。如果未指定 material 属性，则光照和着色结果由应用程序定义。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Primitives](../../aspose.cad.fileformats.collada.fileparser.elements/linestrips/primitives/) { get; set; } | 获取或设置基元。LINESTRIPS 元素可以包含任意数量的 primitives 元素。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

