---
title: "IIfcEntity.EntityLabel"
linktitle: "实体标签"
articleTitle: "实体标签"
second_title: "Aspose.CAD for .NET API 参考"
description: "IIfcEntity 属性。获取实体标签。每个实体都有其标签，该标签是唯一的并在文件中表示它。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.ifc/iifcentity/entitylabel/"
product_version: "26.9"
---
## IIfcEntity.EntityLabel property

获取实体标签。
每个实体都有其标签，该标签是唯一的并在文件中表示它。

```csharp
public int EntityLabel { get; }
```

### Property Value

实体标签。

## 示例

获取第一个实体标签。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var label = ifcImage._entities[0].EntityLabel
}
```

### 另请参阅

* interface [IIfcEntity](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

