---
title: "TreeNode Class"
linktitle: "TreeNode"
articleTitle: "TreeNode"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Dgn.V8.Model.Tree.TreeNode class. Implements a node of a Tree."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dgn.v8.model.tree/treenode/"
keywords: "TreeNode, Aspose.CAD.FileFormats.Dgn.V8.Model.Tree, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TreeNode class

Implements a node of a [`Tree`](./tree/).

```csharp
public class TreeNode
```

## Constructors

| Name | Description |
| --- | --- |
| [TreeNode](treenode/#constructor)() | Creates a TreeNode object. |
| [TreeNode](treenode/#constructor_1)(string) | Creates a TreeNode object. |
| [TreeNode](treenode/#constructor_2)(string, TreeNode[]) | Creates a TreeNode object. |

## Properties

| Name | Description |
| --- | --- |
| [FirstNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/firstnode/) { get; } | The first child node of this node. |
| [FullPath](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/fullpath/) { get; } | Returns the full path of this node. The path consists of the labels of each of the nodes from the root to this node, each separated by the pathSeparator. |
| [LastNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/lastnode/) { get; } | The last child node of this node. |
| [Level](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/level/) { get; } | This denotes the depth of nesting of the TreeNode. |
| [Name](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/name/) { get; set; } | The name for the tree node - useful for indexing. |
| [NextNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nextnode/) { get; } | The next sibling node. |
| [Nodes](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nodes/) { get; } |  |
| [Parent](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/parent/) { get; } | Retrieves parent node. |
| [PrevNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/prevnode/) { get; } | The previous sibling node. |
| [Tag](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tag/) { get; set; } |  |
| [Text](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/text/) { get; set; } | The label text for the tree node |
| [Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tree/) { get; } | Return the TreeView control this node belongs to. |

## Methods

| Name | Description |
| --- | --- |
| [GetNodeCount](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/getnodecount/)(bool) | Returns number of child nodes. |
| [Remove](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/remove/)() | Remove this node from the TreeView control. Child nodes are also removed from the TreeView, but are still attached to this node. |
| override [ToString](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tostring/)() | Returns the label text for the tree node |

### See Also

* namespace [Aspose.CAD.FileFormats.Dgn.V8.Model.Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/)
* assembly [Aspose.CAD](../../)

