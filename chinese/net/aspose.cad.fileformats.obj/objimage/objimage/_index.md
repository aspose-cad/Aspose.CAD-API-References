---
title: "ObjImage.ObjImage"
linktitle: "ObjImage"
articleTitle: "ObjImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "ObjImage 构造函数。初始化 ObjImage 类的新实例。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.obj/objimage/objimage/"
product_version: "26.9"
---
## ObjImage constructor

初始化 [`ObjImage`](../) 类的新实例。

```csharp
public ObjImage(ObjRoot objRoot)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objRoot | ObjRoot | 包含顶点和形状的 ObjRoot 对象。 |

## 示例

创建新的 ObjRoot 对象，填充顶点和单个面，并导出为 PNG 格式。

```csharp
ObjRoot root = new ObjRoot(); 
root.Materials.Add(new ObjMaterial() { Diffuse = new Obj3Values(1, 0, 0) });

root.Vertices.Add(new ObjVertex(0, 0, 0));
root.Vertices.Add(new ObjVertex(100, 100, 100));
root.Vertices.Add(new ObjVertex(100, 200, 300));

ObjShape newShape = new ObjShape();
newShape.MaterialId = root.Materials.Count - 1;

ObjFace newFace = new ObjFace();
newFace.VertexTextureNormals.Add(new ObjVertexTextureNormalIndex() { VertexIndex = root.Vertices.Count - 3 });
newFace.VertexTextureNormals.Add(new ObjVertexTextureNormalIndex() { VertexIndex = root.Vertices.Count - 2 });
newFace.VertexTextureNormals.Add(new ObjVertexTextureNormalIndex() { VertexIndex = root.Vertices.Count - 1 });
newShape.Faces.Add(newFace);
root.Shapes.Add(newShape);

using (ObjImage newImage = new ObjImage(root))
{
CadRasterizationOptions options = new CadRasterizationOptions();
options.PageHeight = 300;
options.PageWidth = 300;
options.DrawType = CadDrawTypeMode.UseObjectColor;
newImage.Save(outputPngFile, new PngOptions() { VectorRasterizationOptions = options});
};
```

### 另请参阅

* class [ObjRoot](../../../aspose.cad.fileformats.obj.elements/objroot/)
* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

