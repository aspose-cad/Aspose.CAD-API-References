---
title: "Класс ValueListSet<T>"
linktitle: "ValueListSet<T>"
articleTitle: "ValueListSet<T>"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.ToolKit.Collections.ValueListSet класс. Представляет специализированный список, требующий уникальности всех элементов."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/"
keywords: "ValueListSet<T>, Aspose.CAD.FileFormats.GLB.ToolKit.Collections, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ValueListSet&lt;T&gt; class

Представляет специализированный список, требующий уникальности всех элементов.

```csharp
public class ValueListSet<T> : IReadOnlyList<T>
    where T : struct
```

| Параметр | Описание |
| --- | --- |
| T | Любой тип значения. |

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ValueListSet](valuelistset/#constructor)() | Конструктор по умолчанию. |
| [ValueListSet](valuelistset/#constructor_1)(int, IEqualityComparer) | Инициализирует новый экземпляр класса ValueListSet. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Comparer](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/comparer/) { get; } |  |
| [Count](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/count/) { get; } |  |
| [Indices](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/indices/) { get; } |  |
| [Item](../../aspose.cad.fileformats.glb.toolkit.collections/valuelistset-1/item/) { get; } |  |

## Методы

| Имя | Описание |
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

## Примечания

- This collection is based on `Dictionary`
 - Replaces `VertexList`
 - Designed to work with lists of vertices. This collection is:
 - like a HashSet, in the sense that every element must be unique.
 - like a list, because elements can be accessed by index: `Item`.
 - `IndexOf` and `Use` are fast as in a HashSet.

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.ToolKit.Collections](../../aspose.cad.fileformats.glb.toolkit.collections/)
* assembly [Aspose.CAD](../../)

