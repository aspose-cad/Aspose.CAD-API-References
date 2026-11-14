---
title: "EvaluateScene 类"
linktitle: "EvaluateScene"
articleTitle: "EvaluateScene"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.EvaluateScene 类。EvaluateScene。evaluate_scene 元素声明指定如何……"
type: docs
weight: 410
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/"
keywords: "EvaluateScene, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## EvaluateScene class

评估场景。
evaluate_scene 元素声明了指定如何评估此 visual_scene 的信息。
可能会有任意数量的 evaluate_scene 元素。
它们按顺序进行评估，特定的元素可以通过设置 enabled=false 来禁用。

```csharp
public class EvaluateScene : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EvaluateScene](evaluatescene/)() | 初始化 `EvaluateScene` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Asset](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/asset/) { get; set; } | 获取或设置资产。 |
| [Enable](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/enable/) { get; set; } | 获取或设置一个值，指示评估是否已启用。允许将其禁用，从而在评估期间跳过。这对于调试很有用。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/extra/) { get; set; } | 获取或设置 extra。extra 元素可以出现任意次数。 |
| [Id](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/id/) { get; set; } | 获取或设置 id。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/name/) { get; set; } | 获取或设置名称。 |
| [Render](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/render/) { get; set; } | 获取或设置 render。render 元素描述了评估场景的一个效果通道。必须至少有一个 render 元素。 |
| [Sid](../../aspose.cad.fileformats.collada.fileparser.elements/evaluatescene/sid/) { get; set; } | 获取或设置 sid。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

