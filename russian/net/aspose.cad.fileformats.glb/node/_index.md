---
title: "Класс Node"
linktitle: "Node"
articleTitle: "Node"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.Node. Узел в иерархии узлов. Когда узел содержит `skin`, все `mesh.primitives` MUST содержат `JOINTS_0` и `WEIGHT..."
type: docs
weight: 390
url: "/net/aspose.cad.fileformats.glb/node/"
keywords: "Node, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Node class

Узел в иерархии узлов.
Когда узел содержит `skin`, все `mesh.primitives` **MUST** содержат атрибуты `JOINTS_0` и `WEIGHTS_0`.
Узел **MAY** может иметь либо `matrix`, либо любую комбинацию свойств `translation`/`rotation`/`scale` (TRS). Свойства TRS преобразуются в матрицы и постмножаются в порядке `T * R * S` для составления матрицы преобразования; сначала к вершинам применяется масштаб, затем вращение, а затем трансляция. Если ни одно не указано, преобразование является единичным. Когда узел используется для анимации (ссылка из animation.channel.target), `matrix` **MUST NOT** должно присутствовать.

```csharp
public sealed class Node : LogicalChildOfRoot, IVisualNodeContainer
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Camera](../../aspose.cad.fileformats.glb/node/camera/) { get; set; } | Получает или задает [`Camera`](../camera/) этого `Node`. |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [IsSkinJoint](../../aspose.cad.fileformats.glb/node/isskinjoint/) { get; } | Возвращает значение, указывающее, используется ли этот узел как костный сустав в [`Skin`](./skin/). |
| [IsSkinSkeleton](../../aspose.cad.fileformats.glb/node/isskinskeleton/) { get; } | Возвращает значение, указывающее, используется ли этот узел как скелетный узел в [`Skin`](./skin/). |
| [IsTransformAnimated](../../aspose.cad.fileformats.glb/node/istransformanimated/) { get; } | Возвращает значение, указывающее, влияет ли какая-либо анимация на это преобразование. |
| [LocalMatrix](../../aspose.cad.fileformats.glb/node/localmatrix/) { get; set; } | Получает или задает локальное преобразование Matrix4x4 этого `Node`. |
| [LocalTransform](../../aspose.cad.fileformats.glb/node/localtransform/) { get; set; } | Получает или задает локальные Scale, Rotation и Translation этого `Node`. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Mesh](../../aspose.cad.fileformats.glb/node/mesh/) { get; set; } | Получает или задает [`Mesh`](../mesh/) этого `Node`. |
| [MorphWeights](../../aspose.cad.fileformats.glb/node/morphweights/) { get; } | Получает Morph Weights этого `Node`. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [PunctualLight](../../aspose.cad.fileformats.glb/node/punctuallight/) { get; set; } | Получает или задает [`PunctualLight`](../punctuallight/) этого `Node`. |
| [Skin](../../aspose.cad.fileformats.glb/node/skin/) { get; set; } | Получает или задает [`Skin`](../skin/) этого `Node`. |
| [VisualChildren](../../aspose.cad.fileformats.glb/node/visualchildren/) { get; } | Получает визуальные дочерние экземпляры `Node`, содержащиеся в этом `Node`. |
| [VisualParent](../../aspose.cad.fileformats.glb/node/visualparent/) { get; } | Получает визуальный родительский экземпляр `Node`, содержащий этот `Node`. |
| [VisualRoot](../../aspose.cad.fileformats.glb/node/visualroot/) { get; } | Получает визуальный корневой экземпляр `Node`, содержащий этот `Node`. |
| [VisualScenes](../../aspose.cad.fileformats.glb/node/visualscenes/) { get; } | Получает коллекцию экземпляров [`Scene`](../scene/), ссылающихся на этот `Node`. |
| [WorldMatrix](../../aspose.cad.fileformats.glb/node/worldmatrix/) { get; set; } | Получает или задает мировую матрицу Matrix4x4 этого `Node`. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateNode](../../aspose.cad.fileformats.glb/node/createnode/)(string) | Создает новый экземпляр `Node`, добавляет его в [`LogicalNodes`](../glbdata/logicalnodes/) и ссылается на него как на дочерний в текущем графе. |
| static [FindNodesUsingMesh](../../aspose.cad.fileformats.glb/node/findnodesusingmesh/)(Mesh) | Получает коллекцию экземпляров `Node`, использующих *mesh*. |
| static [FindNodesUsingSkin](../../aspose.cad.fileformats.glb/node/findnodesusingskin/)(Skin) | Получает коллекцию экземпляров `Node`, использующих *skin*. |
| static [Flatten](../../aspose.cad.fileformats.glb/node/flatten/)(IVisualNodeContainer) | Возвращает все экземпляры `Node` визуальной иерархии в виде плоского списка. |
| [GetCurveSamplers](../../aspose.cad.fileformats.glb/node/getcurvesamplers/)(Animation) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetGpuInstancing](../../aspose.cad.fileformats.glb/node/getgpuinstancing/)() |  |
| [GetLocalTransform](../../aspose.cad.fileformats.glb/node/getlocaltransform/)(Animation, float) | Получает локальное преобразование этого node в заданной анимации в указанное время. |
| [GetMorphWeights](../../aspose.cad.fileformats.glb/node/getmorphweights/)() |  |
| [GetWorldMatrix](../../aspose.cad.fileformats.glb/node/getworldmatrix/)(Animation, float) | Получает мировую матрицу этого node в заданной анимации в указанное время. |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [RemoveGpuInstancing](../../aspose.cad.fileformats.glb/node/removegpuinstancing/)() |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetMorphWeights](../../aspose.cad.fileformats.glb/node/setmorphweights/)(SparseWeight8) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |
| [UseGpuInstancing](../../aspose.cad.fileformats.glb/node/usegpuinstancing/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* interface [IVisualNodeContainer](../ivisualnodecontainer/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

