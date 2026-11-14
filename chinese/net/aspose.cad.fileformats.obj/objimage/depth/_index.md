---
title: "ObjImage.Depth"
linktitle: "深度"
articleTitle: "深度"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 属性。获取图像的深度。计算方式为所有顶点的 Z 坐标的最大值与最小值之差。最小..."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.obj/objimage/depth/"
product_version: "26.9"
---
## ObjImage.Depth property

获取图像的深度。
计算方式为所有顶点的 Z 坐标的最大值与最小值之差。
允许的最小深度为 0。

```csharp
public override int Depth { get; }
```

### Property Value

图像的深度。

## 示例

打印 OBJ 绘图的深度。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    System.Console.WriteLine("The depth of the image is {0}", objImage.Depth);
}
```

### 另请参阅

* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

