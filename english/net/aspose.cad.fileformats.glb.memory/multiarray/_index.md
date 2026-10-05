---
title: "MultiArray Struct"
linktitle: "MultiArray"
articleTitle: "MultiArray"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Memory.MultiArray struct. Wraps an encoded ArraySegment and exposes it as an IList{Single[]}/&gt;."
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.glb.memory/multiarray/"
product_version: "26.9"
---
## MultiArray struct

Wraps an encoded `ArraySegment` and exposes it as an IList{Single[]}/&gt;.

```csharp
public struct MultiArray : IList<float[]>, IReadOnlyList<float[]>
```

## Constructors

| Name | Description |
| --- | --- |
| [MultiArray](multiarray/)(ArraySegment&lt;byte&gt;, int, int, int, int, EncodingType, bool) | Initializes a new instance of the MultiArray class. |

## Properties

| Name | Description |
| --- | --- |
| Count { get; } |  |
| Dimensions { get; } |  |
| Item { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| Contains(float[]) |  |
| CopyItemTo(int, float[]) |  |
| CopyTo(float[][], int) |  |
| Fill(IEnumerable&lt;float[]&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(float[]) |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

