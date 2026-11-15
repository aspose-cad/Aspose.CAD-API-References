---
title: "Класс DracoImage"
linktitle: "DracoImage"
articleTitle: "DracoImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Draco.DracoImage class. Представляет изображение в формате DRACO. Содержит информацию о границах чертежа, вершинах, гранях и атрибутах..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.draco/dracoimage/"
keywords: "DracoImage, Aspose.CAD.FileFormats.Draco, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DracoImage class

Представляет изображение в формате DRACO.
Содержит информацию о границах чертежа, вершинах, гранях и атрибутах.

```csharp
public class DracoImage : Image
```

## Примеры

Загрузка чертежа в формате DRACO.

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
...
}
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| override [Depth](../../aspose.cad.fileformats.draco/dracoimage/depth/) { get; } | Получает глубину изображения. Вычисляется как разница между максимальными и минимальными значениями координаты Z среди всех вершин. Минимально допустимая глубина — 0. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.draco/dracoimage/height/) { get; } | Получает высоту изображения. Вычисляется как разница между максимальными и минимальными значениями координаты Y среди всех вершин. Минимально допустимая высота — 1. |
| [Indices](../../aspose.cad.fileformats.draco/dracoimage/indices/) { get; set; } | Массив индексов граней сетки. |
| override [IsCached](../../aspose.cad.fileformats.draco/dracoimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли данные объекта в данный момент и не требуется ли чтение данных. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.draco/dracoimage/width/) { get; } | Получает ширину изображения. Вычисляется как разница между максимальными и минимальными значениями координаты X среди всех вершин. Минимально допустимая ширина равна 1. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.draco/dracoimage/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/) не будет выполнена. Не реализовано. |
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
* namespace [Aspose.CAD.FileFormats.Draco](../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../)

