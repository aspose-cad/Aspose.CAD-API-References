---
title: SvgOptions
second_title: Справочник по Aspose.CAD для .NET API
description: Параметры создания файла формата SVG.
type: docs
weight: 29880
url: /ru/net/aspose.cad.imageoptions/svgoptions/
---
## SvgOptions class

Параметры создания файла формата SVG.

```csharp
public class SvgOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgOptions](svgoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Callback](../../aspose.cad.imageoptions/svgoptions/callback) { get; set; } | Получает или задает параметры хранилища шрифтов. |
| [ColorType](../../aspose.cad.imageoptions/svgoptions/colortype) { get; set; } | Получает или задает тип цвета для изображения SVG. |
| [InterruptionToken](../../aspose.cad/imageoptionsbase/interruptiontoken) { get; set; } | Токен, который можно использовать для прерывания операции экспорта |
| [Layers](../../aspose.cad/imageoptionsbase/layers) { get; set; } | Получает или устанавливает имена слоев, которые необходимо экспортировать. Все данные будут экспортированы без слоев, если имена не заданы. |
| [MinimumAbsoluteNonscaledLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumabsolutenonscaledlinewidth) { get; set; } | Линии с шириной в пикселях меньше этой будут масштабироваться |
| [MinimumLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumlinewidth) { get; set; } | Минимальная ширина линии (т.е. ширина линии нулевой ширины) относительно минимальной немасштабированной ширины линии |
| [MinimumRelativeLinewidthRatio](../../aspose.cad.imageoptions/svgoptions/minimumrelativelinewidthratio) { get; set; } | Линии шириной меньше размера изображения \ MinimumRelativeLinewidthRatio будут перемасштабированы, если используется относительное масштабирование |
| virtual [Palette](../../aspose.cad/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [Pc3File](../../aspose.cad/imageoptionsbase/pc3file) { get; set; } | Получает или задает полное имя файла PC3. |
| [RescaleSubpixelLinewidths](../../aspose.cad.imageoptions/svgoptions/rescalesubpixellinewidths) { get; set; } | Должна ли быть изменена ширина подпикселя |
| virtual [ResolutionSettings](../../aspose.cad/imageoptionsbase/resolutionsettings) { get; set; } | Получает или устанавливает параметры разрешения. |
| [Rotation](../../aspose.cad/imageoptionsbase/rotation) { get; set; } | Получает или устанавливает параметр для поворота, отражения или поворота и отражения изображения.. |
| [Source](../../aspose.cad/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| override [TargetFormat](../../aspose.cad.imageoptions/svgoptions/targetformat) { get; } |  |
| [TextAsShapes](../../aspose.cad.imageoptions/svgoptions/textasshapes) { get; set; } | Получает или задает значение, указывающее, должен ли текст преобразовываться в фигуры. По умолчанию текст будет преобразован в фигуры. |
| [Timeout](../../aspose.cad/imageoptionsbase/timeout) { get; set; } | Значение времени ожидания для операции экспорта |
| [UseAbsoluteRescaling](../../aspose.cad.imageoptions/svgoptions/useabsoluterescaling) { get; set; } | Должна ли быть определена минимальная ширина строки без перемасштабирования относительно размера всего изображения (если false) или в пикселях (если true) |
| [UserWatermarkColor](../../aspose.cad/imageoptionsbase/userwatermarkcolor) { get; set; } | Цвет пользовательского водяного знака |
| [UserWatermarkText](../../aspose.cad/imageoptionsbase/userwatermarktext) { get; set; } | Текст для пользовательского водяного знака |
| [VectorRasterizationOptions](../../aspose.cad/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| virtual [XmpData](../../aspose.cad/imageoptionsbase/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

### Смотрите также

* class [ImageOptionsBase](../../aspose.cad/imageoptionsbase)
* пространство имен [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->