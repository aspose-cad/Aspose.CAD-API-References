---
title: "ObjImage.GetShapes"
linktitle: "GetShapes"
articleTitle: "GetShapes"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 方法。获取 OBJ 图像可绘制形状的数据。每个形状包含其名称、材质和面的信息。ObjFace 包含关于..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.obj/objimage/getshapes/"
product_version: "26.9"
---
## ObjImage.GetShapes method

获取 OBJ 图像可绘制形状的数据。
每个形状包含其名称、材质和面的信息。
ObjFace 包含关于相应顶点、纹理和法线索引的数据。

```csharp
public IEnumerable<ObjShape> GetShapes()
```

## 示例

打印每个形状的面数量。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    foreach (ObjShape shape in objImage.GetShapes())
    {
        System.Console.WriteLine("Shape has {0} faces", shape.Faces.Count);
    }
}
```

### 另请参阅

* class [ObjShape](../../../aspose.cad.fileformats.obj.elements/objshape/)
* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

