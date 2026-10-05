---
title: "MeshPrimitiveDracoMesh Class"
linktitle: "MeshPrimitiveDracoMesh"
articleTitle: "MeshPrimitiveDracoMesh"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.MeshPrimitiveDracoMesh class. Geometry to be rendered with the given material."
type: docs
weight: 380
url: "/net/aspose.cad.fileformats.glb/meshprimitivedracomesh/"
keywords: "MeshPrimitiveDracoMesh, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## MeshPrimitiveDracoMesh class

Geometry to be rendered with the given material.

```csharp
public sealed class MeshPrimitiveDracoMesh : ExtraProperties, IChildOf<Mesh>
```

## Properties

| Name | Description |
| --- | --- |
| [DrawPrimitiveType](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/drawprimitivetype/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Gets a collection of [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) instances. |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Gets or sets the extras content of this instance. |
| [IndexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/indexaccessor/) { get; set; } |  |
| [LogicalIndex](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/logicalindex/) { get; } | Gets the zero-based index of this `MeshPrimitiveDracoMesh` at [`Primitives`](../mesh/primitives/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/logicalparent/) { get; } | Gets the [`Mesh`](../mesh/) instance that owns this `MeshPrimitiveDracoMesh` instance. |
| [Material](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/material/) { get; set; } | Gets or sets the [`Material`](./material/) instance, or null. |
| [MorphTargetsCount](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/morphtargetscount/) { get; } |  |
| [VertexAccessors](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/vertexaccessors/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [GetBufferViews](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getbufferviews/)(bool, bool, bool) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getindexaccessor/)() |  |
| [GetIndices](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getindices/)() | Gets the raw list of indices of this primitive. |
| [GetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getmorphtargetaccessors/)(int) |  |
| [GetPointIndices](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getpointindices/)() | Decodes the raw indices and returns a list of indexed points. |
| [GetVertexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getvertexaccessor/)(string) |  |
| [GetVertexAccessorsByBuffer](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getvertexaccessorsbybuffer/)(BufferView) |  |
| [GetVertices](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getvertices/)(string) |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/setindexaccessor/)(Accessor) |  |
| [SetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/setmorphtargetaccessors/)(int, IReadOnlyDictionary&lt;string, Accessor&gt;) |  |
| [SetVertexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/setvertexaccessor/)(string, Accessor) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### See Also

* class [ExtraProperties](../extraproperties/)
* interface [IChildOf&lt;TParent&gt;](../../aspose.cad.fileformats.glb.collections/ichildof-1/)
* class [Mesh](../mesh/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

