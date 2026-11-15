---
title: "MultiArray Структура"
linktitle: "MultiArray"
articleTitle: "MultiArray"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Memory.MultiArray struct. Оборачивает закодированный `ArraySegment` и предоставляет его как IList{Single[]}/&gt;."
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.glb.memory/multiarray/"
product_version: "26.9"
---
## MultiArray struct

Оборачивает закодированный `ArraySegment` и предоставляет его как IList{Single[]}/&gt;.

```csharp
public struct MultiArray : IList<float[]>, IReadOnlyList<float[]>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MultiArray](multiarray/)(ArraySegment&lt;byte&gt;, int, int, int, int, EncodingType, bool) | Инициализирует новый экземпляр класса MultiArray. |

## Свойства

| Имя | Описание |
| --- | --- |
| Count { get; } |  |
| Размеры { get; } |  |
| Item { get; set; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| Содержит(float[]) |  |
| CopyItemTo(int, float[]) |  |
| CopyTo(float[][], int) |  |
| Fill(IEnumerable&lt;float[]&gt;, int) |  |
| GetEnumerator() |  |
| IndexOf(float[]) |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

