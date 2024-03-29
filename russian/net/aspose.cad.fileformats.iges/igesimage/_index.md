---
title: IgesImage
second_title: Справочник по Aspose.CAD для .NET API
description: Класс изображения IGES
type: docs
weight: 28400
url: /ru/net/aspose.cad.fileformats.iges/igesimage/
---
## IgesImage class

Класс изображения IGES

```csharp
public class IgesImage : Image
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.cad/image/bounds) { get; } | Получает границы изображения. |
| [Container](../../aspose.cad/image/container) { get; } | Получает[`Image`](../../aspose.cad/image)контейнер. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer) { get; } |  |
| [Disposed](../../aspose.cad/disposableobject/disposed) { get; } |  |
| override [Height](../../aspose.cad.fileformats.iges/igesimage/height) { get; } | Получает высоту изображения |
| override [IsCached](../../aspose.cad.fileformats.iges/igesimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли данные объекта в данный момент и чтение данных не требуется. |
| [Palette](../../aspose.cad/image/palette) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size) { get; } | Получает размер изображения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype) { get; } | Предполагаемый тип юнита, когда для UnitType установлено значение Unitless |
| [UnitType](../../aspose.cad/image/unittype) { get; } | Получает тип текущего юнита. |
| override [Width](../../aspose.cad.fileformats.iges/igesimage/width) { get; } | Получает ширину изображения |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.iges/igesimage/cachedata)() | Кэширует данные и гарантирует, что не будет выполняться дополнительная загрузка данных из базового[`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.cad/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.cad/disposableobject/dispose)() |  |
| [GetDrawables](../../aspose.cad.fileformats.iges/igesimage/getdrawables)() | Получает геометрическое представление документа |
| override [GetStrings](../../aspose.cad.fileformats.iges/igesimage/getstrings)() | Получает все строковые значения из изображения. |
| [Save](../../aspose.cad/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.cad/datastreamsupporter/save)(Stream) |  |
| virtual [Save](../../aspose.cad/datastreamsupporter/save)(string) |  |
| [Save](../../aspose.cad/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save)(string, bool) |  |
| virtual [Save](../../aspose.cad/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |

### Смотрите также

* class [Image](../../aspose.cad/image)
* пространство имен [Aspose.CAD.FileFormats.Iges](../../aspose.cad.fileformats.iges)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
