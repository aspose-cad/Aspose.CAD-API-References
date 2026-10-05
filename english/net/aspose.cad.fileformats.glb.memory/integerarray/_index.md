---
title: "IntegerArray Struct"
linktitle: "IntegerArray"
articleTitle: "IntegerArray"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Memory.IntegerArray struct. Wraps an encoded ArraySegment and exposes it as an IList."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.memory/integerarray/"
product_version: "26.9"
---
## IntegerArray struct

Wraps an encoded `ArraySegment` and exposes it as an `IList`.

```csharp
public struct IntegerArray : IList<uint>, IReadOnlyList<uint>
```

## Constructors

| Name | Description |
| --- | --- |
| [IntegerArray](integerarray/)(ArraySegment&lt;byte&gt;, IndexEncodingType) | Initializes a new instance of the `IntegerArray` struct. |

## Properties

| Name | Description |
| --- | --- |
| Count { get; } | Gets the number of elements in the range delimited by the `IntegerArray` |
| Item { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| Contains(uint) |  |
| CopyTo(uint[], int) |  |
| Fill(IEnumerable&lt;int&gt;, int) |  |
| Fill(IEnumerable&lt;uint&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(uint) |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

