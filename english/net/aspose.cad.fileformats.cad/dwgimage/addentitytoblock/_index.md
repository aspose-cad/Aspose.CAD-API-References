---
title: "DwgImage.AddEntityToBlock"
linktitle: "AddEntityToBlock"
articleTitle: "AddEntityToBlock"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwgImage method. Adds an entity to the specified block."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.cad/dwgimage/addentitytoblock/"
product_version: "26.9"
---
## DwgImage.AddEntityToBlock method

Adds an entity to the specified block.

```csharp
public void AddEntityToBlock(string blockName, CadEntityBase entity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| blockName | String | The name of the block. |
| entity | CadEntityBase | The entity to add. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown if *entity* is null. |
| ArgumentException | Thrown if the block does not exist, is a system block, or the entity is already associated with another block. |

### See Also

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

