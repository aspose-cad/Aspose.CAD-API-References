---
title: "IfcImage.Depth"
linktitle: "深度"
articleTitle: "深度"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage property. 获取深度。它是根据所有实体计算的"
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.ifc/ifcimage/depth/"
product_version: "26.9"
---
## IfcImage.Depth property

获取深度。
它是根据所有实体计算的

```csharp
public override int Depth { get; }
```

### Property Value

深度。

## 示例

获取图像的深度。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var depth = ifcImage.Depth
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

