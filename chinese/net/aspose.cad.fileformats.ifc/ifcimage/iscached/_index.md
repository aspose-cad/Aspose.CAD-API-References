---
title: "IfcImage.IsCached"
linktitle: "IsCached"
articleTitle: "IsCached"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage 属性。获取一个值，指示对象的数据当前是否已缓存且无需读取数据。目前始终返回 true。"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.ifc/ifcimage/iscached/"
product_version: "26.9"
---
## IfcImage.IsCached property

获取一个值，指示对象的数据当前是否已缓存且无需读取数据。
目前始终返回 true

```csharp
public override bool IsCached { get; }
```

### Property Value

`true` 如果对象的数据已缓存；否则，`false`。

## 示例

获取图像的 isCached。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var isCached = ifcImage.IsCached
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

