---
title: "CadMaterialMapTiling 枚举"
linktitle: "CadMaterialMapTiling"
articleTitle: "CadMaterialMapTiling"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapTiling 枚举。指定 CadMaterialMap 的平铺方法。"
type: docs
weight: 360
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmaptiling/"
product_version: "26.9"
---
## CadMaterialMapTiling enumeration

指定 [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/) 的平铺方法。

```csharp
public enum CadMaterialMapTiling : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Inherit | `0` | 从父级继承平铺设置。 |
| Tile | `1` | 沿图像轴重复材质映射（默认）。 |
| Crop | `2` | 在图像轴上将材质映射裁剪至低于 0.0 和高于 1.0 的范围。 |
| Clamp | `3` | 在图像轴上将材质映射限制在 0.0 到 1.0 之间。 |
| Mirror | `4` | 抓取操作为镜像。 |

### 另请参阅

* [Tiling](../tiling/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

