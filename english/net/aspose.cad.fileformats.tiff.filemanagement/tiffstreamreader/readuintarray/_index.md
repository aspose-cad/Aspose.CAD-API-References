---
title: "TiffStreamReader.ReadUIntArray"
linktitle: "ReadUIntArray"
articleTitle: "ReadUIntArray"
second_title: "Aspose.CAD for .NET API Reference"
description: "TiffStreamReader method. Reads an array of unsigned integer values from the stream."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.tiff.filemanagement/tiffstreamreader/readuintarray/"
product_version: "26.9"
---
## TiffStreamReader.ReadUIntArray method

Reads an array of unsigned integer values from the stream.

```csharp
public uint[] ReadUIntArray(long position, long count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| position | Int64 | The position to read from. |
| count | Int64 | The elements count. |

### Return Value

The array of unsigned integer values.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | count;Total bytes count is negative. + count + x4= + totalBytes |

### See Also

* class [TiffStreamReader](../)
* namespace [Aspose.CAD.FileFormats.Tiff.FileManagement](../../../aspose.cad.fileformats.tiff.filemanagement/)
* assembly [Aspose.CAD](../../../)

