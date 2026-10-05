---
title: "IfcImage.Header"
linktitle: "Header"
articleTitle: "Header"
second_title: "Aspose.CAD for .NET API Reference"
description: "IfcImage property. Gets the header."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.ifc/ifcimage/header/"
product_version: "26.9"
---
## IfcImage.Header property

Gets the header.

```csharp
public IfcHeader Header { get; }
```

### Property Value

The header.

## Examples

Gets the header from the image.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var header = ifcImage.Header        
}
```

### See Also

* class [IfcHeader](../../../aspose.cad.fileformats.ifc.header/ifcheader/)
* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

