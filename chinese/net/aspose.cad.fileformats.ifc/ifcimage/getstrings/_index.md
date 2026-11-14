---
title: "IfcImage.GetStrings"
linktitle: "GetStrings"
articleTitle: "GetStrings"
second_title: "Aspose.CAD for .NET API 参考"
description: "IfcImage 方法。获取图像中的所有字符串值。可用于获取图像中的一些文本。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.ifc/ifcimage/getstrings/"
product_version: "26.9"
---
## IfcImage.GetStrings method

获取图像中的所有字符串值。
可用于获取图像中的一些文本

```csharp
public override string[] GetStrings()
```

### 返回值

包含字符串值的数组。

## 示例

获取图像中的所有字符串。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var strings = ifcImage.GetStrings()
}
```

### 另请参阅

* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

