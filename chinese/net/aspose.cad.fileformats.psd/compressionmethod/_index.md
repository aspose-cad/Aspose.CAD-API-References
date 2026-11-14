---
title: "CompressionMethod 枚举"
linktitle: "CompressionMethod"
articleTitle: "CompressionMethod"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Psd.CompressionMethod 枚举。定义用于图像数据的压缩方法。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.psd/compressionmethod/"
product_version: "26.9"
---
## CompressionMethod enumeration

定义用于图像数据的压缩方法。

```csharp
public enum CompressionMethod : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Raw | `0` | 无压缩。图像数据以 RGBA 平面顺序的原始字节存储。这意味着首先写入所有 R 数据，然后是所有 G 数据，接着是所有 B，最后写入所有 A 数据。 |
| RLE | `1` | RLE 压缩的图像数据以所有扫描线（行 * 通道）的字节计数开始，每个计数存储为两个字节的值。随后是 RLE 压缩数据，每条扫描线单独压缩。RLE 压缩使用的算法与 Macintosh ROM 例程 PackBits 以及 TIFF 标准相同。 |
| ZipWithoutPrediction | `2` | ZIP（无预测）。 |
| ZipWithPrediction | `3` | ZIP（有预测）。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Psd](../../aspose.cad.fileformats.psd/)
* assembly [Aspose.CAD](../../)

