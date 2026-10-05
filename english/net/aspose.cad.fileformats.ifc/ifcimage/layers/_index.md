---
title: "IfcImage.Layers"
linktitle: "Layers"
articleTitle: "Layers"
second_title: "Aspose.CAD for .NET API Reference"
description: "IfcImage property. Gets list of all the layers that are present in the image Gets the layers from the image. using (IfcImage ifcImage = (IfcImage)Image.Load(..."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.ifc/ifcimage/layers/"
product_version: "26.9"
---
## IfcImage.Layers property

Gets list of all the layers that are present in the image
 
 Gets the layers from the image.
 
 using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
 {
 var layers = ifcImage.Layers
 }

```csharp
public IList<string> Layers { get; }
```

## Examples

Gets the layers from the image.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var layers = ifcImage.Layers
}
```

### See Also

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

