---
title: "Node 类"
linktitle: "Node"
articleTitle: "Node"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Node 类。节点层次结构中的一个节点。当节点包含 `skin` 时，所有 `mesh.primitives` 必须包含 `JOINTS_0` 和 `WEIGHT...`"
type: docs
weight: 390
url: "/net/aspose.cad.fileformats.glb/node/"
keywords: "Node, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Node class

节点层次结构中的一个节点。
当节点包含 `skin` 时，所有 `mesh.primitives` **MUST** 包含 `JOINTS_0` 和 `WEIGHTS_0` 属性。
一个节点 **MAY** 拥有 `matrix` 或任意组合的 `translation`/`rotation`/`scale`（TRS）属性。TRS 属性会被转换为矩阵，并按照 `T * R * S` 顺序后乘以组成变换矩阵；首先对顶点应用缩放，其次是旋转，最后是平移。如果未提供任何属性，变换为单位矩阵。当节点被用于动画（由 animation.channel.target 引用）时，`matrix` **MUST NOT** 出现。

```csharp
public sealed class Node : LogicalChildOfRoot, IVisualNodeContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Camera](../../aspose.cad.fileformats.glb/node/camera/) { get; set; } | 获取或设置此 `Node` 的 [`Camera`](../camera/)。 |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [IsSkinJoint](../../aspose.cad.fileformats.glb/node/isskinjoint/) { get; } | 获取一个值，指示此节点是否在 [`Skin`](./skin/) 中用作骨骼关节。 |
| [IsSkinSkeleton](../../aspose.cad.fileformats.glb/node/isskinskeleton/) { get; } | 获取一个值，指示此节点是否在 [`Skin`](./skin/) 中用作骨架节点。 |
| [IsTransformAnimated](../../aspose.cad.fileformats.glb/node/istransformanimated/) { get; } | 获取一个值，指示此变换是否受到任何动画的影响。 |
| [LocalMatrix](../../aspose.cad.fileformats.glb/node/localmatrix/) { get; set; } | 获取或设置此 `Node` 的本地变换 Matrix4x4。 |
| [LocalTransform](../../aspose.cad.fileformats.glb/node/localtransform/) { get; set; } | 获取或设置此 `Node` 的本地缩放、旋转和位移。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Mesh](../../aspose.cad.fileformats.glb/node/mesh/) { get; set; } | 获取或设置此 `Node` 的 [`Mesh`](../mesh/)。 |
| [MorphWeights](../../aspose.cad.fileformats.glb/node/morphweights/) { get; } | 获取此 `Node` 的形变权重。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [PunctualLight](../../aspose.cad.fileformats.glb/node/punctuallight/) { get; set; } | 获取或设置此 `Node` 的 [`PunctualLight`](../punctuallight/)。 |
| [Skin](../../aspose.cad.fileformats.glb/node/skin/) { get; set; } | 获取或设置此 `Node` 的 [`Skin`](../skin/)。 |
| [VisualChildren](../../aspose.cad.fileformats.glb/node/visualchildren/) { get; } | 获取此 `Node` 中包含的可视子 `Node` 实例。 |
| [VisualParent](../../aspose.cad.fileformats.glb/node/visualparent/) { get; } | 获取包含此 `Node` 的可视父 `Node` 实例。 |
| [VisualRoot](../../aspose.cad.fileformats.glb/node/visualroot/) { get; } | 获取包含此 `Node` 的可视根 `Node` 实例。 |
| [VisualScenes](../../aspose.cad.fileformats.glb/node/visualscenes/) { get; } | 获取引用此 `Node` 的 [`Scene`](../scene/) 实例集合。 |
| [WorldMatrix](../../aspose.cad.fileformats.glb/node/worldmatrix/) { get; set; } | 获取或设置此 `Node` 的世界 Matrix4x4。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateNode](../../aspose.cad.fileformats.glb/node/createnode/)(string) | 创建一个新的 `Node` 实例，将其添加到 [`LogicalNodes`](../glbdata/logicalnodes/) 并在当前图中将其引用为子节点。 |
| static [FindNodesUsingMesh](../../aspose.cad.fileformats.glb/node/findnodesusingmesh/)(Mesh) | 获取使用 *mesh* 的 `Node` 实例集合。 |
| static [FindNodesUsingSkin](../../aspose.cad.fileformats.glb/node/findnodesusingskin/)(Skin) | 获取使用 *skin* 的 `Node` 实例集合。 |
| static [Flatten](../../aspose.cad.fileformats.glb/node/flatten/)(IVisualNodeContainer) | 返回可视层次结构中所有 `Node` 实例的扁平化列表。 |
| [GetCurveSamplers](../../aspose.cad.fileformats.glb/node/getcurvesamplers/)(Animation) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetGpuInstancing](../../aspose.cad.fileformats.glb/node/getgpuinstancing/)() |  |
| [GetLocalTransform](../../aspose.cad.fileformats.glb/node/getlocaltransform/)(Animation, float) | 获取此节点在给定动画的特定时间点的本地变换。 |
| [GetMorphWeights](../../aspose.cad.fileformats.glb/node/getmorphweights/)() |  |
| [GetWorldMatrix](../../aspose.cad.fileformats.glb/node/getworldmatrix/)(Animation, float) | 获取此节点在给定动画的特定时间点的世界矩阵。 |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [RemoveGpuInstancing](../../aspose.cad.fileformats.glb/node/removegpuinstancing/)() |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/node/setmorphweights/)(SparseWeight8) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |
| [UseGpuInstancing](../../aspose.cad.fileformats.glb/node/usegpuinstancing/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* interface [IVisualNodeContainer](../ivisualnodecontainer/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

