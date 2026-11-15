---
title: "Класс FixedPage"
linktitle: "FixedPage"
articleTitle: "FixedPage"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.FixedPage. Фиксированная страница. Элемент FixedPage содержит содержимое страницы и является корневым элементом..."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/"
keywords: "FixedPage, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## FixedPage class

Фиксированная страница.
Элемент FixedPage содержит содержимое страницы и является корневым элементом части FixedPage.
Фиксированная страница содержит элементы, которые вместе образуют основу всех отметок, отрисованных на странице: Paths, [Glyphs](../glyphs/),
и необязательный группирующий элемент [Canvas](../canvas/).

```csharp
public class FixedPage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FixedPage](fixedpage/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BleedBox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/bleedbox/) { get; set; } | Получает или задаёт bleed‑box. Указывает объединение ContentBox и ограничивающего прямоугольника всего графического содержимого, предназначенного для отображения на окончательной напечатанной и обрезанной странице. Содержит список из четырёх координатных значений (BleedOriginX, BleedOriginY, BleedWidth, BleedHeight), записанных как числа с плавающей точкой, разделённые запятыми. Если опущено, значение по умолчанию — (0,0, Width, Height). |
| [ContentBox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/contentbox/) { get; set; } | Получает или задаёт content‑box. Указывает область страницы, содержащую изображение, которое должно вписываться в область изображения при печати или просмотре. Содержит список из четырёх координатных значений (ContentOriginX, ContentOriginY, ContentWidth, ContentHeight), записанных как числа с плавающей точкой, разделённые запятыми. Указание значения РЕКОМЕНДУЕТСЯ. Если опущено, значение по умолчанию — (0,0,Width,Height). |
| [FixedPageResources](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/fixedpageresources/) { get; set; } | Получает или задаёт ресурсы фиксированной страницы. Разметка FixedPage поддерживает использование ресурсов. Ресурс — это переиспользуемое значение свойства, выраженное в разметке, идентифицированное ключом и хранящееся в словаре ресурсов. Как правило, любое значение свойства, которое может быть выражено с помощью синтаксиса элемент‑свойства, может быть помещено в словарь ресурсов. |
| [Height](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/height/) { get; set; } | Получает или задаёт высоту. Высота страницы, выраженная как число с плавающей точкой в единицах эффективного пространства координат. |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/items/) { get; set; } | Получает или задаёт массив элементов. Фиксированная страница содержит элементы, которые вместе образуют основу всех отметок, отрисованных на странице: Paths, Glyphs и необязательный группирующий элемент Canvas. |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/language/) { get; set; } | Получает или задает язык. Указывает язык по умолчанию, используемый для текущего элемента и для всех дочерних или потомковых элементов. Язык указывается в соответствии с RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/name/) { get; set; } | Получает или задает имя. Содержит строковое значение, которое идентифицирует текущий элемент как именованную, адресуемую точку в документе для целей гиперссылок. |
| [Width](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/width/) { get; set; } | Получает или задает ширину. Ширина страницы, выраженная в виде действительного числа в единицах эффективного координатного пространства. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

