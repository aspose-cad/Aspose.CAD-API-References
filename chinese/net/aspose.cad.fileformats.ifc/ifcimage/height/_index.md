---
title: "IfcImage.Height"
linktitle: "高度"
articleTitle: "高度"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage 属性。获取图像高度。该高度由所有实体计算得出"
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.ifc/ifcimage/height/"
product_version: "26.9"
---
## IfcImage.Height property

获取图像高度。
它是根据所有实体计算的

```csharp
public override int Height { get; }
```

### Property Value

图像高度。

## 示例

获取图像的高度。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var height = ifcImage.Height
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

