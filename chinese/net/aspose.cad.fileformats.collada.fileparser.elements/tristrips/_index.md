---
title: "Tristrips 类"
linktitle: "Tristrips"
articleTitle: "Tristrips"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Tristrips 类。TRISTRIPS。TRISTRIPS 元素提供绑定顶点属性所需的信息..."
type: docs
weight: 1330
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/tristrips/"
keywords: "Tristrips, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Tristrips class

TRISTRIPS。
TRISTRIPS 元素提供绑定顶点属性并将这些顶点组织成相连三角形所需的信息。
网格描述的每个三角形都有三个顶点。
第一个三角形由第一、第二和第三个顶点形成。每个后续三角形由当前顶点形成，复用前两个顶点。

```csharp
public class Tristrips : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Tristrips](tristrips/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/count/) { get; set; } | 获取或设置计数。count 属性指示三角形条带基元的数量。必需属性。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/extra/) { get; set; } | 获取或设置额外内容。 |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/input/) { get; set; } | 获取或设置 input。input 元素可以出现任意次数。此 input 是具有 offset 和 set 属性的本地输入。 |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/material/) { get; set; } | 获取或设置材质。material 属性声明一个材质的符号。该符号在实例化时绑定到材质。如果未指定 material 属性，则光照和着色结果由应用程序定义。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Primitives](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/primitives/) { get; set; } | 获取或设置基元。TRISTRIPS 元素可以包含任意数量的 p 元素。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

