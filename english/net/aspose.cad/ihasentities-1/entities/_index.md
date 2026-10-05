---
title: "IHasEntities<T>.Entities"
linktitle: "Entities"
articleTitle: "Entities"
second_title: "Aspose.CAD for .NET API Reference"
description: "IHasEntities property. Gets all entities that exist on a drawing. Could be useful for walking through them and check its properties"
type: docs
weight: 20
url: "/net/aspose.cad/ihasentities-1/entities/"
product_version: "26.9"
---
## IHasEntities<T>.Entities property

Gets all entities that exist on a drawing.
 Could be useful for walking through them and check its properties

```csharp
public IEnumerable<T> Entities { get; }
```

### Property Value

A set of entity instances

## Examples

Gets entities set from a drawing.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var entities = ifcImage.Entities
}
```

### See Also

* interface [IHasEntities&lt;T&gt;](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

