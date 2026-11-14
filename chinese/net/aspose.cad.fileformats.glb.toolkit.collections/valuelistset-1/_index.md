---
title: "ValueListSet<T> 类"
linktitle: "ValueListSet<T>"
articleTitle: "ValueListSet<T>"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.ToolKit.Collections.ValueListSet 类。表示一个需要所有元素唯一的专用列表。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/"
keywords: "ValueListSet<T>, Aspose.CAD.FileFormats.GLB.ToolKit.Collections, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ValueListSet&lt;T&gt; class

表示一个要求所有元素唯一的专用列表。

```csharp
public class ValueListSet<T> : IReadOnlyList<T>
    where T : struct
```

| 参数 | 描述 |
| --- | --- |
| T | 任意值类型。 |

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ValueListSet](valuelistset/#constructor)() | 默认构造函数。 |
| [ValueListSet](valuelistset/#constructor_1)(int, IEqualityComparer) | 初始化 ValueListSet 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Comparer](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/comparer/) { get; } |  |
| [Count](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/count/) { get; } |  |
| [Indices](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/indices/) { get; } |  |
| [Item](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/item/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/add/)(ref T) |  |
| [ApplyTransform](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/applytransform/)(Func&lt;T, T&gt;) |  |
| [Clear](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/clear/)() |  |
| [Contains](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/contains/)(ref T) |  |
| [CopyTo](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/copyto/#copyto)(ValueListSet&lt;T&gt;) |  |
| [CopyTo](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/copyto/#copyto_1)(T[], int) |  |
| [Exists](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/exists/)(int) |  |
| [GetEnumerator](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/getenumerator/)() |  |
| [IndexOf](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/indexof/)(ref T) |  |
| [Use](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/use/)(ref T) |  |

## 备注

- This collection is based on `Dictionary`
 - Replaces `VertexList`
 - Designed to work with lists of vertices. This collection is:
 - like a HashSet, in the sense that every element must be unique.
 - like a list, because elements can be accessed by index: `Item`.
 - `IndexOf` and `Use` are fast as in a HashSet.

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.ToolKit.Collections](../../aspose.cad.fileformats.glb.toolkit.collections/)
* assembly [Aspose.CAD](../../)

