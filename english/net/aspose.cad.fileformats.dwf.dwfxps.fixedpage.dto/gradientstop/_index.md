---
title: "GradientStop Class"
linktitle: "GradientStop"
articleTitle: "GradientStop"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.GradientStop class. The gradient stop. The GradientStop element is used by both the LinearGradientBrush and R..."
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/"
keywords: "GradientStop, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GradientStop class

The gradient stop.
 The GradientStop element is used by both the [LinearGradientBrush](../lineargradientbrush/) and [RadialGradientBrush](../radialgradientbrush/) elements to define the location
 and range of color progression for rendering a gradient.
 For linear gradient brushes, the offset value of 0.0 is mapped to the start point of the gradient,
 and the offset value of 1.0 is mapped to the end point.
 Intermediate offset values are interpolated between these two points to determine their location.
 For radial gradient brushes, the offset value of 0.0 is mapped to the gradient origin location.
 The offset value of 1.0 is mapped to the circumference of the ellipse as determined by the center,
 x radius, and y radius.Offsets between 0.0 and 1.0 are positioned at a location interpolated between these points.

```csharp
public class GradientStop
```

## Constructors

| Name | Description |
| --- | --- |
| [GradientStop](gradientstop/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/color/) { get; set; } | Gets or sets the color. Specifies the gradient stop color. |
| [Offset](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/offset/) { get; set; } | Gets or sets the offset. Specifies the gradient offset. The offset indicates a point along the progression of the gradient at which a color is specified. Colors between gradient offsets in the progression are interpolated. |

### See Also

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

