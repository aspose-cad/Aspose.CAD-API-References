---
title: "Класс VisualBrush"
linktitle: "VisualBrush"
articleTitle: "VisualBrush"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.VisualBrush. Визуальная кисть. Элемент VisualBrush используется для заполнения региона рисунком. Рис..."
type: docs
weight: 370
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/"
keywords: "VisualBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## VisualBrush class

Визуальная кисть.
Элемент VisualBrush используется для заполнения региона рисунком.
Рисунок может быть указан либо как элемент свойства VisualBrush.[Visual](../visual/), либо как ссылка на ресурс.
Содержимое рисунка может включать ровно один элемент [Canvas](../canvas/), [Path](../path/) или [Glyphs](../glyphs/) и дочерние и последующие элементы этого элемента.

```csharp
public class VisualBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VisualBrush](visualbrush/)() | Инициализирует новый экземпляр класса `VisualBrush`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность заполнения кисти. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения вне этого диапазона недействительны. |
| [TileMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/tilemode/) { get; set; } | Получает или задает режим плитки. Указывает, как содержимое будет размещаться плиткой в заполненном регионе. Допустимые значения: None, Tile, FlipX, FlipY и FlipXY. |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/transform/) { get; set; } | Получает или задает преобразование. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Область просмотра (viewport) кисти преобразуется с использованием этого локального эффективного преобразования рендеринга. |
| [Viewbox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewbox/) { get; set; } | Получает или задает область просмотра (view box). Указывает позицию и размеры исходного содержимого кисти. Задает четыре разделённых запятыми действительных числа (x, y, Width, Height), где ширина и высота неотрицательны. Область просмотра определяет систему координат по умолчанию для элемента, указанного в свойстве VisualBrush.Visual. Углы области просмотра сопоставляются с углами области просмотра (viewport), обеспечивая обрезку и преобразование исходного содержимого кисти по умолчанию. |
| [ViewboxUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewboxunits/) { get; set; } | Получает или задает единицы области просмотра. Указывает взаимосвязь координат области просмотра с содержащим координатным пространством. |
| [Viewport](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewport/) { get; set; } | Получает или задает область просмотра (viewport). Указывает регион в содержащем координатном пространстве основной плитки кисти, который (возможно многократно) применяется для заполнения региона, к которому применяется кисть. Задает четыре разделённых запятыми действительных числа (x, y, Width, Height), где ширина и высота неотрицательны. Выравнивание узора кисти контролируется настройкой значений x и y. |
| [ViewportUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/viewportunits/) { get; set; } | Получает или задает единицы области просмотра. Указывает взаимосвязь координат viewport с содержащим координатным пространством. |
| [Visual](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visual/) { get; set; } | Получает или задает визуальный элемент. Указывает ссылку на ресурс к элементу Path, Glyphs или Canvas, определённому в словаре ресурсов и используемому для отрисовки исходного содержимого кисти. |
| [VisualBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visualbrushtransform/) { get; set; } | Получает или задает преобразование визуальной кисти. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Область просмотра кисти преобразуется с использованием локального эффективного преобразования рендеринга. |
| [VisualBrushVisual](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/visualbrush/visualbrushvisual/) { get; set; } | Получает или задает визуальный элемент визуальной кисти. Указывает элемент Path, Glyphs или Canvas, используемый для отрисовки исходного содержимого кисти. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

