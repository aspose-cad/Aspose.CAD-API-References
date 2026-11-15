---
title: "Класс PageSizingOptions"
linktitle: "PageSizingOptions"
articleTitle: "PageSizingOptions"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.ImageOptions.PageSizingOptions."
type: docs
weight: 340
url: "/net/aspose.cad.imageoptions/pagesizingoptions/"
keywords: "PageSizingOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PageSizingOptions class



```csharp
public class PageSizingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PageSizingOptions](pagesizingoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Depth](../../aspose.cad.imageoptions/pagesizingoptions/depth/) { get; set; } | Глубина выходной страницы. Если она установлена, масштабирование источника и переопределения типа единиц не используются, так как размер страницы задаётся явно. |
| [Height](../../aspose.cad.imageoptions/pagesizingoptions/height/) { get; set; } | Высота выходной страницы. Если она установлена, масштабирование источника и переопределения типа единиц не используются, так как размер страницы задаётся явно. |
| [LayoutName](../../aspose.cad.imageoptions/pagesizingoptions/layoutname/) { get; set; } | Имя страницы, к которой должны применяться эти параметры. Если NULL, то первый объект PageSizingOptions в списке будет применён к любым страницам, которые должны быть экспортированы, но не имеют PageSizingOptions с соответствующим именем. |
| [LegacySizingMode](../../aspose.cad.imageoptions/pagesizingoptions/legacysizingmode/) { get; set; } | Если true, Aspose.CAD будет использовать устаревший режим масштабирования для выходного формата. |
| [Margins](../../aspose.cad.imageoptions/pagesizingoptions/margins/) { get; set; } | Размер полей для текущей страницы. Если размер выходной страницы задаётся явно через Width\Height\Depth, поля вычитаются из размера. Если размер выходной страницы вычисляется из размера источника, поля добавляются. |
| [MarginsUnitType](../../aspose.cad.imageoptions/pagesizingoptions/marginsunittype/) { get; set; } | Тип единиц для полей. Если не задан, будет использоваться тип единиц выходного формата по умолчанию. |
| [OverrideOutputUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overrideoutputunittype/) { get; set; } | Переопределяет единицы измерения выходного формата. Например, единицы PDF — пункты, которые равны 1/72 дюйма. Источник 1x1 дюйм будет экспортирован как 72x72 в PDF. Если OverrideOutputUnitType установить в Inch, вывод будет 1x1. |
| [OverrideSourceUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overridesourceunittype/) { get; set; } | Переопределяет единицы измерения исходной страницы. Если источник 1x1 дюйм, а эта опция установлена в Meters, источник считается 1x1 метр. |
| [SourceScaling](../../aspose.cad.imageoptions/pagesizingoptions/sourcescaling/) { get; set; } | На сколько следует увеличить размер источника, игнорируя единицы. Если источник 1x1 дюйм, а SourceScaling = 10, источник интерпретируется как 10x10 дюймов. |
| [Width](../../aspose.cad.imageoptions/pagesizingoptions/width/) { get; set; } | Ширина выходной страницы. Если она установлена, масштабирование источника и переопределения типа единиц не используются, так как размер страницы задаётся явно. |
| [Zoom](../../aspose.cad.imageoptions/pagesizingoptions/zoom/) { get; set; } | Это коэффициент масштабирования, позволяющий сделать чертёж немного меньше, чтобы вертикальные и горизонтальные линии помещались на холсте. Значение по умолчанию равно 1 - (0.0026 * 2), поскольку команда ZOOM EXTENTS в Autocad оставляет примерно 0,26 % от каждой стороны в виде зазора. |

### См. также

* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

