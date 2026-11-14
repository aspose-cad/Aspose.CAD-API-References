---
title: "Image.Bounds"
linktitle: "边界"
articleTitle: "边界"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 属性。获取图像边界。"
type: docs
weight: 190
url: "/net/aspose.cad/image/bounds/"
product_version: "26.9"
---
## Image.Bounds property

获取图像边界。

```csharp
public Rectangle Bounds { get; }
```

### Property Value

图像边界。

## 示例

根据边界对绘图进行自定义处理

```csharp
var fileName = @"C:\path\drawing.dwg";
using (Aspose.CAD.Image drawing = Aspose.CAD.Image.Load(fileName))
{
    if (drawing.Bounds.Width > 500)
    {
        // ...
    }
}
```

### 另请参阅

* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

