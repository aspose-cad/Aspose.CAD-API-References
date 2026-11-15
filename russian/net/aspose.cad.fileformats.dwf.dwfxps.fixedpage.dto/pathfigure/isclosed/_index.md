---
title: "PathFigure.IsClosed"
linktitle: "IsClosed"
articleTitle: "IsClosed"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство PathFigure. Получает или задает значение, указывающее, закрыт ли путь. Указывает, закрыт ли путь. Если установлено в true, обводка рисуется «закрытой», ..."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isclosed/"
product_version: "26.9"
---
## PathFigure.IsClosed property

Получает или задает значение, указывающее, закрыт ли объект.
Указывает, закрыт ли путь.
Если установлено в true, обводка рисуется «закрытой», то есть,
последняя точка в последнем сегменте фигуры пути соединяется с
точкой, указанной в атрибуте StartPoint,
в противном случае обводка рисуется «открытой», и последняя точка не соединяется с начальной точкой.
Применяется только если фигура пути используется в элементе Path, который задает обводку.

```csharp
public bool IsClosed { get; set; }
```

### См. также

* class [PathFigure](../)
* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../../)

