---
title: "IfcImage.Entities"
linktitle: "Entities"
articleTitle: "Entities"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage property. 获取绘图中存在的所有实体。可用于遍历它们并检查其属性"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.ifc/ifcimage/entities/"
product_version: "26.9"
---
## IfcImage.Entities property

获取绘图中存在的所有实体。
可用于遍历它们并检查其属性

```csharp
public IEnumerable<IIfcEntity> Entities { get; }
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

* interface [IIfcEntity](../../iifcentity/)
* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

