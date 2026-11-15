---
title: "BufferView Класс"
linktitle: "BufferView"
articleTitle: "BufferView"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.BufferView класс. Представление буфера, обычно представляющее его подмножество."
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.glb/bufferview/"
keywords: "BufferView, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## BufferView class

Представление буфера, обычно представляющее подмножество буфера.

```csharp
public sealed class BufferView : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteStride](../../aspose.cad.fileformats.glb/bufferview/bytestride/) { get; } | Получает количество байтов между начала последовательных элементов, или Zero. |
| [Content](../../aspose.cad.fileformats.glb/bufferview/content/) { get; } | Получает фактические байты, определённые этим `BufferView` |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [IsDataBuffer](../../aspose.cad.fileformats.glb/bufferview/isdatabuffer/) { get; } | Получает значение, указывающее, определяет ли этот `BufferView` буфер данных общего назначения. |
| [IsIndexBuffer](../../aspose.cad.fileformats.glb/bufferview/isindexbuffer/) { get; } | Получает значение, указывающее, определяет ли этот `BufferView` индексный буфер, готовый к работе с GPU. |
| [IsVertexBuffer](../../aspose.cad.fileformats.glb/bufferview/isvertexbuffer/) { get; } | Получает значение, указывающее, определяет ли этот `BufferView` вершинный буфер, готовый к работе с GPU. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindAccessors](../../aspose.cad.fileformats.glb/bufferview/findaccessors/)() | Находит все аксессоры, использующие этот BufferView |
| [FindImages](../../aspose.cad.fileformats.glb/bufferview/findimages/)() |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [IsInterleaved](../../aspose.cad.fileformats.glb/bufferview/isinterleaved/)(IEnumerable&lt;Accessor&gt;) | Проверяет, используют ли *accessors* этот буфер в чередующейся организации |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

