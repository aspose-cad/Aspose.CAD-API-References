---
title: "IfcImage.Header"
linktitle: "标题"
articleTitle: "标题"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage property. 获取标题。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.ifc/ifcimage/header/"
product_version: "26.9"
---
## IfcImage.Header property

获取头部信息。

```csharp
public IfcHeader Header { get; }
```

### Property Value

标题。

## 示例

获取图像的标题。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var header = ifcImage.Header        
}
```

### 另请参阅

* class [IfcHeader](../../../aspose.cad.fileformats.ifc.header/ifcheader/)
* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

