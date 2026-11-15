---
title: "GlbData.UseTextureSampler"
linktitle: "UseTextureSampler"
articleTitle: "UseTextureSampler"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Создает или переиспользует экземпляр TextureSampler в LogicalTextureSamplers."
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.glb/glbdata/usetexturesampler/"
product_version: "26.9"
---
## GlbData.UseTextureSampler method

Создает или переиспользует экземпляр [`TextureSampler`](../../texturesampler/)
в [`LogicalTextureSamplers`](../logicaltexturesamplers/).

```csharp
public TextureSampler UseTextureSampler(TextureWrapMode ws, TextureWrapMode wt, 
    TextureMipMapFilter min, TextureInterpolationFilter mag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ws | TextureWrapMode | Значение [`TextureWrapMode`](../../texturewrapmode/) по оси S. |
| wt | TextureWrapMode | Значение [`TextureWrapMode`](../../texturewrapmode/) по оси T. |
| min | TextureMipMapFilter | Значение [`TextureMipMapFilter`](../../texturemipmapfilter/). |
| mag | TextureInterpolationFilter | Значение [`TextureInterpolationFilter`](../../textureinterpolationfilter/). |

### Возвращаемое значение

Экземпляр [`TextureSampler`](../../texturesampler/), или null, если все аргументы имеют значения по умолчанию.

### См. также

* class [TextureSampler](../../texturesampler/)
* enum [TextureWrapMode](../../texturewrapmode/)
* enum [TextureMipMapFilter](../../texturemipmapfilter/)
* enum [TextureInterpolationFilter](../../textureinterpolationfilter/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

