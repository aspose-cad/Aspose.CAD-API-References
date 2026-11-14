---
title: "Node.GetWorldMatrix"
linktitle: "GetWorldMatrix"
articleTitle: "GetWorldMatrix"
second_title: "Aspose.CAD for .NET API 参考"
description: "Node 方法。获取此节点在给定动画的特定时间点的世界矩阵。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb/node/getworldmatrix/"
product_version: "26.9"
---
## Node.GetWorldMatrix method

获取此节点在给定动画的特定时间点的世界矩阵。

```csharp
public Matrix4x4 GetWorldMatrix(Animation animation, float time)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 动画 | 动画 | 要采样的动画。 |
| 时间 | Single | 动画中的时间偏移。 |

### 返回值

采样的变换。

## 备注

这是一个便利方法，但它较慢，最好缓存 [`GetCurveSamplers`](../getcurvesamplers/)。

### 另请参阅

* class [Animation](../../animation/)
* class [Node](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

