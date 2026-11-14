---
title: "Projection.CreatePerspectiveMatrix"
linktitle: "CreatePerspectiveMatrix"
articleTitle: "CreatePerspectiveMatrix"
second_title: "Aspose.CAD for .NET API 参考"
description: "投影方法。计算透视投影矩阵。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/projection/createperspectivematrix/"
product_version: "26.9"
---
## Projection.CreatePerspectiveMatrix method

计算透视投影矩阵。

```csharp
public static Matrix4x4 CreatePerspectiveMatrix(float aspectRatio, float yfov, float znear, 
    float zfar = inf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| aspectRatio | Single | 水平与垂直之间的宽高比。（可选） |
| yfov | Single | 垂直视场角，以弧度表示。 |
| znear | Single | Z 轴上最近平面的距离。 |
| zfar | Single | Z 轴上远平面的距离。可选地，此值可以是正无穷大 |

### 返回值

一个投影矩阵

### 另请参阅

* class [Projection](../)
* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../../)

