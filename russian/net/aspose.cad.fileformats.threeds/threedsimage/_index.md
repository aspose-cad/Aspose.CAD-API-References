---
title: "Класс ThreeDSImage"
linktitle: "ThreeDSImage"
articleTitle: "ThreeDSImage"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.ThreeDS.ThreeDSImage. Класс 3DS изображения. Позволяет загружать 3D модели из файлов 3DS. В примере ниже 3D модель загружена из файла и e..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.threeds/threedsimage/"
keywords: "ThreeDSImage, Aspose.CAD.FileFormats.ThreeDS, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ThreeDSImage class

Класс 3DS изображения.
Позволяет загружать 3D модели из файлов 3DS. В примере ниже 3D модель загружена из файла и экспортирована в PDF.
Полученный PDF‑файл будет содержать проекцию 3D модели, занимающей всю страницу с полями.

```csharp
public class ThreeDSImage : Image
```

## Примеры

Загрузка модели 3DS и экспорт ThreeDSImage в PDF‑документ нужного размера.

```csharp
using (ThreeDSImage image = (ThreeDSImage)Image.Load(inFileName))
{
    PdfOptions pdfOptions = new PdfOptions();
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PageWidth = 1600; 
    rasterizationOptions.PageHeight = 1600; 
    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    image.Save(outFileName, pdfOptions);
}
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreeDSImage](threedsimage/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AmbientLight](../../aspose.cad.fileformats.threeds/threedsimage/ambientlight/) { get; set; } | Цвет окружающего света. |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| override [Depth](../../aspose.cad.fileformats.threeds/threedsimage/depth/) { get; } | Получает глубину изображения. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [HasMaterials](../../aspose.cad.fileformats.threeds/threedsimage/hasmaterials/) { get; } | Возвращает значение, указывающее, имеет ли объект материалы. |
| [HasMeshes](../../aspose.cad.fileformats.threeds/threedsimage/hasmeshes/) { get; } | Возвращает значение, указывающее, имеет ли объект сетки. |
| override [Height](../../aspose.cad.fileformats.threeds/threedsimage/height/) { get; } | Получает высоту изображения. |
| override [IsCached](../../aspose.cad.fileformats.threeds/threedsimage/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и чтение данных не требуется. |
| [Materials](../../aspose.cad.fileformats.threeds/threedsimage/materials/) { get; } | Список материалов. |
| [MeshVersion](../../aspose.cad.fileformats.threeds/threedsimage/meshversion/) { get; } | Версия. |
| [Meshes](../../aspose.cad.fileformats.threeds/threedsimage/meshes/) { get; } | Список сеток. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| [ThreeDSVersion](../../aspose.cad.fileformats.threeds/threedsimage/threedsversion/) { get; } | Версия. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.threeds/threedsimage/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.threeds/threedsimage/cachedata/)() | Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/). |
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
| [UpdateImage](../../aspose.cad.fileformats.threeds/threedsimage/updateimage/)() |  |

### См. также

* [Image](../image/)
* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.ThreeDS](../../aspose.cad.fileformats.threeds/)
* assembly [Aspose.CAD](../../)

