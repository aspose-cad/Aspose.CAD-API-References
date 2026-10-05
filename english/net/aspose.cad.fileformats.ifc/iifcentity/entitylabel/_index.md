---
title: "IIfcEntity.EntityLabel"
linktitle: "EntityLabel"
articleTitle: "EntityLabel"
second_title: "Aspose.CAD for .NET API Reference"
description: "IIfcEntity property. Gets the entity label. Each entity has its label, which is unique and represents it in the file"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.ifc/iifcentity/entitylabel/"
product_version: "26.9"
---
## IIfcEntity.EntityLabel property

Gets the entity label.
 Each entity has its label, which is unique and represents it in the file

```csharp
public int EntityLabel { get; }
```

### Property Value

The entity label.

## Examples

Gets first entity label from.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var label = ifcImage._entities[0].EntityLabel
}
```

### See Also

* interface [IIfcEntity](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

