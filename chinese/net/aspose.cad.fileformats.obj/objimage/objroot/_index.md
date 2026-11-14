---
title: "ObjImage.ObjRoot"
linktitle: "ObjRoot"
articleTitle: "ObjRoot"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 属性。获取或设置绘图的根信息。ObjRoot 包含关于顶点、材质和形状的数据。可能对导出信息有用..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.obj/objimage/objroot/"
product_version: "26.9"
---
## ObjImage.ObjRoot property

获取或设置绘图的根信息。
ObjRoot 包含关于顶点、材质和形状的数据。
可能对面信息的展示有用。

```csharp
public ObjRoot ObjRoot { get; set; }
```

## 示例

打印 OBJ 绘图中顶点的总数量。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    ObjRoot rootInformation = objImage.ObjRoot;
    System.Console.WriteLine("The drawing has {0} vertices", rootInformation.Vertices.Count);
}
```

### 另请参阅

* class [ObjRoot](../../../aspose.cad.fileformats.obj.elements/objroot/)
* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

