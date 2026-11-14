---
title: "IfcImage.Width"
linktitle: "宽度"
articleTitle: "宽度"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage property. 获取图像宽度。它是根据所有实体计算的"
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.ifc/ifcimage/width/"
product_version: "26.9"
---
## IfcImage.Width property

获取图像宽度。
它是根据所有实体计算的

```csharp
public override int Width { get; }
```

### Property Value

图像宽度。

## 示例

获取图像的宽度。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var width = ifcImage.Width
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

