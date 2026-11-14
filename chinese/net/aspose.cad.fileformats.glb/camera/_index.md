---
title: "Camera 类"
linktitle: "Camera"
articleTitle: "Camera"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Camera 类。相机的投影。节点 **MAY** 引用相机以应用变换，将相机放置在场景中。"
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.glb/camera/"
keywords: "Camera, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Camera class

相机的投影。
节点 **MAY** 引用相机以应用变换，将相机放置在场景中。

```csharp
public sealed class Camera : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Matrix](../../aspose.cad.fileformats.glb/camera/matrix/) { get; } | 获取当前 [`Settings`](./settings/) 的投影矩阵 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Settings](../../aspose.cad.fileformats.glb/camera/settings/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetOrthographicMode](../../aspose.cad.fileformats.glb/camera/setorthographicmode/)(float, float, float, float) | 配置此 `Camera` 使用正交投影。 |
| [SetPerspectiveMode](../../aspose.cad.fileformats.glb/camera/setperspectivemode/)(float?, float, float, float) | 配置此 `Camera` 使用透视投影。 |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

