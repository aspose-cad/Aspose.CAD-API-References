---
title: "IHasEntities<T> 接口"
linktitle: "IHasEntities<T>"
articleTitle: "IHasEntities<T>"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.IHasEntities 接口。表示由实体组成的绘图的通用接口。"
type: docs
weight: 380
url: "/net/aspose.cad/ihasentities-1/"
product_version: "26.9"
---
## IHasEntities&lt;T&gt; interface

表示由实体组成的绘图的通用接口。

```csharp
public interface IHasEntities<T>
    where T : IDrawingEntity
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Entities](../../aspose.cad/ihasentities-1/entities/) { get; } | 获取绘图中存在的所有实体。可用于遍历它们并检查其属性。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [TryRemoveEntity](../../aspose.cad/ihasentities-1/tryremoveentity/)(T) | 如果存在，则从绘图中移除实体 |

### 另请参阅

* interface [IDrawingEntity](../idrawingentity/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

