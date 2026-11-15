---
title: "Класс BitmapImage"
linktitle: "BitmapImage"
articleTitle: "BitmapImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Bitmap.BitmapImage class. Универсальный класс, используемый для хранения любых растровых данных независимо от формата."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.bitmap/bitmapimage/"
keywords: "BitmapImage, Aspose.CAD.FileFormats.Bitmap, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## BitmapImage class

Универсальный класс, используемый для хранения любых растровых данных независимо от формата.

```csharp
public class BitmapImage : Image
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [Data](../../aspose.cad.fileformats.bitmap/bitmapimage/data/) { get; } |  |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | Получает глубину изображения. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.bitmap/bitmapimage/height/) { get; } | Получает высоту изображения. |
| override [IsCached](../../aspose.cad.fileformats.bitmap/bitmapimage/iscached/) { get; } | Определяет, кэшировано ли изображение |
| [LoadOptions](../../aspose.cad.fileformats.bitmap/bitmapimage/loadoptions/) { get; } | Параметры, с которыми было загружено это изображение. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.bitmap/bitmapimage/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.bitmap/bitmapimage/cachedata/)() |  |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | Получает все строковые значения из изображения. |
| override [Save](../../aspose.cad/image/save/)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в заданном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла в соответствии с параметрами сохранения. |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в заданном формате файла в соответствии с параметрами сохранения. |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла в соответствии с параметрами сохранения. |

### См. также

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.Bitmap](../../aspose.cad.fileformats.bitmap/)
* assembly [Aspose.CAD](../../)

