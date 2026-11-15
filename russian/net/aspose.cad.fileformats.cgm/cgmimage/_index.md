---
title: "CgmImage класс"
linktitle: "CgmImage"
articleTitle: "CgmImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cgm.CgmImage класс. Представляет файл CGM в бинарном режиме"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cgm/cgmimage/"
keywords: "CgmImage, Aspose.CAD.FileFormats.Cgm, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CgmImage class

Представляет файл CGM в бинарном режиме

```csharp
public class CgmImage : Image
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CgmImage](cgmimage/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [Data](../../aspose.cad.fileformats.cgm/cgmimage/data/) { get; } | Предоставляет структуру данных CGM |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | Получает глубину изображения. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.cgm/cgmimage/height/) { get; } |  |
| override [IsCached](../../aspose.cad.fileformats.cgm/cgmimage/iscached/) { get; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.cgm/cgmimage/width/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.cgm/cgmimage/cachedata/)() |  |
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
* namespace [Aspose.CAD.FileFormats.Cgm](../../aspose.cad.fileformats.cgm/)
* assembly [Aspose.CAD](../../)

