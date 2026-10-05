---
title: "SatImage Class"
linktitle: "SatImage"
articleTitle: "SatImage"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Sat.SatImage class. SAT image class."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.sat/satimage/"
keywords: "SatImage, Aspose.CAD.FileFormats.Sat, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SatImage class

SAT image class.

```csharp
public class SatImage : BRepImage
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Gets the annotation service. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Gets the image bounds. |
| [Container](../../aspose.cad/image/container/) { get; } | Gets the [`Image`](../../aspose.cad/image/) container. |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Gets or sets the custom properties. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| override [Depth](../../aspose.cad.fileformats.sat/brepimage/depth/) { get; } | Gets the image depth. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [Height](../../aspose.cad.fileformats.sat/brepimage/height/) { get; } | Gets the image height. |
| override [IsCached](../../aspose.cad.fileformats.sat/brepimage/iscached/) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Gets or sets the color palette. |
| [Size](../../aspose.cad/image/size/) { get; } | Gets the image size. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Gets current unit type. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Assumed unit type when UnitType is set to Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.sat/brepimage/width/) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.sat/brepimage/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | Gets all string values from image. |
| override [Save](../../aspose.cad/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | Saves the object's data to the specified file location. |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |

### See Also

* class [BRepImage](../brepimage/)
* namespace [Aspose.CAD.FileFormats.Sat](../../aspose.cad.fileformats.sat/)
* assembly [Aspose.CAD](../../)

