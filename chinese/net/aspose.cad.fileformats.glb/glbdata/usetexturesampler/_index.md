---
title: "GlbData.UseTextureSampler"
linktitle: "UseTextureSampler"
articleTitle: "UseTextureSampler"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。创建或复用一个位于 LogicalTextureSamplers 的 TextureSampler 实例。"
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.glb/glbdata/usetexturesampler/"
product_version: "26.9"
---
## GlbData.UseTextureSampler method

创建或复用一个 [`TextureSampler`](../../texturesampler/) 实例
位于 [`LogicalTextureSamplers`](../logicaltexturesamplers/)。

```csharp
public TextureSampler UseTextureSampler(TextureWrapMode ws, TextureWrapMode wt, 
    TextureMipMapFilter min, TextureInterpolationFilter mag)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ws | TextureWrapMode | S 轴上的 [`TextureWrapMode`](../../texturewrapmode/)。 |
| wt | TextureWrapMode | T 轴上的 [`TextureWrapMode`](../../texturewrapmode/)。 |
| min | TextureMipMapFilter | `[`TextureMipMapFilter`](../../texturemipmapfilter/)` 的值。 |
| mag | TextureInterpolationFilter | `[`TextureInterpolationFilter`](../../textureinterpolationfilter/)` 的值。 |

### 返回值

一个 [`TextureSampler`](../../texturesampler/) 实例，如果所有参数都是默认值则为 null。

### 另请参阅

* class [TextureSampler](../../texturesampler/)
* enum [TextureWrapMode](../../texturewrapmode/)
* enum [TextureMipMapFilter](../../texturemipmapfilter/)
* enum [TextureInterpolationFilter](../../textureinterpolationfilter/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

