---
title: "Trifans 类"
linktitle: "三角扇形"
articleTitle: "三角扇形"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Trifans 类。TRIFANS。TRIFANS 元素提供绑定顶点属性所需的信息 ..."
type: docs
weight: 1320
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/trifans/"
keywords: "Trifans, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Trifans class

TRIFANS。
TRIFANS 元素提供绑定顶点属性所需的信息，然后将这些顶点组织成相连的三角形。
网格描述的每个三角形都有三个顶点。
第一个三角形由第一、第二和第三个顶点构成。
每个后续三角形由当前顶点形成，重复使用第一个顶点和前一个顶点。

```csharp
public class Trifans : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Trifans](trifans/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/count/) { get; set; } | 获取或设置计数。count 属性指示三角形扇形基元的数量。必需属性。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/extra/) { get; set; } | 获取或设置额外内容。 |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/input/) { get; set; } | 获取或设置输入。input 元素可以出现任意次数。此输入是具有 offset 和 set 属性的本地输入。 |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/material/) { get; set; } | 获取或设置材质。material 属性声明材质的符号。该符号在实例化时绑定到材质。如果未指定 material 属性，则光照和着色结果由应用程序定义。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Primitives](../../aspose.cad.fileformats.collada.fileparser.elements/trifans/primitives/) { get; set; } | 获取或设置基元。TRIFANS 元素可以包含任意数量的 primitives 元素。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

