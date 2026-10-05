---
title: "IfcImage.IsCached"
linktitle: "IsCached"
articleTitle: "IsCached"
second_title: "Aspose.CAD for .NET API Reference"
description: "IfcImage property. Gets a value indicating whether object's data is cached currently and no data reading is required. At present time always returns true"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.ifc/ifcimage/iscached/"
product_version: "26.9"
---
## IfcImage.IsCached property

Gets a value indicating whether object's data is cached currently and no data reading is required.
 At present time always returns true

```csharp
public override bool IsCached { get; }
```

### Property Value

`true` if object's data is cached; otherwise, `false`.

## Examples

Gets the isCached from the image.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var isCached = ifcImage.IsCached
}
```

### See Also

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

