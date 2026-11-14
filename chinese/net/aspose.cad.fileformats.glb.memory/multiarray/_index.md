---
title: "MultiArray 结构"
linktitle: "MultiArray"
articleTitle: "MultiArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.MultiArray 结构。封装已编码的 ArraySegment 并将其公开为 IList{Single[]}/&gt;。"
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.glb.memory/multiarray/"
product_version: "26.9"
---
## MultiArray struct

封装已编码的 `ArraySegment` 并将其公开为 IList{Single[]}/&gt;。

```csharp
public struct MultiArray : IList<float[]>, IReadOnlyList<float[]>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultiArray](multiarray/)(ArraySegment&lt;byte&gt;, int, int, int, int, EncodingType, bool) | 初始化 MultiArray 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Count { get; } |  |
| Dimensions { get; } |  |
| Item { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| Contains(float[]) |  |
| CopyItemTo(int, float[]) |  |
| CopyTo(float[][], int) |  |
| Fill(IEnumerable&lt;float[]&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(float[]) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

