---
title: "Класс Animation"
linktitle: "Анимация"
articleTitle: "Анимация"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.Animation. Анимация ключевых кадров."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb/animation/"
keywords: "Animation, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Animation class

Анимация ключевых кадров.

```csharp
public sealed class Animation : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Channels](../../aspose.cad.fileformats.glb/animation/channels/) { get; } |  |
| [Duration](../../aspose.cad.fileformats.glb/animation/duration/) { get; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |

## Методы

| Имя | Описание |
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

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

