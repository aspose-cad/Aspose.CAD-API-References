---
title: ColorMap
second_title: Справочник по Aspose.CAD для .NET API
description: Получает или задает карту цветов.
type: docs
weight: 70
url: /ru/net/aspose.cad.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Получает или задает карту цветов.

```csharp
public ushort[] ColorMap { get; set; }
```

### Стоимость имущества

Карта цветов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | значение |
| [TiffImageException](../../../aspose.cad.cadexceptions.imageformats/tiffimageexception) | Цветовая карта может быть определена только для отсчетов на пиксель, равных 1. или Количество битов на выборку не определено. |
| ArgumentOutOfRangeException | значение Длина массива должна соответствовать следующей формуле:3 * (2 ** BitsPerSample). |

### Смотрите также

* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.CAD.ImageOptions](../../tiffoptions)
* сборка [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->