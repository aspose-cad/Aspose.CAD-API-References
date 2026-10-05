---
title: "NodeBuilder.LocalMatrix"
linktitle: "LocalMatrix"
articleTitle: "LocalMatrix"
second_title: "Aspose.CAD for .NET API Reference"
description: "NodeBuilder property. Gets or sets the local transform Matrix4x4 of this NodeBuilder."
type: docs
weight: 360
url: "/net/aspose.cad.fileformats.glb.scenes/nodebuilder/localmatrix/"
product_version: "26.9"
---
## NodeBuilder.LocalMatrix property

Gets or sets the local transform `Matrix4x4` of this [`NodeBuilder`](../).

```csharp
public Matrix4x4 LocalMatrix { get; set; }
```

## Remarks

When setting the value, If there's no animations currently attached to this node,

 the transform is stored as a matrix. Otherwise, it's decomposed to a SRT chain.

### See Also

* class [NodeBuilder](../)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../../)

