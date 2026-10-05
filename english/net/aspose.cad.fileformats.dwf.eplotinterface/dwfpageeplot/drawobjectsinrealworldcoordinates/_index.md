---
title: "DwfPageEPlot.DrawObjectsInRealWorldCoordinates"
linktitle: "DrawObjectsInRealWorldCoordinates"
articleTitle: "DrawObjectsInRealWorldCoordinates"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwfPageEPlot property. Gets the collection of entities scaled to real-world units from resource with role '2d streaming graphics'."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/drawobjectsinrealworldcoordinates/"
product_version: "26.9"
---
## DwfPageEPlot.DrawObjectsInRealWorldCoordinates property

Gets the collection of entities scaled to real-world units from resource with role '2d streaming graphics'.

```csharp
public DwfWhipDrawable[] DrawObjectsInRealWorldCoordinates { get; }
```

### Return Value

The collection of entities scaled to real-world units or 'null' value, if resource does not contain the 'Units' operand.

## Examples

Retrieves the collection of entities scaled to real-world units.

```csharp
string file = "ExampleFile.dwf";
DwfWhipDrawable[] result;
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        result = page.DrawObjectsInRealWorldCoordinates;
    }
}

foreach (DwfWhipDrawable s in result)
{
    Do something;
}
```

### See Also

* class [DwfWhipDrawable](../../../aspose.cad.fileformats.dwf.whip.objects.drawable/dwfwhipdrawable/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

