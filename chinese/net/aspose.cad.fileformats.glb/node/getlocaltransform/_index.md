---
title: "Node.GetLocalTransform"
linktitle: "GetLocalTransform"
articleTitle: "GetLocalTransform"
second_title: "Aspose.CAD for .NET API 参考"
description: "Node 方法。获取在给定动画的特定时间点此节点的局部变换。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb/node/getlocaltransform/"
product_version: "26.9"
---
## Node.GetLocalTransform method

获取此节点在给定动画的特定时间点的本地变换。

```csharp
public AffineTransform GetLocalTransform(Animation animation, float time)
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

* struct [AffineTransform](../../../aspose.cad.fileformats.glb.transforms/affinetransform/)
* class [Animation](../../animation/)
* class [Node](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

