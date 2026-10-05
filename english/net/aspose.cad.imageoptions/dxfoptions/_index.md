---
title: "DxfOptions Class"
linktitle: "DxfOptions"
articleTitle: "DxfOptions"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.ImageOptions.DxfOptions class. Class for DXF format output creation options"
type: docs
weight: 140
url: "/net/aspose.cad.imageoptions/dxfoptions/"
keywords: "DxfOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DxfOptions class

Class for DXF format output creation options

```csharp
public class DxfOptions : ImageOptionsBase, ITextAsLinesOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DxfOptions](dxfoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BezierPointCount](../../aspose.cad.imageoptions/dxfoptions/bezierpointcount/) { get; set; } | How many points to generate when converting Bezier curves to polylines if OutputMode is Render |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | Token that can be used to interrupt export operation |
| [ConvertMeshToLines](../../aspose.cad.imageoptions/dxfoptions/convertmeshtolines/) { get; set; } | Gets or sets a value indicating whether mesh geometry (e.g. 3D shells from DWF) should be exported as lines (wireframe) instead of MESH entities, so the resulting DXF contains only lines. Enabled by default: DWF to DXF conversion never produces meshes unless this is set to `false`. |
| [ConvertTextBeziers](../../aspose.cad.imageoptions/dxfoptions/converttextbeziers/) { get; set; } | Wether to convert Bezier curves in text outlines to multipoint polylines (converted to 4 points if false) f OutputMode is Render |
| [DxfFileFormat](../../aspose.cad.imageoptions/dxfoptions/dxffileformat/) { get; set; } | Gets or sets the DXF file format. |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | Gets or sets a of layer names must be exported. All data will be exported without layers if names is not sets. |
| [MergeLinesInsideContour](../../aspose.cad.imageoptions/dxfoptions/mergelinesinsidecontour/) { get; set; } | Gets or sets whether the sequence of polylines forming the contour should be merged into a single polyline. |
| [OriginPosition](../../aspose.cad.imageoptions/dxfoptions/originposition/) { get; set; } | Gets or sets the origin position. |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | Whether to convert contents to target format as is, or render to lines and then save. Convert mode is availible for DWG\DXF, DWF source formats. |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | Gets or sets the PC3 file full name. |
| [PrettyFormatting](../../aspose.cad.imageoptions/dxfoptions/prettyformatting/) { get; set; } |  |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | Gets or sets a value indicating which image sizes to use when rendering: graphic sizes (true, default) or set in metadata (false). |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | Gets or sets the parameter for rotate, flip, or rotate and flip the image.. |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| override [TargetFormat](../../aspose.cad.imageoptions/dxfoptions/targetformat/) { get; } |  |
| [TextAsLines](../../aspose.cad.imageoptions/dxfoptions/textaslines/) { get; set; } | Gets or sets a value indicating whether [text as lines] if OutputMode is Render. |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | Timeout value for export operation (in milliseconds) |
| [TryConvertToMesh](../../aspose.cad.imageoptions/dxfoptions/tryconverttomesh/) { get; set; } | Gets or sets a value indicating whether to attempt converting the file format to MESH. |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | Color for user-generated watermark |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | Text for user-generated watermark |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| [Version](../../aspose.cad.imageoptions/dxfoptions/version/) { get; set; } | Version of output DXF format |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

### See Also

* [ImageOptionsBase](../imageoptionsbase/)
* class [ImageOptionsBase](../imageoptionsbase/)
* interface [ITextAsLinesOptions](../itextaslinesoptions/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

