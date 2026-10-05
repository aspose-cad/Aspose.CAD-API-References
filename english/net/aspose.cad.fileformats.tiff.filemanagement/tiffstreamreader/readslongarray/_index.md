---
title: "TiffStreamReader.ReadSLongArray"
linktitle: "ReadSLongArray"
articleTitle: "ReadSLongArray"
second_title: "Aspose.CAD for .NET API Reference"
description: "TiffStreamReader method. Reads an array of signed integer values from the stream."
type: docs
weight: 180
url: "/net/aspose.cad.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/"
product_version: "26.9"
---
## TiffStreamReader.ReadSLongArray method

Reads an array of signed integer values from the stream.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| position | Int64 | The position to read from. |
| count | Int64 | The elements count. |

### Return Value

The array of signed integer values.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | count;Total bytes count is negative. + count + x4= + totalBytes |

### See Also

* class [TiffStreamReader](../)
* namespace [Aspose.CAD.FileFormats.Tiff.FileManagement](../../../aspose.cad.fileformats.tiff.filemanagement/)
* assembly [Aspose.CAD](../../../)

