---
title: "U3dImage Class"
linktitle: "U3dImage"
articleTitle: "U3dImage"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.U3d.U3dImage class. U3D image class"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.u3d/u3dimage/"
keywords: "U3dImage, Aspose.CAD.FileFormats.U3d, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## U3dImage class

U3D image class

```csharp
public class U3dImage : Image
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | Gets the annotation service. |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | Gets the image bounds. |
| [Container](../../aspose.cad/image/container/) { get; } | Gets the [`Image`](../../aspose.cad/image/) container. |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | Gets or sets the custom properties. |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| override [Depth](../../aspose.cad.fileformats.u3d/u3dimage/depth/) { get; } | Gets the depth. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [Height](../../aspose.cad.fileformats.u3d/u3dimage/height/) { get; } | Gets the image height. |
| override [IsCached](../../aspose.cad.fileformats.u3d/u3dimage/iscached/) { get; } | Determines whether image is cached |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | Gets or sets the color palette. |
| [Size](../../aspose.cad/image/size/) { get; } | Gets the image size. |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | Gets current unit type. |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | Assumed unit type when UnitType is set to Unitless |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.u3d/u3dimage/width/) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.u3d/u3dimage/cachedata/)() |  |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Disposes the current instance. |
| [GetLogicalModelsTree](../../aspose.cad.fileformats.u3d/u3dimage/getlogicalmodelstree/)() |  |
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

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.U3d](../../aspose.cad.fileformats.u3d/)
* assembly [Aspose.CAD](../../)

