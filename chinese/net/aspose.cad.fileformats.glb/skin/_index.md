---
title: "Skin 类"
linktitle: "Skin"
articleTitle: "Skin"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Skin 类。定义皮肤的关节和矩阵。"
type: docs
weight: 480
url: "/net/aspose.cad.fileformats.glb/skin/"
keywords: "Skin, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Skin class

定义皮肤的关节和矩阵。

```csharp
public sealed class Skin : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [JointsCount](../../aspose.cad.fileformats.glb/skin/jointscount/) { get; } | 获取关节的数量 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Skeleton](../../aspose.cad.fileformats.glb/skin/skeleton/) { get; set; } | 获取或设置 Skeleton [`Node`](../node/)，它表示关节层次结构的根。 |
| [VisualParents](../../aspose.cad.fileformats.glb/skin/visualparents/) { get; } | 获取使用此 `Skin` 的一组 [`Node`](../node/) 实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindJoints](../../aspose.cad.fileformats.glb/skin/bindjoints/#bindjoints)(params Node[]) |  |
| [BindJoints](../../aspose.cad.fileformats.glb/skin/bindjoints/#bindjoints_1)(Matrix4x4, params Node[]) | 将 [`Node`](../node/) 的骨骼骨架绑定到关联的蒙皮网格。 |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetInverseBindMatricesAccessor](../../aspose.cad.fileformats.glb/skin/getinversebindmatricesaccessor/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

