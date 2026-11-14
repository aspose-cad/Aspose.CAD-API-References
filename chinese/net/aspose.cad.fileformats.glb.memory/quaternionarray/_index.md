---
title: "QuaternionArray 结构体"
linktitle: "QuaternionArray"
articleTitle: "QuaternionArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.QuaternionArray 结构体。封装已编码的 ArraySegment 并将其公开为 IList。"
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.glb.memory/quaternionarray/"
product_version: "26.9"
---
## QuaternionArray struct

封装已编码的 `ArraySegment` 并将其公开为 `IList`。

```csharp
public struct QuaternionArray : IList<Quaternion>, IReadOnlyList<Quaternion>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [QuaternionArray](quaternionarray/)(ArraySegment&lt;byte&gt;, int, EncodingType, bool) | 初始化 QuaternionArray 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Count { get; } |  |
| Item { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| Contains(Quaternion) |  |
| CopyTo(Quaternion[], int) |  |
| Fill(IEnumerable&lt;Quaternion&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(Quaternion) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

