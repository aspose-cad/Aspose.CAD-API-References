---
title: "ObjOptions Class"
linktitle: "ObjOptions"
articleTitle: "ObjOptions"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.ImageOptions.ObjOptions class. The OBJ options."
type: docs
weight: 330
url: "/net/aspose.cad.imageoptions/objoptions/"
keywords: "ObjOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ObjOptions class

The OBJ options.

```csharp
public class ObjOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [ObjOptions](objoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | Token that can be used to interrupt export operation |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | Gets or sets a of layer names must be exported. All data will be exported without layers if names is not sets. |
| [MtlFileName](../../aspose.cad.imageoptions/objoptions/mtlfilename/) { get; set; } | Gets or sets the MTL file name to be written inside a file. |
| [MtlFileStream](../../aspose.cad.imageoptions/objoptions/mtlfilestream/) { get; set; } | Gets or sets the MTL stream to output mtl file to. |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | Whether to convert contents to target format as is, or render to lines and then save. Convert mode is availible for DWG\DXF, DWF source formats. |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | Gets or sets the PC3 file full name. |
| [Precision](../../aspose.cad.imageoptions/objoptions/precision/) { get; set; } | Gets or sets the precision during faces formation. Lower value means more faces and details. Bigger value could lead to missing small parts of the drawing, e.g., small text. |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | Gets or sets a value indicating which image sizes to use when rendering: graphic sizes (true, default) or set in metadata (false). |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | Gets or sets the parameter for rotate, flip, or rotate and flip the image.. |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| override [TargetFormat](../../aspose.cad.imageoptions/objoptions/targetformat/) { get; } |  |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | Timeout value for export operation (in milliseconds) |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | Color for user-generated watermark |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | Text for user-generated watermark |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

### See Also

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

