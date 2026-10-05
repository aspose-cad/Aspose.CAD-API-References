---
title: "SceneInstance Class"
linktitle: "SceneInstance"
articleTitle: "SceneInstance"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Runtime.SceneInstance class. Represents a specific and independent state of a SceneTemplate."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/"
keywords: "SceneInstance, Aspose.CAD.FileFormats.GLB.Runtime, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneInstance class

Represents a specific and independent state of a `SceneTemplate`.

```csharp
public sealed class SceneInstance : IReadOnlyList<DrawableInstance>
```

## Properties

| Name | Description |
| --- | --- |
| [Armature](../../aspose.cad.fileformats.glb.runtime/sceneinstance/armature/) { get; } |  |
| [Count](../../aspose.cad.fileformats.glb.runtime/sceneinstance/count/) { get; } |  |
| [Item](../../aspose.cad.fileformats.glb.runtime/sceneinstance/item/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetDrawableInstance](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/)(int) | Gets a [`DrawableInstance`](../drawableinstance/) object, where: - Name is the name of this drawable instance. Originally, it was the name of [`Node`](../../aspose.cad.fileformats.glb/node/). - MeshIndex is the logical Index of a [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) in [`LogicalMeshes`](../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/). - Transform is an `IGeometryTransform` that can be used to transform the [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) into world space. |
| [GetEnumerator](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getenumerator/)() |  |

### See Also

* struct [DrawableInstance](../drawableinstance/)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../)

