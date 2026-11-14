---
title: "ObjImage.Width"
linktitle: "宽度"
articleTitle: "宽度"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 属性。获取图像的宽度。计算方式为所有顶点的 X 坐标最大值与最小值之差。最..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.obj/objimage/width/"
product_version: "26.9"
---
## ObjImage.Width property

获取图像的宽度。
计算方式为所有顶点的 X 坐标最大值与最小值之差。
最小允许宽度为 1。

```csharp
public override int Width { get; }
```

### Property Value

图像的宽度。

## 示例

打印 OBJ 绘图的宽度。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    System.Console.WriteLine("The width of the image is {0}", objImage.Width);
}
```

### 另请参阅

* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

