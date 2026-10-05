---
title: "SvgOptions Class"
linktitle: "SvgOptions"
articleTitle: "SvgOptions"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.ImageOptions.SvgOptions class. The SVG file format creation options."
type: docs
weight: 520
url: "/net/aspose.cad.imageoptions/svgoptions/"
keywords: "SvgOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SvgOptions class

The SVG file format creation options.

```csharp
public class SvgOptions : ImageOptionsBase, ITextAsShapesOptions
```

## Examples

// Renders loaded file and saves it to SVG

```csharp
using (var img = Image.Load(file))
{
    CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
    SvgOptions opt = new SvgOptions();

    opt.VectorRasterizationOptions = cadRasterizationOptions;
    cadRasterizationOptions.DrawType = CadDrawTypeMode.UseObjectColor;
    img.Save(outSvg, opt);
}
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgOptions](svgoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Callback](../../aspose.cad.imageoptions/svgoptions/callback/) { get; set; } | Gets or sets the callback that can be used to store image and font binary data as user needs |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | Token that can be used to interrupt export operation |
| [ExportEntityIDs](../../aspose.cad.imageoptions/svgoptions/exportentityids/) { get; set; } | Whether to include source file entity IDs into output - specific per-source-format support is needed |
| [ExportLayers](../../aspose.cad.imageoptions/svgoptions/exportlayers/) { get; set; } | Whether to add layer information to exported entities - specific per-source-format support is needed |
| [GroupingMode](../../aspose.cad.imageoptions/svgoptions/groupingmode/) { get; set; } | Whether to group objects |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | Gets or sets a of layer names must be exported. All data will be exported without layers if names is not sets. |
| [MinimumAbsoluteNonscaledLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumabsolutenonscaledlinewidth/) { get; set; } | Lines with width in pixels less than this will be rescaled if absolute rescaling treshold |
| [MinimumLinewidth](../../aspose.cad.imageoptions/svgoptions/minimumlinewidth/) { get; set; } | Minumum width of the line relative to minimum non-rescaled linewidth. A line with width of 0 would be drawn with this width if rescaling is used ( as it is by default), lines thicker than that will be drawn thicker until they reach rescaling treshold, lines thicker than that won't be rescaled. |
| [MinimumRelativeLinewidthRatio](../../aspose.cad.imageoptions/svgoptions/minimumrelativelinewidthratio/) { get; set; } | Lines with width less than image's size\minimumRelativeLinewidthRatio will be rescaled if relative rescaling treshold is used. A smaller dimension is picked as image size. |
| [OmitDeclaration](../../aspose.cad.imageoptions/svgoptions/omitdeclaration/) { get; set; } | Whether to omit DOCTYPE declaration - embedded SVG doesn't need it. |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | Whether to convert contents to target format as is, or render to lines and then save. Convert mode is availible for DWG\DXF, DWF source formats. |
| virtual [Palette](../../aspose.cad.imageoptions/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | Gets or sets the PC3 file full name. |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | Gets or sets a value indicating which image sizes to use when rendering: graphic sizes (true, default) or set in metadata (false). |
| [RescaleSubpixelLinewidths](../../aspose.cad.imageoptions/svgoptions/rescalesubpixellinewidths/) { get; set; } | Whether sub-pixel linewidths should be rescaled. If set to true, lines thinner than a width specified by other options will be drawn thicker, asymptotically approaching the minimum width |
| virtual [ResolutionSettings](../../aspose.cad.imageoptions/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | Gets or sets the parameter for rotate, flip, or rotate and flip the image.. |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| override [TargetFormat](../../aspose.cad.imageoptions/svgoptions/targetformat/) { get; } |  |
| [TextAsShapes](../../aspose.cad.imageoptions/svgoptions/textasshapes/) { get; set; } | Gets or sets a value indicating whether text must be converted as shapes. By default text will be converted to shapes, so it won't be selectable. |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | Timeout value for export operation (in milliseconds) |
| [UseAbsoluteRescaling](../../aspose.cad.imageoptions/svgoptions/useabsoluterescaling/) { get; set; } | Wether minimum non-rescaled line widh should be defined relative to whole image size (if false) or in pixels (if true). If false, use to specify maximum rate of image size to line width when line won't be rescaled up yet. If true, use to specify minimum unscaled width in pixels |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | Color for user-generated watermark |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | Text for user-generated watermark |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.cad.imageoptions/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

### See Also

* [ImageOptionsBase](../imageoptionsbase/)
* class [ImageOptionsBase](../imageoptionsbase/)
* interface [ITextAsShapesOptions](../itextasshapesoptions/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

