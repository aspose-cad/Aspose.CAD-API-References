---
title: "Класс Mesh"
linktitle: "Mesh"
articleTitle: "Mesh"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Mesh class. Набор примитивов для рендеринга. Его глобальное преобразование определяется узлом, который ссылается на него."
type: docs
weight: 350
url: "/net/aspose.cad.fileformats.glb/mesh/"
keywords: "Mesh, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Mesh class

Набор примитивов для рендеринга.
Его глобальное преобразование определяется узлом, который ссылается на него.

```csharp
public sealed class Mesh : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AllPrimitivesHaveJoints](../../aspose.cad.fileformats.glb/mesh/allprimitiveshavejoints/) { get; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [MorphWeights](../../aspose.cad.fileformats.glb/mesh/morphweights/) { get; } |  |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Primitives](../../aspose.cad.fileformats.glb/mesh/primitives/) { get; } |  |
| [VisualParents](../../aspose.cad.fileformats.glb/mesh/visualparents/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [CreatePrimitive](../../aspose.cad.fileformats.glb/mesh/createprimitive/)() | Создаёт новый экземпляр [`MeshPrimitive`](../meshprimitive/) и добавляет его в текущий `Mesh`. |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetMorphWeights](../../aspose.cad.fileformats.glb/mesh/getmorphweights/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/mesh/setmorphweights/#setmorphweights)(IReadOnlyList&lt;float&gt;) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/mesh/setmorphweights/#setmorphweights_1)(SparseWeight8) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

