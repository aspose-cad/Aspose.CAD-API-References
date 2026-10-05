---
title: "Image.Palette"
linktitle: "Palette"
articleTitle: "Palette"
second_title: "Aspose.CAD for .NET API Reference"
description: "Image property. Gets or sets the color palette."
type: docs
weight: 230
url: "/net/aspose.cad/image/palette/"
product_version: "26.9"
---
## Image.Palette property

Gets or sets the color palette.

```csharp
public IColorPalette Palette { get; set; }
```

### Property Value

The color palette.

## Examples

Asserts DGN drawing contains palette

```csharp
var fileName = @"C:\path\drawing.dgn";
using (DgnImage drawing = (DgnImage)Image.Load(fileName))
{
    AssertLegacy.IsNotEmpty(drawing.Palette);
}
```

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

