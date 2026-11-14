---
title: "SceneBuilder.ApplyBasisTransform"
linktitle: "ApplyBasisTransform"
articleTitle: "ApplyBasisTransform"
second_title: "Aspose.CAD for .NET API 参考"
description: "SceneBuilder 方法。对该 SceneBuilder 应用变换。"
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.glb.scenes/scenebuilder/applybasistransform/"
product_version: "26.9"
---
## SceneBuilder.ApplyBasisTransform method

对该 [`SceneBuilder`](../) 应用变换。

```csharp
public void ApplyBasisTransform(Matrix4x4 basisTransform, string basisNodeName = "BasisTransform")
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| basisTransform | Matrix4x4 | 要应用的变换。 |
| basisNodeName | String | 虚拟根节点的名称。 |

## 备注

在某些情况下，无法应用
 *basisTransform* to the nodes in the scene.

在这些情况下，会创建一个虚拟节点，并且这些
节点会成为该虚拟节点的子节点。
 
 

此方法用于切换坐标轴（Z-UP 或 Y-UP）以及左右手坐标系模式。
 
 

应在场景完全创建后调用此方法。

### 另请参阅

* class [SceneBuilder](../)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../../)

