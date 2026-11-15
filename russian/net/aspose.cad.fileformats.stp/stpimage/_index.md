---
title: "StpImage Класс"
linktitle: "StpImage"
articleTitle: "StpImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Stp.StpImage класс. Класс изображения STP."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.stp/stpimage/"
keywords: "StpImage, Aspose.CAD.FileFormats.Stp, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StpImage class

Класс изображения STP.

```csharp
public class StpImage : Image
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StpImage](stpimage/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Author](../../aspose.cad.fileformats.stp/stpimage/author/) { get; set; } |  |
| [Authorization](../../aspose.cad.fileformats.stp/stpimage/authorization/) { get; set; } |  |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Collections](../../aspose.cad.fileformats.stp/stpimage/collections/) { get; } | Полезные коллекции для упрощения перебора данных STP. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| override [Depth](../../aspose.cad.fileformats.stp/stpimage/depth/) { get; } | Получает глубину изображения. |
| [Description](../../aspose.cad.fileformats.stp/stpimage/description/) { get; set; } |  |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.stp/stpimage/height/) { get; } | Получает высоту изображения. |
| [ImplementationLevel](../../aspose.cad.fileformats.stp/stpimage/implementationlevel/) { get; set; } |  |
| override [IsCached](../../aspose.cad.fileformats.stp/stpimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли данные объекта в данный момент и не требуется ли чтение данных. |
| [Items](../../aspose.cad.fileformats.stp/stpimage/items/) { get; } |  |
| [Name](../../aspose.cad.fileformats.stp/stpimage/name/) { get; set; } |  |
| [Organization](../../aspose.cad.fileformats.stp/stpimage/organization/) { get; set; } |  |
| [OriginatingSystem](../../aspose.cad.fileformats.stp/stpimage/originatingsystem/) { get; set; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [PreprocessorVersion](../../aspose.cad.fileformats.stp/stpimage/preprocessorversion/) { get; set; } |  |
| [Schemas](../../aspose.cad.fileformats.stp/stpimage/schemas/) { get; } |  |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| [Timestamp](../../aspose.cad.fileformats.stp/stpimage/timestamp/) { get; set; } |  |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| [UnsupportedSchemas](../../aspose.cad.fileformats.stp/stpimage/unsupportedschemas/) { get; } |  |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.stp/stpimage/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [Append](../../aspose.cad.fileformats.stp/stpimage/append/)(StpImage) | Добавляет содержимое другого изображения STP. Эта функция позволяет объединять содержимое разных изображений STP. В приведённом ниже примере модели загружаются из файлов, а затем объединяются в одно изображение. Полученное изображение STP будет содержать все примитивы из каждого из загруженных файлов STP. |
| override [CacheData](../../aspose.cad.fileformats.stp/stpimage/cachedata/)() | Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [CopyHeaderValues](../../aspose.cad.fileformats.stp/stpimage/copyheadervalues/)(StpImage) |  |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [GetLogicalModelsTree](../../aspose.cad.fileformats.stp/stpimage/getlogicalmodelstree/)() | Выводит структуру дерева LogicalModels в строку. |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | Получает все строковые значения из изображения. |
| [GetTopLevelItems](../../aspose.cad.fileformats.stp/stpimage/gettoplevelitems/)() | Получает все элементы верхнего уровня (т. е. не связанные ни с каким другим элементом) в файле. |
| override [Save](../../aspose.cad/image/save/)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в заданном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла в соответствии с параметрами сохранения. |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в заданном формате файла в соответствии с параметрами сохранения. |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла в соответствии с параметрами сохранения. |
| [UpdateSize](../../aspose.cad.fileformats.stp/stpimage/updatesize/)() |  |

### См. также

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.Stp](../../aspose.cad.fileformats.stp/)
* assembly [Aspose.CAD](../../)

