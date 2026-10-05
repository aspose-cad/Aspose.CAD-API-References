---
title: "SceneInstance.GetDrawableInstance"
linktitle: "GetDrawableInstance"
articleTitle: "GetDrawableInstance"
second_title: "Aspose.CAD for .NET API Reference"
description: "SceneInstance method. Gets a DrawableInstance object, where: - Name is the name of this drawable instance. Originally, it was the name of Node. - MeshIndex i..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/"
product_version: "26.9"
---
## SceneInstance.GetDrawableInstance method

Gets a [`DrawableInstance`](../../drawableinstance/) object, where:
 - Name is the name of this drawable instance. Originally, it was the name of [`Node`](../../../aspose.cad.fileformats.glb/node/).
 - MeshIndex is the logical Index of a [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) in [`LogicalMeshes`](../../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/).
 - Transform is an `IGeometryTransform` that can be used to transform the [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) into world space.

```csharp
public DrawableInstance GetDrawableInstance(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index of the drawable reference, from 0 to DrawableInstancesCount |

### Return Value

[`DrawableInstance`](../../drawableinstance/) object.

### See Also

* struct [DrawableInstance](../../drawableinstance/)
* class [SceneInstance](../)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../../)

