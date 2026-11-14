---
title: "GlbData.ApplyBasisTransform"
linktitle: "ApplyBasisTransform"
articleTitle: "ApplyBasisTransform"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。对模型的所有场景应用全局变换。"
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.glb/glbdata/applybasistransform/"
product_version: "26.9"
---
## GlbData.ApplyBasisTransform method

对模型的所有场景应用世界变换。

```csharp
public void ApplyBasisTransform(Matrix4x4 basisTransform, string basisNodeName = "BasisTransform")
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| basisTransform | Matrix4x4 | 要应用的变换。 |
| basisNodeName | String | 如果需要创建，新根节点的名称。 |

## 备注

此方法适用于对整个模型应用一般的轴或缩放变换。
通过将动画节点封装在主基准变换节点内部来保留动画。
与此同时，未动画的节点直接进行变换。
如果 *basisTransform* 的行列式为负，面剔除应该
在渲染时翻转。

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

