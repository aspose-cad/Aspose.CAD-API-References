---
title: "Класс GradientStop"
linktitle: "GradientStop"
articleTitle: "GradientStop"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.GradientStop class. Точка градиента. Элемент GradientStop используется как в LinearGradientBrush, так и в R..."
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/"
keywords: "GradientStop, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GradientStop class

Точка градиента.
Элемент GradientStop используется как элементами [LinearGradientBrush](../lineargradientbrush/) и [RadialGradientBrush](../radialgradientbrush/) для определения положения
и диапазона прогрессии цвета при рендеринге градиента.
Для линейных градиентных кистей значение смещения 0.0 сопоставляется с начальной точкой градиента,
а значение смещения 1.0 сопоставляется с конечной точкой.
Промежуточные значения смещения интерполируются между этими двумя точками для определения их положения.
Для радиальных градиентных кистей значение смещения 0.0 сопоставляется с расположением начала градиента.
Значение смещения 1.0 сопоставляется с окружностью эллипса, определяемой центром,
радиусом по оси x и радиусом по оси y. Смещения между 0.0 и 1.0 размещаются в положении, интерполированном между этими точками.

```csharp
public class GradientStop
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GradientStop](gradientstop/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/color/) { get; set; } | Получает или задает цвет. Указывает цвет точки градиента. |
| [Offset](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/offset/) { get; set; } | Получает или задает смещение. Указывает смещение градиента. Смещение указывает точку вдоль прогрессии градиента, в которой задаётся цвет. Цвета между смещениями градиента в прогрессии интерполируются. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

