---
title: "CadMaterialChannelFlag 枚举"
linktitle: "CadMaterialChannelFlag"
articleTitle: "CadMaterialChannelFlag"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialChannelFlag 枚举。指示 CadMaterial 哪些纹理通道处于活动状态的标志。可以组合多个标志……"
type: docs
weight: 300
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialchannelflag/"
product_version: "26.9"
---
## CadMaterialChannelFlag enumeration

指示 [`CadMaterial`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterial/) 哪些纹理通道处于活动状态的标志。可以组合多个标志。

```csharp
[Flags]
public enum CadMaterialChannelFlag : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 没有纹理通道处于活动状态。 |
| UseDiffuse | `1` | 漫反射纹理通道处于活动状态。 |
| UseSpecular | `2` | 高光纹理通道处于活动状态。 |
| UseReflection | `4` | 反射纹理通道处于活动状态。 |
| UseOpacity | `8` | 不透明度纹理通道处于活动状态。 |
| UseBump | `10` | 凹凸纹理通道处于活动状态。 |
| UseRefraction | `20` | 折射纹理通道处于活动状态。 |
| UseAll | `3F` | 所有纹理通道均已激活。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

