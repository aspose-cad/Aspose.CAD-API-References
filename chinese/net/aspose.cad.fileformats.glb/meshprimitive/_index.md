---
title: "MeshPrimitive 类"
linktitle: "MeshPrimitive"
articleTitle: "MeshPrimitive"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.MeshPrimitive class. 使用给定材质渲染的几何体。"
type: docs
weight: 370
url: "/net/aspose.cad.fileformats.glb/meshprimitive/"
keywords: "MeshPrimitive, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## MeshPrimitive class

几何体将使用给定的材质进行渲染。

```csharp
public sealed class MeshPrimitive : ExtraProperties, IChildOf<Mesh>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DrawPrimitiveType](../../aspose.cad.fileformats.glb/meshprimitive/drawprimitivetype/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [IndexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/indexaccessor/) { get; set; } |  |
| [LogicalIndex](../../aspose.cad.fileformats.glb/meshprimitive/logicalindex/) { get; } | 获取此 `MeshPrimitive` 在 [`Primitives`](../mesh/primitives/) 中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/meshprimitive/logicalparent/) { get; } | 获取拥有此 `MeshPrimitive` 实例的 [`Mesh`](../mesh/) 实例。 |
| [Material](../../aspose.cad.fileformats.glb/meshprimitive/material/) { get; set; } | 获取或设置 [`Material`](./material/) 实例，或为 null。 |
| [MorphTargetsCount](../../aspose.cad.fileformats.glb/meshprimitive/morphtargetscount/) { get; } |  |
| [VertexAccessors](../../aspose.cad.fileformats.glb/meshprimitive/vertexaccessors/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBufferViews](../../aspose.cad.fileformats.glb/meshprimitive/getbufferviews/)(bool, bool, bool) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/getindexaccessor/)() |  |
| [GetIndices](../../aspose.cad.fileformats.glb/meshprimitive/getindices/)() | 获取此基元的原始索引列表。 |
| [GetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitive/getmorphtargetaccessors/)(int) |  |
| [GetPointIndices](../../aspose.cad.fileformats.glb/meshprimitive/getpointindices/)() | 解码原始索引并返回索引点列表。 |
| [GetVertexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/getvertexaccessor/)(string) |  |
| [GetVertexAccessorsByBuffer](../../aspose.cad.fileformats.glb/meshprimitive/getvertexaccessorsbybuffer/)(BufferView) |  |
| [GetVertices](../../aspose.cad.fileformats.glb/meshprimitive/getvertices/)(string) |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/setindexaccessor/)(Accessor) |  |
| [SetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitive/setmorphtargetaccessors/)(int, IReadOnlyDictionary&lt;string, Accessor&gt;) |  |
| [SetVertexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/setvertexaccessor/)(string, Accessor) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [ExtraProperties](../extraproperties/)
* interface [IChildOf&lt;TParent&gt;](../../aspose.cad.fileformats.glb.collections/ichildof-1/)
* class [Mesh](../mesh/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

