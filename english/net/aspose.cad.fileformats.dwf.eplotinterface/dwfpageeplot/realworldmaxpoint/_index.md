---
title: "DwfPageEPlot.RealWorldMaxPoint"
linktitle: "RealWorldMaxPoint"
articleTitle: "RealWorldMaxPoint"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwfPageEPlot property. Gets the maximum value of entities coordinates scaled to real-world units."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldmaxpoint/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldMaxPoint property

Gets the maximum value of entities coordinates scaled to real-world units.

```csharp
public Cad3DPoint RealWorldMaxPoint { get; }
```

### Return Value

The maximum value of entities coordinates scaled to real-world units or 'null' value, if resource does not contain the 'Units' operand.

## Examples

Gets width and height of image scaled to real-world units.

```csharp
string file = "ExampleFile.dwf";
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        Cad3DPoint maxPoint = page.RealWorldMaxPoint;
        Cad3DPoint minPoint = page.RealWorldMinPoint;
        double width = maxPoint.X - minPoint.X;
        double height = maxPoint.Y - minPoint.Y;
    }
}
```

### See Also

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

