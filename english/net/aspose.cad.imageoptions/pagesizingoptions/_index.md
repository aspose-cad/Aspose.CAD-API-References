---
title: "PageSizingOptions Class"
linktitle: "PageSizingOptions"
articleTitle: "PageSizingOptions"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.ImageOptions.PageSizingOptions class."
type: docs
weight: 340
url: "/net/aspose.cad.imageoptions/pagesizingoptions/"
keywords: "PageSizingOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PageSizingOptions class



```csharp
public class PageSizingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PageSizingOptions](pagesizingoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Depth](../../aspose.cad.imageoptions/pagesizingoptions/depth/) { get; set; } | Depth of the output page. If it is set, source scaling and unit type overrides are not used as page size is set explicitly. |
| [Height](../../aspose.cad.imageoptions/pagesizingoptions/height/) { get; set; } | Height of the output page. If it is set, source scaling and unit type overrides are not used as page size is set explicitly. |
| [LayoutName](../../aspose.cad.imageoptions/pagesizingoptions/layoutname/) { get; set; } | Name of the page that these options should be applied for. If NULL, then first PageSizingOptions in list will be applied to any pages that should be exported but do not have PageSizingOptions with corresponding name |
| [LegacySizingMode](../../aspose.cad.imageoptions/pagesizingoptions/legacysizingmode/) { get; set; } | If true, Aspose.CAD would use legacy sizing mode for output format. |
| [Margins](../../aspose.cad.imageoptions/pagesizingoptions/margins/) { get; set; } | Size of margins for current page. If output page size is provided explicitly via Width\Height\Depth, margins are subtracted from the size. If output page size is calculated from source size, margins are added. |
| [MarginsUnitType](../../aspose.cad.imageoptions/pagesizingoptions/marginsunittype/) { get; set; } | Unit type for margins. If not set, will default to output format's units. |
| [OverrideOutputUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overrideoutputunittype/) { get; set; } | Overrides output format measurement units. For example, PDF's units are points which are 1/72 of an inch. The 1x1 inch source would be output as 72x72 to PDF. If OverrideOutputUnitType would be set to Inch, output would be 1x1. |
| [OverrideSourceUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overridesourceunittype/) { get; set; } | Overrides source page measurement units. If source is 1x1 inch, and this option is set to Meters, source is assumed to be 1x1 meter. |
| [SourceScaling](../../aspose.cad.imageoptions/pagesizingoptions/sourcescaling/) { get; set; } | How much source size should be scaled up disregarding units. If source is 1x1 inch, and SourceScaling = 10, source is interpreted as 10x10 inch. |
| [Width](../../aspose.cad.imageoptions/pagesizingoptions/width/) { get; set; } | Width of the output page. If it is set, source scaling and unit type overrides are not used as page size is set explicitly. |
| [Zoom](../../aspose.cad.imageoptions/pagesizingoptions/zoom/) { get; set; } | This is a scaling factor to make drawing a bit smaller to fit vertical and horizontal lines into canvas. Default value is 1 - (0.0026 * 2) because during ZOOM EXTENTS command in Autocad it leaves about 0.26% from each side as a gap. |

### See Also

* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

