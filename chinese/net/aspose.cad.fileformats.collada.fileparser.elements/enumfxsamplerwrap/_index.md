---
title: "EnumFxSamplerWrap 枚举"
linktitle: "EnumFxSamplerWrap"
articleTitle: "EnumFxSamplerWrap"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.EnumFxSamplerWrap 枚举。FX 采样器包装方式的枚举。"
type: docs
weight: 360
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/enumfxsamplerwrap/"
product_version: "26.9"
---
## EnumFxSamplerWrap enumeration

FX sampler wrap 枚举。

```csharp
public enum EnumFxSamplerWrap
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| WRAP | `0` | 包装。将在每个整数节点平铺纹理。例如，对于 u 值在 0 到 3 之间，纹理会重复三次；不进行镜像。 |
| CLAMP | `1` | 夹紧。等同于 CLIP_TO_EDGE。纹理坐标达到或超过范围 [0.0, 1.0] 时，会被设置在 0.0 或 1.0 以内，以免采样到边界。 |
| BORDER | `2` | 边框。类似 clamp，但纹理坐标超出范围 [0.0, 1.0] 时会被设置为边框颜色。 |
| MIRROR | `3` | 镜像。纹理在每个整数节点处翻转。例如，对于 u 值在 0 到 1 之间时，纹理按正常方式取样；在 1 到 2 之间时，纹理被翻转（镜像）；在 2 到 3 之间时，纹理再次正常；依此类推。 |
| MIRROR_ONCE | `4` | 一次镜像。对纹理坐标取绝对值（即在 0 周围镜像），然后将其限制到最大值。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

