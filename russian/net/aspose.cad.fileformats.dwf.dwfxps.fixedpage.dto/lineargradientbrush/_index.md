---
title: "LinearGradientBrush Класс"
linktitle: "LinearGradientBrush"
articleTitle: "LinearGradientBrush"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.LinearGradientBrush класс. Линейная градиентная кисть. Элемент LinearGradientBrush используется для указания li..."
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/"
keywords: "LinearGradientBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## LinearGradientBrush class

Линейная градиентная кисть.
Элемент LinearGradientBrush используется для указания линейной градиентной кисти вдоль вектора.
Заполняет область линейным градиентом.

```csharp
public class LinearGradientBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/)() | Инициализирует новый экземпляр класса `LinearGradientBrush`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorInterpolationMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/colorinterpolationmode/) { get; set; } | Получает или задает color interpolation mode. Указывает гамма‑функцию для интерполяции цвета. Коррекция гаммы не должна применяться к альфа‑компоненту, если он указан. |
| [EndPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/endpoint/) { get; set; } | Получает или задает конечную точку. Указывает конечную точку линейного градиента. Линейная градиентная кисть интерполирует цвета от начальной точки до конечной, где начальная точка представляет смещение 0, а EndPoint — смещение 1. Значение атрибута Offset, указанное в элементе GradientStop, относится к смещениям 0 и 1, определённым начальной и конечной точками. |
| [LinearGradientBrushGradientStops](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/lineargradientbrushgradientstops/) { get; set; } | Получает или задает градиентные остановки линейной градиентной кисти. Содержит последовательность элементов GradientStop. |
| [LinearGradientBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/lineargradientbrushtransform/) { get; set; } | Получает или задает преобразование линейной градиентной кисти. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, образуя эффективное преобразование рендеринга, локальное для кисти. Начальная и конечная точки преобразуются с использованием локального эффективного преобразования рендеринга. |
| [MappingMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/mappingmode/) { get; set; } | Получает или задает режим отображения. Указывает, что начальная и конечная точки определены в эффективном координатном пространстве (включает атрибут Transform кисти). |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность линейного градиента. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения вне этого диапазона недействительны. |
| [SpreadMethod](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/spreadmethod/) { get; set; } | Получает или задает метод распространения. Описывает, как кисть должна заполнять область содержимого за пределами основной, начальной области градиента. Допустимые значения: Pad, Reflect и Repeat. |
| [StartPoint](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/startpoint/) { get; set; } | Получает или задает начальную точку. Указывает начальную точку линейного градиента. |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/lineargradientbrush/transform/) { get; set; } | Получает или задает преобразование. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform кисти конкатенируется с текущим эффективным преобразованием рендеринга, образуя эффективное преобразование рендеринга, локальное для кисти. Начальная и конечная точки преобразуются с использованием локального эффективного преобразования рендеринга. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

