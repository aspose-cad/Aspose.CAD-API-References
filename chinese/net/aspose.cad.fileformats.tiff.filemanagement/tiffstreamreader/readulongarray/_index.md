---
title: "TiffStreamReader.ReadULongArray"
linktitle: "ReadULongArray"
articleTitle: "ReadULongArray"
second_title: "Aspose.CAD for .NET API 参考"
description: "TiffStreamReader 方法。读取来自流的无符号整数值数组。"
type: docs
weight: 240
url: "/net/aspose.cad.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/"
product_version: "26.9"
---
## TiffStreamReader.ReadULongArray method

从流中读取无符号整数值数组。

```csharp
public uint[] ReadULongArray(long position, long count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | Int64 | 要读取的起始位置。 |
| 计数 | Int64 | 元素计数。 |

### 返回值

无符号整数值数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;总字节计数为负数。+ count + x4= + totalBytes |

### 另请参阅

* class [TiffStreamReader](../)
* namespace [Aspose.CAD.FileFormats.Tiff.FileManagement](../../../aspose.cad.fileformats.tiff.filemanagement/)
* assembly [Aspose.CAD](../../../)

