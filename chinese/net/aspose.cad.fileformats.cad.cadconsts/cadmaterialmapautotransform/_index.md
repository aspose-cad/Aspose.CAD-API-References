---
title: "CadMaterialMapAutoTransform 枚举"
linktitle: "CadMaterialMapAutoTransform"
articleTitle: "CadMaterialMapAutoTransform"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapAutoTransform 枚举。指定 CadMaterialMap 的自动变换方法。"
type: docs
weight: 330
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmapautotransform/"
product_version: "26.9"
---
## CadMaterialMapAutoTransform enumeration

指定 [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/) 的自动变换方法。

```csharp
[Flags]
public enum CadMaterialMapAutoTransform : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Inherit | `0` | 从父级继承自动变换设置。 |
| None | `1` | 未应用自动变换。 |
| TransformObject | `2` | 将映射器变换乘以一个按当前对象边界缩放并平移到当前对象原点的变换。 |
| Model | `4` | 将映射器变换乘以模型（块）变换。 |

### 另请参阅

* [AutoTransform](../autotransform/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

