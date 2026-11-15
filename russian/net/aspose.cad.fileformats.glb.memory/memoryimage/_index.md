---
title: "Структура MemoryImage"
linktitle: "MemoryImage"
articleTitle: "MemoryImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Структура Aspose.CAD.FileFormats.GLB.Memory.MemoryImage. Представляет файл изображения, хранящийся в виде массива байтов в памяти."
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.glb.memory/memoryimage/"
product_version: "26.9"
---
## MemoryImage struct

Представляет файл изображения, хранящийся в виде массивa байтов в памяти.

```csharp
public struct MemoryImage : IEquatable<MemoryImage>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MemoryImage](memoryimage/)(ArraySegment&lt;byte&gt;) | Инициализирует новый экземпляр класса MemoryImage. |

## Свойства

| Имя | Описание |
| --- | --- |
| Content { get; } | Получает байты файла изображения. |
| Empty { get; } |  |
| FileExtension { get; } | Возвращает наиболее подходящую строку расширения для этого изображения. |
| IsDds { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение DDS. |
| IsEmpty { get; } |  |
| IsExtendedFormat { get; } | Возвращает значение, указывающее, представляет ли этот объект изображение, поддерживаемое расширением glTF. |
| IsJpg { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение JPG. |
| IsKtx2 { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение KTX2. |
| IsPng { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение PNG. |
| IsValid { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение. |
| IsWebp { get; } | Возвращает значение, указывающее, представляет ли этот объект действительное изображение WEBP. |
| MimeType { get; } | Возвращает наиболее подходящую строку MIME‑типа для этого изображения. |
| SourcePath { get; } | Возвращает путь к источнику этого изображения или **null**. |

## Методы

| Имя | Описание |
| --- | --- |
| AreEqual(MemoryImage, MemoryImage) |  |
| Equals(MemoryImage) |  |
| Equals(object) |  |
| GetHashCode() |  |
| IsImageOfType(string) | определяет изображение определённого типа. |
| Open() | Открывает файл изображения для чтения его содержимого |
| SaveToFile(string) | Сохраняет изображение, хранящееся в этом `MemoryImage`, в файл. |
| ToDebuggerDisplay() |  |
| TryParseMime64(string, out MemoryImage) | Пытается разобрать строку Mime64 в `MemoryImage` |

## Operators

| Имя | Описание |
| --- | --- |
| operator MemoryImage |  |
| operator MemoryImage |  |
| operator MemoryImage |  |
| operator == |  |
| operator != |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

