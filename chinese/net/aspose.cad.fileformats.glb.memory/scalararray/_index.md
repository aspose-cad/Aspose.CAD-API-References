---
title: "ScalarArray 结构体"
linktitle: "ScalarArray"
articleTitle: "ScalarArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.ScalarArray 结构体。包装一个已编码的 ArraySegment，并将其公开为 IList。"
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.glb.memory/scalararray/"
product_version: "26.9"
---
## ScalarArray struct

封装已编码的 `ArraySegment` 并将其公开为 `IList`。

```csharp
public struct ScalarArray : IList<float>, IReadOnlyList<float>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ScalarArray](scalararray/)(ArraySegment&lt;byte&gt;, int, EncodingType, bool) | 初始化 `ScalarArray` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Count { get; } |  |
| Item { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| Contains(float) |  |
| CopyTo(float[], int) |  |
| Fill(IEnumerable&lt;float&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(float) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

