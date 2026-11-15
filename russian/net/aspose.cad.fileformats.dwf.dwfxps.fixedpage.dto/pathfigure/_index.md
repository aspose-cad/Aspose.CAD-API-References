---
title: "Класс PathFigure"
linktitle: "PathFigure"
articleTitle: "PathFigure"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.PathFigure class. Фигура пути. Элемент PathFigure состоит из набора одного или более линейных или криволинейных сегментов."
type: docs
weight: 210
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/"
keywords: "PathFigure, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PathFigure class

Фигура пути.
Элемент PathFigure состоит из набора одной или более линейных или криволинейных сегментов.
Элементы сегментов определяют форму фигуры пути.
Начальная точка первого элемента сегмента указывается атрибутом StartPoint фигуры пути.
Последняя точка каждого элемента сегмента является первой точкой следующего элемента сегмента.

```csharp
public class PathFigure
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathFigure](pathfigure/)() | Инициализирует новый экземпляр класса `PathFigure`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsClosed](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isclosed/) { get; set; } | Получает или задает значение, указывающее, замкнут ли путь. Указывает, является ли путь замкнутым. Если установить true, контур рисуется «замкнутым», то есть последняя точка последнего сегмента фигуры пути соединяется с точкой, указанной в атрибуте StartPoint; иначе контур рисуется «открытым», и последняя точка не соединяется с начальной точкой. Применяется только если фигура пути используется в элементе Path, который задает контур. |
| [IsFilled](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isfilled/) { get; set; } | Получает или задает значение, указывающее, заполнена ли. Указывает, используется ли фигура пути при вычислении площади содержащей геометрии пути. Может быть true или false. Когда установлено в false, фигура пути рассматривается только для обводки. |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/items/) { get; set; } | Получает или задает элементы сегмента. Элементы сегмента: • ArcSegment. • PolyBezierSegment. • PolyLineSegment. • PolyQuadraticBezierSegment. |
| [StartPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/startpoint/) { get; set; } | Получает или задает начальную точку. Указывает начальную точку первого сегмента фигуры пути. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

