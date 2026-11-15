---
title: "TiffStreamReader.ReadUIntArray"
linktitle: "ReadUIntArray"
articleTitle: "ReadUIntArray"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод TiffStreamReader. Считывает массив значений беззнаковых целых чисел из потока."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.tiff.filemanagement/tiffstreamreader/readuintarray/"
product_version: "26.9"
---
## TiffStreamReader.ReadUIntArray method

Читает массив значений беззнаковых целых чисел из потока.

```csharp
public uint[] ReadUIntArray(long position, long count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | Int64 | Позиция, из которой читать. |
| count | Int64 | Количество элементов. |

### Возвращаемое значение

Массив беззнаковых целочисленных значений.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательно. + count + x4= + totalBytes |

### См. также

* class [TiffStreamReader](../)
* namespace [Aspose.CAD.FileFormats.Tiff.FileManagement](../../../aspose.cad.fileformats.tiff.filemanagement/)
* assembly [Aspose.CAD](../../../)

