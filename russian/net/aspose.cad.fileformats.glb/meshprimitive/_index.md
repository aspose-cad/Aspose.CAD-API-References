---
title: "Класс MeshPrimitive"
linktitle: "MeshPrimitive"
articleTitle: "MeshPrimitive"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.MeshPrimitive class. Геометрия, которая будет отрисована с заданным материалом."
type: docs
weight: 370
url: "/net/aspose.cad.fileformats.glb/meshprimitive/"
keywords: "MeshPrimitive, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## MeshPrimitive class

Геометрия, которая будет отрисована с указанным материалом.

```csharp
public sealed class MeshPrimitive : ExtraProperties, IChildOf<Mesh>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DrawPrimitiveType](../../aspose.cad.fileformats.glb/meshprimitive/drawprimitivetype/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [IndexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/indexaccessor/) { get; set; } |  |
| [LogicalIndex](../../aspose.cad.fileformats.glb/meshprimitive/logicalindex/) { get; } | Получает индекс, начинающийся с нуля, этого `MeshPrimitive` в [`Primitives`](../mesh/primitives/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/meshprimitive/logicalparent/) { get; } | Получает экземпляр [`Mesh`](../mesh/), которому принадлежит этот `MeshPrimitive`. |
| [Material](../../aspose.cad.fileformats.glb/meshprimitive/material/) { get; set; } | Получает или задает экземпляр [`Material`](./material/), или null. |
| [MorphTargetsCount](../../aspose.cad.fileformats.glb/meshprimitive/morphtargetscount/) { get; } |  |
| [VertexAccessors](../../aspose.cad.fileformats.glb/meshprimitive/vertexaccessors/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBufferViews](../../aspose.cad.fileformats.glb/meshprimitive/getbufferviews/)(bool, bool, bool) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetIndexAccessor](../../aspose.cad.fileformats.glb/meshprimitive/getindexaccessor/)() |  |
| [GetIndices](../../aspose.cad.fileformats.glb/meshprimitive/getindices/)() | Получает необработанный список индексов этого примитива. |
| [GetMorphTargetAccessors](../../aspose.cad.fileformats.glb/meshprimitive/getmorphtargetaccessors/)(int) |  |
| [GetPointIndices](../../aspose.cad.fileformats.glb/meshprimitive/getpointindices/)() | Декодирует необработанные индексы и возвращает список индексированных точек. |
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

### См. также

* class [ExtraProperties](../extraproperties/)
* interface [IChildOf&lt;TParent&gt;](../../aspose.cad.fileformats.glb.collections/ichildof-1/)
* class [Mesh](../mesh/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

