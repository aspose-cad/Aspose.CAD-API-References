---
title: "Glyphs.CaretStops"
linktitle: "CaretStops"
articleTitle: "CaretStops"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство Glyphs. Получает или задает позиции остановки каретки. Определяет позиции в последовательности символов Unicode, где инструмент выделения текста может разместить ..."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/caretstops/"
product_version: "26.9"
---
## Glyphs.CaretStops property

Получает или задает позиции остановки каретки.
Определяет позиции в последовательности символов Unicode, где инструмент выделения текста может разместить каретку редактирования текста.
Потенциальные позиции остановки каретки определяются их индексами в кодовых единицах UTF-16, представленных значением атрибута UnicodeString.
Когда этот атрибут отсутствует, текст в значении атрибута UnicodeString ДОЛЖЕН интерпретироваться
как имеющий остановку каретки между каждой кодовой единицей Unicode UTF-16 и в начале и в конце текста.
Значение ДОЛЖНО указывать, что каретка не может остановиться перед большинством комбинирующих знаков или перед второй кодовой единицей UTF-16 в суррогатных парах UTF-16.

```csharp
public string CaretStops { get; set; }
```

### См. также

* class [Glyphs](../)
* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../../)

