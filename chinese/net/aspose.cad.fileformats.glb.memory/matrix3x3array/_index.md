---
title: "Matrix3x3Array 结构体"
linktitle: "Matrix3x3Array"
articleTitle: "Matrix3x3Array"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.Matrix3x3Array 结构体。封装已编码的 ArraySegment 并将其公开为 IList。"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.glb.memory/matrix3x3array/"
product_version: "26.9"
---
## Matrix3x3Array struct

封装已编码的 `ArraySegment` 并将其公开为 `IList`。

```csharp
public struct Matrix3x3Array : IList<Matrix4x4>, IReadOnlyList<Matrix4x4>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix3x3Array](matrix3x3array/)(ArraySegment&lt;byte&gt;, int, EncodingType, bool) | 初始化 Matrix3x3Array 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Count { get; } |  |
| Item { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| Contains(Matrix4x4) |  |
| CopyTo(Matrix4x4[], int) |  |
| Fill(IEnumerable&lt;Matrix4x4&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(Matrix4x4) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

