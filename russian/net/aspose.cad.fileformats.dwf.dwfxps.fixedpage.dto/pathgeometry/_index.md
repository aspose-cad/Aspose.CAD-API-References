---
title: "PathGeometry класс"
linktitle: "PathGeometry"
articleTitle: "PathGeometry"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.PathGeometry класс. Геометрия пути. Элемент PathGeometry содержит набор фигур пути, указанных либо..."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/"
keywords: "PathGeometry, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PathGeometry class

Геометрия пути.
Элемент PathGeometry содержит набор фигур пути, указанных либо
с атрибутом Figures или с дочерним элементом [PathFigure](../pathfigure/).
Производители НЕ ДОЛЖНЫ указывать фигуры пути геометрии одновременно с атрибутом Figures и дочерним элементом [PathFigure](../pathfigure/).

```csharp
public class PathGeometry
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathGeometry](pathgeometry/)() | Инициализирует новый экземпляр класса `PathGeometry`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Figures](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/figures/) { get; set; } | Получает или задает фигуры. Описывает геометрию пути. |
| [FillRule](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/fillrule/) { get; set; } | Получает или задает правило заполнения. Указывает, как пересекающиеся области геометрических фигур комбинируются для формирования региона. Допустимые значения: EvenOdd и NonZero. |
| [PathFigure](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/pathfigure/) { get; set; } | Получает или задает фигуру пути. Указывает набор из одного или нескольких сегментных элементов, определяющих замкнутый регион. |
| [PathGeometryTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/pathgeometrytransform/) { get; set; } | Получает или задает преобразование геометрии пути. Указывает локальное матричное преобразование, применяемое ко всем дочерним и потомкам элементам геометрии пути перед использованием для заполнения, обрезки или обводки. |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathgeometry/transform/) { get; set; } | Получает или задает преобразование. Указывает локальное матричное преобразование, применяемое ко всем дочерним и потомкам элементам геометрии пути перед использованием для заполнения, обрезки или обводки. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

