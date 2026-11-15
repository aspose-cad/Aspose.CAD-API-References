---
title: "Класс PostScriptImage"
linktitle: "PostScriptImage"
articleTitle: "PostScriptImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.PostScript.PostScriptImage class. Класс изображения PostScript."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.postscript/postscriptimage/"
keywords: "PostScriptImage, Aspose.CAD.FileFormats.PostScript, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PostScriptImage class

Класс изображения PostScript.

```csharp
public class PostScriptImage : Image
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | Получает глубину изображения. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.postscript/postscriptimage/height/) { get; } | Получает высоту изображения в пунктах (72 пункта на дюйм). |
| override [IsCached](../../aspose.cad.fileformats.postscript/postscriptimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли данные объекта в данный момент и не требуется ли чтение данных. |
| [MaxPoint](../../aspose.cad.fileformats.postscript/postscriptimage/maxpoint/) { get; } | Получает максимальную координату точки элементов рисования всех страниц в пунктах (72 пункта на дюйм). |
| [MinPoint](../../aspose.cad.fileformats.postscript/postscriptimage/minpoint/) { get; } | Получает минимальную координату точки элементов рисования всех страниц в пунктах (72 пункта на дюйм). |
| [Pages](../../aspose.cad.fileformats.postscript/postscriptimage/pages/) { get; } | Получает страницы изображения. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.postscript/postscriptimage/width/) { get; } | Получает ширину изображения в пунктах (72 пункта на дюйм). |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.postscript/postscriptimage/cachedata/)() | Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| override [GetStrings](../../aspose.cad.fileformats.postscript/postscriptimage/getstrings/)() | Получает все строковые значения из изображения. |
| [GetUnitTranslationCoefficient](../../aspose.cad.fileformats.postscript/postscriptimage/getunittranslationcoefficient/)(UnitType) | Получает коэффициент преобразования типа единицы измерения |
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
* namespace [Aspose.CAD.FileFormats.PostScript](../../aspose.cad.fileformats.postscript/)
* assembly [Aspose.CAD](../../)

