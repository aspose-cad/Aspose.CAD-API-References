---
title: "Image.Size"
linktitle: "Size"
articleTitle: "Size"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 属性。获取图像尺寸。"
type: docs
weight: 240
url: "/net/aspose.cad/image/size/"
product_version: "26.9"
---
## Image.Size property

获取图像尺寸。

```csharp
public Size Size { get; }
```

### Property Value

图像尺寸。

## 示例

如果绘图不为空，则处理该绘图。

```csharp
var fileName = @"C:\path\drawing.dwg";
using (Aspose.CAD.Image drawing = Aspose.CAD.Image.Load(fileName))
{
    if (!drawing.Size.IsEmpty)
    {
        // ...
    }
}
```

### 另请参阅

* struct [Size](../../size/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

