---
title: "ObjImage.Height"
linktitle: "高度"
articleTitle: "高度"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 属性。获取图像的高度。计算方式为所有顶点的 Y 坐标的最大值与最小值之差。最小..."
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.obj/objimage/height/"
product_version: "26.9"
---
## ObjImage.Height property

获取图像的高度。
计算方式为所有顶点的 Y 坐标的最大值与最小值之差。
允许的最小高度为 1。

```csharp
public override int Height { get; }
```

### Property Value

图像的高度。

## 示例

打印 OBJ 绘图的高度。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    System.Console.WriteLine("The height of the image is {0}", objImage.Height);
}
```

### 另请参阅

* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

