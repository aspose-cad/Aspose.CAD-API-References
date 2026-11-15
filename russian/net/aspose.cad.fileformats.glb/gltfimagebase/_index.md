---
title: "Класс GltfImageBase"
linktitle: "GltfImageBase"
articleTitle: "GltfImageBase"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.GltfImageBase. Представляет базовый класс сериализуемого объекта glTF schema2. Наследуется от ExtraProperties."
type: docs
weight: 230
url: "/net/aspose.cad.fileformats.glb/gltfimagebase/"
keywords: "GltfImageBase, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GltfImageBase class

Представляет базовый класс сериализуемого объекта glTF schema2.
Наследуется от [`ExtraProperties`](../extraproperties/).

```csharp
public class GltfImageBase : Image
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GltfImageBase](gltfimagebase/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Возвращает сервис аннотаций. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Возвращает границы изображения. |
| [Container](../../aspose.cad/image/container/) { get; } | Возвращает контейнер [`Image`](../../aspose.cad/image/). |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Получает или задает пользовательские свойства. |
| [Data](../../aspose.cad.fileformats.glb/gltfimagebase/data/) { get; } |  |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| override [Depth](../../aspose.cad.fileformats.glb/gltfimagebase/depth/) { get; } | Получает глубину изображения. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [Height](../../aspose.cad.fileformats.glb/gltfimagebase/height/) { get; } | Получает высоту изображения. |
| override [IsCached](../../aspose.cad.fileformats.glb/gltfimagebase/iscached/) { get; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Size](../../aspose.cad/image/size/) { get; } | Получает размер изображения. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Получает текущий тип единицы измерения. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Предполагаемый тип единицы, когда UnitType установлен в Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.glb/gltfimagebase/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.glb/gltfimagebase/cachedata/)() |  |
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
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

