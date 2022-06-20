---
title: VectorRasterizationOptions
second_title: Справочник по Aspose.CAD для .NET API
description: Параметры векторной растеризации.
type: docs
weight: 29970
url: /ru/net/aspose.cad.imageoptions/vectorrasterizationoptions/
---
## VectorRasterizationOptions class

Параметры векторной растеризации.

```csharp
public abstract class VectorRasterizationOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [ContentAsBitmap](../../aspose.cad.imageoptions/vectorrasterizationoptions/contentasbitmap) { get; set; } | Получает или задает значение, указывающее, представлено ли содержимое рисунка в виде изображения внутри Pdf. Применимо только для экспорта CAD в Pdf. Значение по умолчанию — ложь. |
| [DrawColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/drawcolor) { get; set; } | Получает или задает цвет переднего плана. |
| [EmbedBackground](../../aspose.cad.imageoptions/vectorrasterizationoptions/embedbackground) { get; set; } | Если цвет фона не равен цвету фона по умолчанию выходного формата (белый для PDF и SVG, прозрачный для растра) должен быть встроен в выходное изображение (если не встроен, фон будет установлен по умолчанию для выходной системы рендеринга, но цвет содержимого, который зависит от цвета фона, будет отображаться с использованием указанного цвета фона) |
| [GraphicsOptions](../../aspose.cad.imageoptions/vectorrasterizationoptions/graphicsoptions) { get; set; } | Получает или задает параметры для рендеринга растрового изображения внутри pdf (если для параметра ContentAsBitmap установлено значение true). |
| [LayoutPageSizes](../../aspose.cad.imageoptions/vectorrasterizationoptions/layoutpagesizes) { get; set; } | Получает или задает размеры страницы макета. |
| [Margins](../../aspose.cad.imageoptions/vectorrasterizationoptions/margins) { get; set; } | Получает или устанавливает поля. |
| [PageHeight](../../aspose.cad.imageoptions/vectorrasterizationoptions/pageheight) { get; set; } | Получает или задает высоту страницы. |
| [PageSize](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagesize) { get; set; } | Получает или задает размер страницы. |
| [PageWidth](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagewidth) { get; set; } | Получает или задает ширину страницы. |
| [RelativePosition](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativeposition) { get; set; } | Положение левого верхнего угла экспортируемой области относительно всего изображения документа, в относительных единицах - 0,0 вверху слева, 1,1 внизу изображения документа. |
| [RelativeScale](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativescale) { get; set; } | Масштаб экспортируемой области относительно всего изображения документа. Рассчитывается как отношение соответствующего размера экспортируемой области к большему размеру экспортируемого документа. |
| [UnitType](../../aspose.cad.imageoptions/vectorrasterizationoptions/unittype) { get; set; } | Получает или устанавливает тип единицы измерения результата экспорта. |

### Смотрите также

* пространство имен [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->