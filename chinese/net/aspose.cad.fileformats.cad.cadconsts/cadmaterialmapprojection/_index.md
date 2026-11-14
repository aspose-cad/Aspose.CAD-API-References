---
title: "CadMaterialMapProjection 枚举"
linktitle: "CadMaterialMapProjection"
articleTitle: "CadMaterialMapProjection"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapProjection 枚举. 指定 CadMaterialMap 的纹理投影方法。"
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmapprojection/"
product_version: "26.9"
---
## CadMaterialMapProjection enumeration

指定纹理投影方法用于 [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/)。

```csharp
public enum CadMaterialMapProjection : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Inherit | `0` | 从父级继承投影。 |
| Planar | `1` | 将二维图像坐标直接映射到 XY 坐标。 |
| Box | `2` | 将二维图像坐标映射到垂直于主轴的平面。 |
| Cylinder | `3` | 将二维图像坐标映射到沿 Z 轴的圆柱体。 |
| Sphere | `4` | 将二维图像坐标映射到极点位于 Z 轴的球体。 |

### 另请参阅

* [Projection](../projection/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

