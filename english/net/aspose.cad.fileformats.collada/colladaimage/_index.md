---
title: ColladaImage
second_title: Aspose.CAD for .NET API Reference
description: 
type: docs
weight: 4200
url: /net/aspose.cad.fileformats.collada/colladaimage/
---
## ColladaImage class

COLLADA image

```csharp
public sealed class ColladaImage : Image
```

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.cad/image/bounds) { get; } | Gets the image bounds. |
| [Container](../../aspose.cad/image/container) { get; } | Gets the [`Image`](../../aspose.cad/image) container. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer) { get; } |  |
| [Disposed](../../aspose.cad/disposableobject/disposed) { get; } |  |
| override [Height](../../aspose.cad.fileformats.collada/colladaimage/height) { get; } | Gets the image height. |
| override [IsCached](../../aspose.cad.fileformats.collada/colladaimage/iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Palette](../../aspose.cad/image/palette) { get; set; } | Gets or sets the color palette. |
| [Size](../../aspose.cad/image/size) { get; } | Gets the image size. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype) { get; } | Assumed unit type when UnitType is set to Unitless |
| [UnitType](../../aspose.cad/image/unittype) { get; } | Gets current unit type. |
| override [Width](../../aspose.cad.fileformats.collada/colladaimage/width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.collada/colladaimage/cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.cad/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.cad/disposableobject/dispose)() |  |
| virtual [GetStrings](../../aspose.cad/image/getstrings)() | Gets all string values from image. |
| [Save](../../aspose.cad/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.cad/datastreamsupporter/save)(Stream) |  |
| virtual [Save](../../aspose.cad/datastreamsupporter/save)(string) |  |
| [Save](../../aspose.cad/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save)(string, bool) |  |
| virtual [Save](../../aspose.cad/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |

### See Also

* class [Image](../../aspose.cad/image)
* namespace [Aspose.CAD.FileFormats.Collada](../../aspose.cad.fileformats.collada)
* assembly [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->