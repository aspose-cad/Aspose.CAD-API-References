---
title: "Класс LogicalChildOfRoot"
linktitle: "LogicalChildOfRoot"
articleTitle: "LogicalChildOfRoot"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.LogicalChildOfRoot класс. Все элементы gltf, хранящиеся в ModelRoot, должны наследоваться от этого класса."
type: docs
weight: 320
url: "/net/aspose.cad.fileformats.glb/logicalchildofroot/"
keywords: "LogicalChildOfRoot, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## LogicalChildOfRoot class

Все элементы gltf, хранящиеся в ModelRoot, должны наследоваться от этого класса.

```csharp
public abstract class LogicalChildOfRoot : ExtraProperties, IChildOf<GlbData>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| static [RenameLogicalElements&lt;T&gt;](../../aspose.cad.fileformats.glb/logicalchildofroot/renamelogicalelements/)(IEnumerable&lt;T&gt;, string) | Переименовывает все безымянные и дублирующие элементы в коллекции, чтобы у всех элементов было уникальное корректное имя. |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [ExtraProperties](../extraproperties/)
* interface [IChildOf&lt;TParent&gt;](../../aspose.cad.fileformats.glb.collections/ichildof-1/)
* class [GlbData](../glbdata/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

