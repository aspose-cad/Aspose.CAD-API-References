---
title: "SceneInstance.GetDrawableInstance"
linktitle: "GetDrawableInstance"
articleTitle: "GetDrawableInstance"
second_title: "Aspose.CAD for .NET API 参考"
description: "SceneInstance 方法。获取一个 DrawableInstance 对象，其中：- Name 是此 drawable 实例的名称。最初，它是 Node 的名称。- MeshIndex i..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/"
product_version: "26.9"
---
## SceneInstance.GetDrawableInstance method

获取一个 [`DrawableInstance`](../../drawableinstance/) 对象，其中：
 - Name is the name of this drawable instance. Originally, it was the name of [`Node`](../../../aspose.cad.fileformats.glb/node/).
 - MeshIndex is the logical Index of a [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) in [`LogicalMeshes`](../../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/).
 - Transform is an `IGeometryTransform` that can be used to transform the [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) into world space.

```csharp
public DrawableInstance GetDrawableInstance(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | drawable 引用的索引，范围从 0 到 DrawableInstancesCount |

### 返回值

[`DrawableInstance`](../../drawableinstance/) object.

### 另请参阅

* struct [DrawableInstance](../../drawableinstance/)
* class [SceneInstance](../)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../../)

