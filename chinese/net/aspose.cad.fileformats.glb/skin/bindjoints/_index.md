---
title: "Skin.BindJoints"
linktitle: "BindJoints"
articleTitle: "BindJoints"
second_title: "Aspose.CAD for .NET API 参考"
description: "Skin 方法。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/skin/bindjoints/"
product_version: "26.9"
---
## BindJoints(params Node[]) {#bindjoints}



```csharp
public void BindJoints(params Node[] joints)
```

### 另请参阅

* class [Node](../../node/)
* class [Skin](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## BindJoints(Matrix4x4, params Node[]) {#bindjoints_1}

将 [`Node`](../../node/) 的骨骼装配绑定到关联的蒙皮网格。

```csharp
public void BindJoints(Matrix4x4 meshBindTransform, params Node[] joints)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| meshBindTransform | Matrix4x4 | 绑定时网格的世界变换矩阵。 |
| joints | Node[] | 一组 [`Node`](../../node/) 关节。 |

## 备注

此方法使用每个关节的 [`WorldMatrix`](../../node/worldmatrix/) 值来计算逆绑定矩阵。

### 另请参阅

* class [Node](../../node/)
* class [Skin](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

