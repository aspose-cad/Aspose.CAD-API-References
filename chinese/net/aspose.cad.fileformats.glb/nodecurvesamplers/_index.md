---
title: "NodeCurveSamplers 结构体"
linktitle: "NodeCurveSamplers"
articleTitle: "NodeCurveSamplers"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.NodeCurveSamplers 结构体。表示一个代理，用于访问节点的动画曲线。使用 GetCurveSamplers 进行访问。"
type: docs
weight: 400
url: "/net/aspose.cad.fileformats.glb/nodecurvesamplers/"
product_version: "26.9"
---
## NodeCurveSamplers struct

表示一个代理，用于访问 [`Node`](../node/) 的动画曲线。
使用 [`GetCurveSamplers`](../node/getcurvesamplers/) 进行访问。

```csharp
public struct NodeCurveSamplers : IEquatable<NodeCurveSamplers>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| HasMorphingCurves { get; } | 如果存在形变曲线，则为 true。 |
| HasTransformCurves { get; } | 如果定义了 Scale、Rotation 或 Translation 中的任意一个，则为 true。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Equals(NodeCurveSamplers) |  |
| Equals(object) |  |
| GetHashCode() |  |
| GetLocalTransform(float) |  |
| GetMorphingWeights(float) |  |
| GetSparseMorphingWeights(float) |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| 动画 |  |
| TargetNode |  |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 == |  |
| 运算符 != |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

