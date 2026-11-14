---
title: "TreeNode 类"
linktitle: "TreeNode"
articleTitle: "TreeNode"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dgn.V8.Model.Tree.TreeNode 类。实现树的节点。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dgn.v8.model.tree/treenode/"
keywords: "TreeNode, Aspose.CAD.FileFormats.Dgn.V8.Model.Tree, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TreeNode class

实现一个 [`Tree`](./tree/) 的节点。

```csharp
public class TreeNode
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TreeNode](treenode/#constructor)() | 创建一个 TreeNode 对象。 |
| [TreeNode](treenode/#constructor_1)(string) | 创建一个 TreeNode 对象。 |
| [TreeNode](treenode/#constructor_2)(string, TreeNode[]) | 创建一个 TreeNode 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FirstNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/firstnode/) { get; } | 此节点的第一个子节点。 |
| [FullPath](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/fullpath/) { get; } | 返回此节点的完整路径。该路径由从根节点到此节点的每个节点的标签组成，标签之间使用 pathSeparator 分隔。 |
| [LastNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/lastnode/) { get; } | 此节点的最后一个子节点。 |
| [Level](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/level/) { get; } | 这表示 TreeNode 的嵌套深度。 |
| [Name](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/name/) { get; set; } | 树节点的名称——用于索引。 |
| [NextNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nextnode/) { get; } | 下一个兄弟节点。 |
| [Nodes](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nodes/) { get; } |  |
| [Parent](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/parent/) { get; } | 检索父节点。 |
| [PrevNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/prevnode/) { get; } | 上一个兄弟节点。 |
| [Tag](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tag/) { get; set; } |  |
| [Text](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/text/) { get; set; } | 树节点的标签文本 |
| [Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tree/) { get; } | 返回此节点所属的 TreeView 控件。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetNodeCount](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/getnodecount/)(bool) | 返回子节点的数量。 |
| [Remove](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/remove/)() | 从 TreeView 控件中移除此节点。子节点也会从 TreeView 中移除，但仍然附加在此节点上。 |
| override [ToString](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tostring/)() | 返回树节点的标签文本 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dgn.V8.Model.Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/)
* assembly [Aspose.CAD](../../)

