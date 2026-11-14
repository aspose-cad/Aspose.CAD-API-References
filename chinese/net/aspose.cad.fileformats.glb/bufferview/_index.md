---
title: "BufferView 类"
linktitle: "BufferView"
articleTitle: "BufferView"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.BufferView 类。对缓冲区的视图，通常表示缓冲区的子集。"
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.glb/bufferview/"
keywords: "BufferView, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## BufferView class

对缓冲区的视图，通常表示缓冲区的子集。

```csharp
public sealed class BufferView : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ByteStride](../../aspose.cad.fileformats.glb/bufferview/bytestride/) { get; } | 获取连续元素起始之间的字节数，或为零。 |
| [Content](../../aspose.cad.fileformats.glb/bufferview/content/) { get; } | 获取此 `BufferView` 定义的实际字节 |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [IsDataBuffer](../../aspose.cad.fileformats.glb/bufferview/isdatabuffer/) { get; } | 获取一个值，指示此 `BufferView` 是否定义了通用数据缓冲区。 |
| [IsIndexBuffer](../../aspose.cad.fileformats.glb/bufferview/isindexbuffer/) { get; } | 获取一个值，指示此 `BufferView` 是否定义了 GPU 就绪的索引缓冲区。 |
| [IsVertexBuffer](../../aspose.cad.fileformats.glb/bufferview/isvertexbuffer/) { get; } | 获取一个值，指示此 `BufferView` 是否定义了 GPU 就绪的顶点缓冲区。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindAccessors](../../aspose.cad.fileformats.glb/bufferview/findaccessors/)() | 查找所有使用此 BufferView 的访问器 |
| [FindImages](../../aspose.cad.fileformats.glb/bufferview/findimages/)() |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [IsInterleaved](../../aspose.cad.fileformats.glb/bufferview/isinterleaved/)(IEnumerable&lt;Accessor&gt;) | 检查 *accessors* 是否以交错方式使用此缓冲区 |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

