---
title: "SceneInstance 类"
linktitle: "SceneInstance"
articleTitle: "SceneInstance"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Runtime.SceneInstance 类。表示 SceneTemplate 的特定且独立的状态。"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/"
keywords: "SceneInstance, Aspose.CAD.FileFormats.GLB.Runtime, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneInstance class

表示 `SceneTemplate` 的特定且独立的状态。

```csharp
public sealed class SceneInstance : IReadOnlyList<DrawableInstance>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Armature](../../aspose.cad.fileformats.glb.runtime/sceneinstance/armature/) { get; } |  |
| [Count](../../aspose.cad.fileformats.glb.runtime/sceneinstance/count/) { get; } |  |
| [Item](../../aspose.cad.fileformats.glb.runtime/sceneinstance/item/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetDrawableInstance](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/)(int) | 获取一个 [`DrawableInstance`](../drawableinstance/) 对象，其：- Name 是此可绘制实例的名称。最初，它是 [`Node`](../../aspose.cad.fileformats.glb/node/) 的名称。- MeshIndex 是 [`LogicalMeshes`](../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/) 中 [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) 的逻辑索引。- Transform 是一个 `IGeometryTransform`，可用于将 [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) 转换到世界空间。 |
| [GetEnumerator](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getenumerator/)() |  |

### 另请参阅

* struct [DrawableInstance](../drawableinstance/)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../)

