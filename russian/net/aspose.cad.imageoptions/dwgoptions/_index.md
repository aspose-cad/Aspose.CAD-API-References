---
title: "Класс DwgOptions"
linktitle: "DwgOptions"
articleTitle: "DwgOptions"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.ImageOptions.DwgOptions. Параметры создания файлов формата DWG."
type: docs
weight: 130
url: "/net/aspose.cad.imageoptions/dwgoptions/"
keywords: "DwgOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DwgOptions class

Параметры создания формата файла DWG.

```csharp
public class DwgOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DwgOptions](dwgoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | Токен, который может использоваться для прерывания операции экспорта. |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | Gets or sets список имён слоёв, которые должны быть экспортированы. Все данные будут экспортированы без слоёв, если имена не заданы. |
| [OriginPosition](../../aspose.cad.imageoptions/dwgoptions/originposition/) { get; set; } | Получает или задает исходную позицию. |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | Определяет, следует ли конвертировать содержимое в целевой формат как есть, или отрисовывать в линии, а затем сохранять. Режим конвертации доступен для исходных форматов DWG\DXF, DWF. |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | Gets or sets полное имя файла PC3. |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | Gets or sets значение, указывающее, какие размеры изображений использовать при рендеринге: графические размеры (true, по умолчанию) или размеры из метаданных (false). |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets настройки разрешения. |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | Gets or sets параметр для поворота, отражения или их комбинации изображения. |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | Gets or sets источник, в котором создаётся изображение. |
| override [TargetFormat](../../aspose.cad.imageoptions/dwgoptions/targetformat/) { get; } | Целевой формат |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | Значение тайм-аута для операции экспорта (в миллисекундах) |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | Цвет для пользовательского водяного знака |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | Текст для пользовательского водяного знака |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры векторной растеризации. |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |

### См. также

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

