---
title: Accessor
second_title: Aspose.CAD for .NET API 参考
description: 访问器 访问器元素声明对数组元素之一的访问模式 FLOAT_ARRAYINT_ARRAYNAME_ARRAYBOOL_ARRAYTOKEN_ARRAY 和 IDREF_ARRAY 访问器元素描述了对以交错或非交错方式组织的数组的访问 取决于偏移量和步幅属性
type: docs
weight: 4220
url: /zh/net/aspose.cad.fileformats.collada.fileparser.elements/accessor/
---
## Accessor class

访问器。 访问器元素声明对数组元素之一的访问模式: FLOAT_ARRAY、INT_ARRAY、NAME_ARRAY、BOOL_ARRAY、TOKEN_ARRAY 和 IDREF_ARRAY。 访问器元素描述了对以交错或非交错方式组织的数组的访问， 取决于偏移量和步幅属性。

```csharp
public class Accessor : ColladaElement
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Accessor](accessor)() | 初始化[`Accessor`](../accessor)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/count) { get; set; } | 获取或设置计数。 count 属性表示数组被访问的次数。 必需属性。 |
| [Offset](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/offset) { get; set; } | 获取或设置偏移量。 offset 属性表示要从数组中读取的第一个值的索引。 默认值为 0。 可选属性。 |
| [Parameter](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/parameter) { get; set; } | 获取或设置参数。 访问器元素可以有任意数量的参数元素。 |
| [Source](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/source) { get; set; } | 获取或设置源。 source 属性指示要使用 URL 表达式访问的数组的位置。 必需属性。 |
| [Stride](../../aspose.cad.fileformats.collada.fileparser.elements/accessor/stride) { get; set; } | 获取或设置步幅。 stride属性表示每次访问数组时要被视为一个单元的值的个数。 默认值为1，表示访问单个值。 可选属性。 |

### 也可以看看

* class [ColladaElement](../colladaelement)
* 命名空间 [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements)
* 部件 [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
