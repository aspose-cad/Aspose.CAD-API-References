---
title: "MeshPrimitiveDracoMesh класс"
linktitle: "MeshPrimitiveDracoMesh"
articleTitle: "MeshPrimitiveDracoMesh"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.MeshPrimitiveDracoMesh class. Геометрия, которая будет отрисована с заданным материалом."
type: docs
weight: 380
url: "/net/aspose.cad.fileformats.glb/meshprimitivedracomesh/"
keywords: "MeshPrimitiveDracoMesh, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## MeshPrimitiveDracoMesh class

Геометрия, которая будет отрисована с указанным материалом.

```csharp
public sealed class MeshPrimitiveDracoMesh : ExtraProperties, IChildOf<Mesh>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DrawPrimitiveType](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/drawprimitivetype/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [IndexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/indexaccessor/) { get; set; } |  |
| [LogicalIndex](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/logicalindex/) { get; } | Возвращает нулевой индекс этого `MeshPrimitiveDracoMesh` в [`Primitives`](../mesh/primitives/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/logicalparent/) { get; } | Возвращает экземпляр [`Mesh`](../mesh/), которому принадлежит этот `MeshPrimitiveDracoMesh`. |
| [Material](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/material/) { get; set; } | Получает или задает экземпляр [`Material`](./material/), или null. |
| [MorphTargetsCount](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/morphtargetscount/) { get; } |  |
| [VertexAccessors](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/vertexaccessors/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBufferViews](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getbufferviews/)(bool, bool, bool) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getindexaccessor/)() |  |
| [GetIndices](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getindices/)() | Получает необработанный список индексов этого примитива. |
| [GetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getmorphtargetaccessors/)(int) |  |
| [GetPointIndices](../../aspose.cad.fileformats.glb/meshprimitivedracomesh/getpointindices/)() | Декодирует необработанные индексы и возвращает список индексированных точек. |
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

### См. также

* class [ExtraProperties](../extraproperties/)
* interface [IChildOf&lt;TParent&gt;](../../aspose.cad.fileformats.glb.collections/ichildof-1/)
* class [Mesh](../mesh/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

