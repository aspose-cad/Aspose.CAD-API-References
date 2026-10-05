---
title: "DwfPageEPlot.RealWorldUnits"
linktitle: "RealWorldUnits"
articleTitle: "RealWorldUnits"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwfPageEPlot property. Gets the real-world scale units. String label that indicates the unit of measure that scale represents when measuring a single logical..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldunits/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldUnits property

Gets the real-world scale units.
 String label that indicates the unit of measure that scale represents when measuring a single logical coordinate.

```csharp
public string RealWorldUnits { get; }
```

### Return Value

The the real-world scale units or empty string, if the unit name is not specified or resource does not contain the 'Units' operand.

## Examples

Gets the real-world scale units.

```csharp
string file = "ExampleFile.dwf";
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        string unitsName =page.RealWorldUnits;
    }
}
```

### See Also

* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

