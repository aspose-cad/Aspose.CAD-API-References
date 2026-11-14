---
title: "Mesh 类"
linktitle: "Mesh"
articleTitle: "Mesh"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Mesh 类。用于渲染的一组基元。其全局变换由引用它的节点定义。"
type: docs
weight: 350
url: "/net/aspose.cad.fileformats.glb/mesh/"
keywords: "Mesh, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Mesh class

用于渲染的一组基元。
其全局变换由引用它的节点定义。

```csharp
public sealed class Mesh : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllPrimitivesHaveJoints](../../aspose.cad.fileformats.glb/mesh/allprimitiveshavejoints/) { get; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [MorphWeights](../../aspose.cad.fileformats.glb/mesh/morphweights/) { get; } |  |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Primitives](../../aspose.cad.fileformats.glb/mesh/primitives/) { get; } |  |
| [VisualParents](../../aspose.cad.fileformats.glb/mesh/visualparents/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreatePrimitive](../../aspose.cad.fileformats.glb/mesh/createprimitive/)() | 创建一个新的 [`MeshPrimitive`](../meshprimitive/) 实例并将其添加到当前 `Mesh`。 |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetMorphWeights](../../aspose.cad.fileformats.glb/mesh/getmorphweights/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/mesh/setmorphweights/#setmorphweights)(IReadOnlyList&lt;float&gt;) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/mesh/setmorphweights/#setmorphweights_1)(SparseWeight8) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

