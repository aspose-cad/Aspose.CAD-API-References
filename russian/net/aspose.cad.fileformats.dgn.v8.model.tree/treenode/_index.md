---
title: "Класс TreeNode"
linktitle: "TreeNode"
articleTitle: "TreeNode"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dgn.V8.Model.Tree.TreeNode класс. Реализует узел дерева."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dgn.v8.model.tree/treenode/"
keywords: "TreeNode, Aspose.CAD.FileFormats.Dgn.V8.Model.Tree, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TreeNode class

Реализует узел [`Tree`](./tree/).

```csharp
public class TreeNode
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TreeNode](treenode/#constructor)() | Создаёт объект TreeNode. |
| [TreeNode](treenode/#constructor_1)(string) | Создаёт объект TreeNode. |
| [TreeNode](treenode/#constructor_2)(string, TreeNode[]) | Создаёт объект TreeNode. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FirstNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/firstnode/) { get; } | Первый дочерний узел этого узла. |
| [FullPath](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/fullpath/) { get; } | Возвращает полный путь этого узла. Путь состоит из меток каждого из узлов от корня до этого узла, разделённых символом pathSeparator. |
| [LastNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/lastnode/) { get; } | Последний дочерний узел этого узла. |
| [Level](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/level/) { get; } | Это обозначает глубину вложенности TreeNode. |
| [Name](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/name/) { get; set; } | Имя узла дерева — полезно для индексации. |
| [NextNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nextnode/) { get; } | Следующий соседний узел. |
| [Nodes](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/nodes/) { get; } |  |
| [Parent](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/parent/) { get; } | Получает родительский узел. |
| [PrevNode](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/prevnode/) { get; } | Предыдущий соседний узел. |
| [Tag](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tag/) { get; set; } |  |
| [Text](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/text/) { get; set; } | Текст метки узла дерева |
| [Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tree/) { get; } | Возвращает элемент управления TreeView, к которому принадлежит этот узел. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetNodeCount](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/getnodecount/)(bool) | Возвращает количество дочерних узлов. |
| [Remove](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/remove/)() | Удаляет этот узел из элемента управления TreeView. Дочерние узлы также удаляются из TreeView, но остаются привязанными к этому узлу. |
| override [ToString](../../aspose.cad.fileformats.dgn.v8.model.tree/treenode/tostring/)() | Возвращает текст метки узла дерева |

### См. также

* namespace [Aspose.CAD.FileFormats.Dgn.V8.Model.Tree](../../aspose.cad.fileformats.dgn.v8.model.tree/)
* assembly [Aspose.CAD](../../)

