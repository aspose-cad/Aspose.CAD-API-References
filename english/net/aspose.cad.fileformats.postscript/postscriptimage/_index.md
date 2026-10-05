---
title: "PostScriptImage Class"
linktitle: "PostScriptImage"
articleTitle: "PostScriptImage"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.PostScript.PostScriptImage class. PostScript image class."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.postscript/postscriptimage/"
keywords: "PostScriptImage, Aspose.CAD.FileFormats.PostScript, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PostScriptImage class

PostScript image class.

```csharp
public class PostScriptImage : Image
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Gets the annotation service. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Gets the image bounds. |
| [Container](../../aspose.cad/image/container/) { get; } | Gets the [`Image`](../../aspose.cad/image/) container. |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Gets or sets the custom properties. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | Gets the image depth. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [Height](../../aspose.cad.fileformats.postscript/postscriptimage/height/) { get; } | Gets the image height in points (72 points per inch). |
| override [IsCached](../../aspose.cad.fileformats.postscript/postscriptimage/iscached/) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [MaxPoint](../../aspose.cad.fileformats.postscript/postscriptimage/maxpoint/) { get; } | Gets the maximum point coordinate of drawing elements of all pages in points (72 points per inch). |
| [MinPoint](../../aspose.cad.fileformats.postscript/postscriptimage/minpoint/) { get; } | Gets the minimum point coordinate of drawing elements of all pages in points (72 points per inch). |
| [Pages](../../aspose.cad.fileformats.postscript/postscriptimage/pages/) { get; } | Gets the image pages. |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Gets or sets the color palette. |
| [Size](../../aspose.cad/image/size/) { get; } | Gets the image size. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Gets current unit type. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Assumed unit type when UnitType is set to Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.postscript/postscriptimage/width/) { get; } | Gets the image width in points (72 points per inch). |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.postscript/postscriptimage/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetStrings](../../aspose.cad.fileformats.postscript/postscriptimage/getstrings/)() | Gets all string values from image. |
| [GetUnitTranslationCoefficient](../../aspose.cad.fileformats.postscript/postscriptimage/getunittranslationcoefficient/)(UnitType) | Gets unit type convert coefficient |
| override [Save](../../aspose.cad/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | Saves the object's data to the specified file location. |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |

### See Also

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.PostScript](../../aspose.cad.fileformats.postscript/)
* assembly [Aspose.CAD](../../)

