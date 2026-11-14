---
title: "IntegerArray 结构体"
linktitle: "IntegerArray"
articleTitle: "IntegerArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.IntegerArray 结构体。包装一个已编码的 ArraySegment，并将其公开为 IList。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.memory/integerarray/"
product_version: "26.9"
---
## IntegerArray struct

封装已编码的 `ArraySegment` 并将其公开为 `IList`。

```csharp
public struct IntegerArray : IList<uint>, IReadOnlyList<uint>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [IntegerArray](integerarray/)(ArraySegment&lt;byte&gt;, IndexEncodingType) | 初始化 `IntegerArray` 结构体的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Count { get; } | 获取 `IntegerArray` 所限定范围内的元素数量。 |
| Item { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| 包含(uint) |  |
| 复制到(uint[], int) |  |
| 填充(IEnumerable&lt;int&gt;, int) |  |
| 填充(IEnumerable&lt;uint&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(uint) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

