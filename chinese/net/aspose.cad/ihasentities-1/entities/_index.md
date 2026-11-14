---
title: "IHasEntities<T>.Entities"
linktitle: "Entities"
articleTitle: "Entities"
second_title: "Aspose.CAD for .NET API 参考"
description: "IHasEntities 属性。获取图形上存在的所有实体。可用于遍历它们并检查其属性"
type: docs
weight: 20
url: "/net/aspose.cad/ihasentities-1/entities/"
product_version: "26.9"
---
## IHasEntities<T>.Entities property

获取图形上存在的所有实体。
可用于遍历它们并检查其属性

```csharp
public IEnumerable<T> Entities { get; }
```

### Property Value

一组实体实例

## 示例

获取绘图中的实体集合。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var entities = ifcImage.Entities
}
```

### 另请参阅

* interface [IHasEntities&lt;T&gt;](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

