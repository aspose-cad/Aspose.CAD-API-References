---
title: "VisualScene 类"
linktitle: "VisualScene"
articleTitle: "VisualScene"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.VisualScene 类。VisualScene。visual_scene 元素声明 visual_scene 层次结构的基础……"
type: docs
weight: 1350
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/visualscene/"
keywords: "VisualScene, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## VisualScene class

VisualScene。
visual_scene 元素声明 visual_scene 层次结构或场景图的基础。
场景包含由创作工具生成的大部分视觉和变换信息内容的元素。

```csharp
public class VisualScene : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VisualScene](visualscene/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Asset](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/asset/) { get; set; } | 获取或设置资产。visual_scene 元素可能包含 asset 元素。 |
| [EvaluateScene](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/evaluatescene/) { get; set; } | 获取或设置 evaluate 场景。evaluate_scene 元素声明指定如何评估此 visual_scene 的信息。可以有任意数量的 evaluate_scene 元素。它们按顺序评估，特定的元素可以通过设置 enabled=false 来禁用。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/extra/) { get; set; } | 获取或设置 extra。extra 元素可以出现任意次数。 |
| [Id](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/id/) { get; set; } | 获取或设置 id。id 属性是包含此元素唯一标识符的文本字符串。该值必须在实例文档中唯一。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Node](../../aspose.cad.fileformats.collada.fileparser.elements/visualscene/node/) { get; set; } | 获取或设置节点。visual_scene 元素必须至少包含一个 node 元素。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

