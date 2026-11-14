---
title: "Animation 类"
linktitle: "动画"
articleTitle: "动画"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Animation 类。关键帧动画。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb/animation/"
keywords: "Animation, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Animation class

关键帧动画。

```csharp
public sealed class Animation : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Channels](../../aspose.cad.fileformats.glb/animation/channels/) { get; } |  |
| [Duration](../../aspose.cad.fileformats.glb/animation/duration/) { get; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateMorphChannel](../../aspose.cad.fileformats.glb/animation/createmorphchannel/#createmorphchannel)(Node, IReadOnlyDictionary&lt;float, SparseWeight8&gt;, int, bool) |  |
| [CreateMorphChannel&lt;TWeights&gt;](../../aspose.cad.fileformats.glb/animation/createmorphchannel/#createmorphchannel_1)(Node, IReadOnlyDictionary&lt;float, TWeights&gt;, int, bool) |  |
| [CreateRotationChannel](../../aspose.cad.fileformats.glb/animation/createrotationchannel/)(Node, IReadOnlyDictionary&lt;float, Quaternion&gt;, bool) |  |
| [CreateScaleChannel](../../aspose.cad.fileformats.glb/animation/createscalechannel/)(Node, IReadOnlyDictionary&lt;float, Vector3&gt;, bool) |  |
| [CreateTranslationChannel](../../aspose.cad.fileformats.glb/animation/createtranslationchannel/)(Node, IReadOnlyDictionary&lt;float, Vector3&gt;, bool) |  |
| [FindChannels](../../aspose.cad.fileformats.glb/animation/findchannels/)(Node) |  |
| [FindMorphChannel](../../aspose.cad.fileformats.glb/animation/findmorphchannel/)(Node) |  |
| [FindRotationChannel](../../aspose.cad.fileformats.glb/animation/findrotationchannel/)(Node) |  |
| [FindScaleChannel](../../aspose.cad.fileformats.glb/animation/findscalechannel/)(Node) |  |
| [FindTranslationChannel](../../aspose.cad.fileformats.glb/animation/findtranslationchannel/)(Node) |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

