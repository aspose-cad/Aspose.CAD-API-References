---
title: "ArmatureInstance 类"
linktitle: "ArmatureInstance"
articleTitle: "ArmatureInstance"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Runtime.ArmatureInstance 类。表示一组骨骼的变换状态。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.runtime/armatureinstance/"
keywords: "ArmatureInstance, Aspose.CAD.FileFormats.GLB.Runtime, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ArmatureInstance class

表示一组骨骼的变换状态。

```csharp
public class ArmatureInstance
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimationTracks](../../aspose.cad.fileformats.glb.runtime/armatureinstance/animationtracks/) { get; } | 获取此实例的动画轨道总数。 |
| [LogicalNodes](../../aspose.cad.fileformats.glb.runtime/armatureinstance/logicalnodes/) { get; } | 获取此骨架的所有节点的扁平化集合。 |
| [VisualNodes](../../aspose.cad.fileformats.glb.runtime/armatureinstance/visualnodes/) { get; } | 获取此 [`SceneInstance`](../sceneinstance/) 使用的所有 [`NodeInstance`](../nodeinstance/) 根节点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetAnimationFrame](../../aspose.cad.fileformats.glb.runtime/armatureinstance/setanimationframe/)(int, float, bool) | 从动画帧设置骨骼的变换。 |
| [SetLocalMatrix](../../aspose.cad.fileformats.glb.runtime/armatureinstance/setlocalmatrix/)(string, Matrix4x4) | 设置骨骼的矩阵。 |
| [SetModelMatrix](../../aspose.cad.fileformats.glb.runtime/armatureinstance/setmodelmatrix/)(string, Matrix4x4) | 设置骨骼的矩阵。 |
| [SetPoseTransforms](../../aspose.cad.fileformats.glb.runtime/armatureinstance/setposetransforms/)() | 将骨骼的变换重置为默认位置。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../)

