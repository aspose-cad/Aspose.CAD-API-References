---
title: "Image.Container"
linktitle: "容器"
articleTitle: "容器"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 属性。获取 Image 容器。"
type: docs
weight: 200
url: "/net/aspose.cad/image/container/"
product_version: "26.9"
---
## Image.Container property

获取 [`Image`](../) 容器。

```csharp
public Image Container { get; }
```

### Property Value

[`Image`](../) 容器。

## 备注

如果此属性不为 null，则表示图像包含在另一个图像中。

## 示例

获取当前绘图所在的根（顶层）绘图。

```csharp
Image drawing = ...
while (drawing.Container != null)
{
    drawing = drawing.Container;
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

