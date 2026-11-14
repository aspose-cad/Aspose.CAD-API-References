---
title: "TiffStreamReader.ReadSLongArray"
linktitle: "ReadSLongArray"
articleTitle: "ReadSLongArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "TiffStreamReader 方法。 从流中读取有符号整数值的数组。"
type: docs
weight: 180
url: "/net/aspose.cad.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/"
product_version: "26.9"
---
## TiffStreamReader.ReadSLongArray method

从流中读取有符号整数值数组。

```csharp
public int[] ReadSLongArray(long position, long count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | Int64 | 要读取的起始位置。 |
| 计数 | Int64 | 元素计数。 |

### 返回值

有符号整数值的数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;总字节计数为负数。+ count + x4= + totalBytes |

### 另请参阅

* class [TiffStreamReader](../)
* namespace [Aspose.CAD.FileFormats.Tiff.FileManagement](../../../aspose.cad.fileformats.tiff.filemanagement/)
* assembly [Aspose.CAD](../../../)

