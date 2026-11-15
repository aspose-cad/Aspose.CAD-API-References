---
title: "Класс RadialGradientBrush"
linktitle: "RadialGradientBrush"
articleTitle: "RadialGradientBrush"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.RadialGradientBrush class. Радиальная градиентная кисть."
type: docs
weight: 260
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/"
keywords: "RadialGradientBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## RadialGradientBrush class

Радиальная градиентная кисть.

```csharp
public class RadialGradientBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RadialGradientBrush](radialgradientbrush/)() | Инициализирует новый экземпляр класса `RadialGradientBrush`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Center](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/center/) { get; set; } | Получает или задает center. Указывает центральную точку радиального градиента (то есть центр эллипса). Радиальная градиентная кисть интерполирует цвета от начала градиента до окружности эллипса. Окружность определяется центром и радиусами. |
| [ColorInterpolationMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/colorinterpolationmode/) { get; set; } | Получает или задает color interpolation mode. Указывает гамма‑функцию для интерполяции цвета. Коррекция гаммы не должна применяться к альфа‑компоненту, если он указан. |
| [GradientOrigin](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/gradientorigin/) { get; set; } | Получает или задает начало градиента. Указывает исходную точку радиального градиента. |
| [MappingMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/mappingmode/) { get; set; } | Получает или задает режим отображения. Указывает, что центр, радиус по оси x и радиус по оси y определяются в эффективном пространстве координат (включает атрибут Transform кисти). |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность радиального градиента. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения вне этого диапазона недействительны. |
| [RadialGradientBrushGradientStops](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radialgradientbrushgradientstops/) { get; set; } | Получает или задает остановки градиента кисти радиального градиента. Содержит последовательность элементов GradientStop. |
| [RadialGradientBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radialgradientbrushtransform/) { get; set; } | Получает или задает преобразование кисти радиального градиента. Описывает матричное преобразование, применяемое к пространству координат кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Центр, начало градиента, радиус по оси x и радиус по оси y преобразуются с использованием локального эффективного преобразования рендеринга. |
| [RadiusX](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radiusx/) { get; set; } | Получает или задает радиус по оси x. Указывает радиус в измерении x эллипса, определяющего радиальный градиент. |
| [RadiusY](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/radiusy/) { get; set; } | Получает или задает радиус по оси y. Указывает радиус в измерении y эллипса, определяющего радиальный градиент. |
| [SpreadMethod](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/spreadmethod/) { get; set; } | Получает или задает метод распространения. Описывает, как кисть должна заполнять область содержимого за пределами основной, начальной области градиента. Допустимые значения: Pad, Reflect и Repeat. |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/radialgradientbrush/transform/) { get; set; } | Получает или задает преобразование. Описывает матричное преобразование, применяемое к пространству координат кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Эллипс, определяемый центром, началом градиента, значениями радиусов по осям x и y, преобразуется с использованием локального эффективного преобразования рендеринга. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

