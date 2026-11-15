---
title: "Skin Класс"
linktitle: "Skin"
articleTitle: "Skin"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Skin класс. Суставы и матрицы, определяющие скин."
type: docs
weight: 480
url: "/net/aspose.cad.fileformats.glb/skin/"
keywords: "Skin, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Skin class

Суставы и матрицы, определяющие скин.

```csharp
public sealed class Skin : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [JointsCount](../../aspose.cad.fileformats.glb/skin/jointscount/) { get; } | Получает количество сочленений |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Skeleton](../../aspose.cad.fileformats.glb/skin/skeleton/) { get; set; } | Получает или задает Skeleton [`Node`](../node/), который представляет корень иерархии сочленений. |
| [VisualParents](../../aspose.cad.fileformats.glb/skin/visualparents/) { get; } | Получает коллекцию экземпляров [`Node`](../node/), используя этот `Skin`. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindJoints](../../aspose.cad.fileformats.glb/skin/bindjoints/#bindjoints)(params Node[]) |  |
| [BindJoints](../../aspose.cad.fileformats.glb/skin/bindjoints/#bindjoints_1)(Matrix4x4, params Node[]) | Привязывает арматуру кости [`Node`](../node/) к соответствующей skinned mesh. |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetInverseBindMatricesAccessor](../../aspose.cad.fileformats.glb/skin/getinversebindmatricesaccessor/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

