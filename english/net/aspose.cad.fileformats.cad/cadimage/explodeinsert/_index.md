---
title: "CadImage.ExplodeInsert"
linktitle: "ExplodeInsert"
articleTitle: "ExplodeInsert"
second_title: "Aspose.CAD for .NET API Reference"
description: "CadImage method. Explodes an insert and puts its contained entities in place of that insert, also returning these entities"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.cad/cadimage/explodeinsert/"
product_version: "26.9"
---
## CadImage.ExplodeInsert method

Explodes an insert and puts its contained entities in place of that insert, also returning these entities

```csharp
public CadEntityBase[] ExplodeInsert(string objectID, bool recurse)
```

| Parameter | Type | Description |
| --- | --- | --- |
| objectID | String | Insert handle or, in older formats number, [`Id`](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) |
| recurse | Boolean | Whether to explode child inserts recursively |

### Return Value

All entities from exploded insert, null if not found or not explodable

### See Also

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [CadImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

