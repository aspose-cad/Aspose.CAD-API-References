---
title: "Accessor 类"
linktitle: "Accessor"
articleTitle: "Accessor"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Accessor class. 访问器。访问器元素声明对数组元素之一的访问模式..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/accessor/"
keywords: "Accessor, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Accessor class

访问器。
访问器元素声明对数组元素之一的访问模式：
FLOAT_ARRAY, INT_ARRAY, NAME_ARRAY, BOOL_ARRAY, TOKEN_ARRAY, and IDREF_ARRAY.
访问器元素描述对以交错或非交错方式组织的数组的访问，
取决于 offset 和 stride 属性。

```csharp
public class Accessor : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Accessor](accessor/)() | 初始化 `Accessor` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/count/) { get; set; } | 获取或设置计数。count 属性指示数组被访问的次数。必需属性。 |
| [Offset](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/offset/) { get; set; } | 获取或设置偏移。offset 属性指示从数组中读取的第一个值的索引。默认值为 0。可选属性。 |
| [Parameter](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/parameter/) { get; set; } | 获取或设置参数。访问器元素可以有任意数量的 parameter 元素。 |
| [Source](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/source/) { get; set; } | 获取或设置源。source 属性指示使用 URL 表达式访问的数组位置。必需属性。 |
| [Stride](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/stride/) { get; set; } | 获取或设置步幅。stride 属性指示在每次访问数组时被视为一个单元的值的数量。默认值为 1，表示访问单个值。可选属性。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

