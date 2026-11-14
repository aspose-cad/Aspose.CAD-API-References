---
title: "IfcImage.Layers"
linktitle: "图层"
articleTitle: "图层"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage property. 获取图像中存在的所有图层的列表。获取图像的图层。 using (IfcImage ifcImage = (IfcImage)Image.Load(..."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.ifc/ifcimage/layers/"
product_version: "26.9"
---
## IfcImage.Layers property

获取图像中存在的所有图层列表
 
获取图像的图层。
 
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
var layers = ifcImage.Layers
}

```csharp
public IList<string> Layers { get; }
```

## 示例

获取图像的图层。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var layers = ifcImage.Layers
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

