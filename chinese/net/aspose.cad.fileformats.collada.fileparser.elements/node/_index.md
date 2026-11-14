---
title: "Node 类"
linktitle: "Node"
articleTitle: "Node"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Node 类。该节点。节点体现场景中元素的层次关系。"
type: docs
weight: 860
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/node/"
keywords: "Node, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Node class

节点。
节点体现场景中元素的层次关系。

```csharp
public class Node : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Node](node/)() | 初始化 `Node` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Asset](../../aspose.cad.fileformats.collada.fileparser.elements/node/asset/) { get; set; } | 获取或设置资产。节点元素可能包含资产元素。 |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/node/extra/) { get; set; } | 获取或设置 extra。extra 元素可以出现任意次数。 |
| [Id](../../aspose.cad.fileformats.collada.fileparser.elements/node/id/) { get; set; } | 获取或设置 id。id 属性是包含此元素唯一标识符的文本字符串。该值必须在实例文档中唯一。可选属性。 |
| [InstanceCamera](../../aspose.cad.fileformats.collada.fileparser.elements/node/instancecamera/) { get; set; } | 获取或设置实例相机。节点元素可以实例化任意数量的相机对象。 |
| [InstanceGeometry](../../aspose.cad.fileformats.collada.fileparser.elements/node/instancegeometry/) { get; set; } | 获取或设置实例几何体。节点元素可以实例化任意数量的几何体对象。 |
| [InstanceLight](../../aspose.cad.fileformats.collada.fileparser.elements/node/instancelight/) { get; set; } | 获取或设置实例灯光。节点元素可以实例化任意数量的灯光对象。 |
| [InstanceNode](../../aspose.cad.fileformats.collada.fileparser.elements/node/instancenode/) { get; set; } | 获取或设置实例节点。节点元素可以实例化任意数量的节点元素或层次对象。 |
| [Layer](../../aspose.cad.fileformats.collada.fileparser.elements/node/layer/) { get; set; } | 获取或设置图层。layer 属性指示此节点所属的图层名称。例如，值为 "foreground glowing" 表示此节点同时属于 'foreground' 图层和 'glowing' 图层。默认值为空，表示该节点不属于任何图层。可选属性。 |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/node/name/) { get; set; } | 获取或设置 name。name 属性是此元素的文本字符串名称。可选属性。 |
| [Nodes](../../aspose.cad.fileformats.collada.fileparser.elements/node/nodes/) { get; set; } | 获取或设置节点。节点元素可以是层次结构，并且可以是任意数量其他节点元素的父节点。 |
| [Sid](../../aspose.cad.fileformats.collada.fileparser.elements/node/sid/) { get; set; } | 获取或设置 sid。sid 属性是包含此元素子标识符的文本字符串值。此值必须在父元素范围内唯一。可选属性。 |
| [TransformItems](../../aspose.cad.fileformats.collada.fileparser.elements/node/transformitems/) { get; set; } | 获取或设置变换项。 |
| [Type](../../aspose.cad.fileformats.collada.fileparser.elements/node/type/) { get; set; } | 获取或设置节点类型。type 属性指示节点元素的类型。默认值为 "NODE"。可选属性。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

