---
title: "InputLocalOffset 类"
linktitle: "InputLocalOffset"
articleTitle: "InputLocalOffset"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.InputLocalOffset 类。输入本地偏移。input_local_offset_type 元素用于表示 i..."
type: docs
weight: 580
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/"
keywords: "InputLocalOffset, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## InputLocalOffset class

输入本地偏移。
input_local_offset_type 元素用于表示只能引用同一文档中声明的资源的索引输入。

```csharp
public class InputLocalOffset : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [InputLocalOffset](inputlocaloffset/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Offset](../../aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/offset/) { get; set; } | 获取或设置偏移量。offset 属性表示在索引列表中的偏移。如果两个 input 元素共享相同的偏移，它们将被相同方式索引。这既是对索引列表的一种简单压缩形式，也定义了输入应使用的顺序。必需属性。 |
| [Semantic](../../aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/semantic/) { get; set; } | 获取或设置 semantic。semantic 属性是输入连接的用户定义含义。必需属性。 |
| [SetSpecified](../../aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/setspecified/) { get; set; } | 获取或设置指示是否指定集合的值。 |
| [SingleSet](../../aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/singleset/) { get; set; } | 获取或设置单个集合。set 属性指示哪些输入应组合为单个集合。当多个输入共享相同语义时，这很有帮助。 |
| [Source](../../aspose.cad.fileformats.collada.fileparser.elements/inputlocaloffset/source/) { get; set; } | 获取或设置源。source 属性指示数据源的位置。必需属性。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

