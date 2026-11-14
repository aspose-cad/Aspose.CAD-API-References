---
title: "IColorConverter.Convert"
linktitle: "转换"
articleTitle: "转换"
second_title: "Aspose.CAD for .NET API 参考"
description: "IColorConverter 方法。将传入的数据转换为输出格式。"
type: docs
weight: 10
url: "/net/aspose.cad/icolorconverter/convert/"
product_version: "26.9"
---
## IColorConverter.Convert method

将传入的数据转换为输出格式。

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 源格式。 |
| data | Byte[] | 源数据。 |
| offset | Int32 | 数据复制应开始的字节偏移量。 |
| bitStart | Int32 | 位起始。注意，此值不是字节对齐的，而是实际的位，复制应从此位开始。 |
| samplesCount | Int32 | 样本计数。 |
| linesCount | Int32 | 行计数。 |
| destFormat | PixelDataFormat | 目标格式。 |
| outputData | Byte[] | 输出数据。 |
| outputOffset | Int32 | 数据复制应开始的输出偏移。 |

### 返回值

转换的字节数。

### 另请参阅

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

