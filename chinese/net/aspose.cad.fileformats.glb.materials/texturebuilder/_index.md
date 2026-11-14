---
title: "TextureBuilder 类"
linktitle: "TextureBuilder"
articleTitle: "TextureBuilder"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Materials.TextureBuilder 类。表示 ChannelBuilder 使用的纹理。"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.glb.materials/texturebuilder/"
keywords: "TextureBuilder, Aspose.CAD.FileFormats.GLB.Materials, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TextureBuilder class

表示由 [`ChannelBuilder`](../channelbuilder/) 使用的纹理

```csharp
public class TextureBuilder : BaseBuilder
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [ContentComparer](../../aspose.cad.fileformats.glb.materials/texturebuilder/contentcomparer/) { get; } |  |
| [CoordinateSet](../../aspose.cad.fileformats.glb.materials/texturebuilder/coordinateset/) { get; set; } |  |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [FallbackImage](../../aspose.cad.fileformats.glb.materials/texturebuilder/fallbackimage/) { get; set; } | 获取或设置此 `TextureBuilder` 使用的回退图像字节，支持的格式有：PNG，JPG。 |
| [MagFilter](../../aspose.cad.fileformats.glb.materials/texturebuilder/magfilter/) { get; set; } |  |
| [MinFilter](../../aspose.cad.fileformats.glb.materials/texturebuilder/minfilter/) { get; set; } |  |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [PrimaryImage](../../aspose.cad.fileformats.glb.materials/texturebuilder/primaryimage/) { get; set; } | 获取或设置此 `TextureBuilder` 使用的默认图像字节，支持的格式有：PNG、JPG、DDS、WEBP 和 KTX2。 |
| [Transform](../../aspose.cad.fileformats.glb.materials/texturebuilder/transform/) { get; } |  |
| [WrapS](../../aspose.cad.fileformats.glb.materials/texturebuilder/wraps/) { get; set; } |  |
| [WrapT](../../aspose.cad.fileformats.glb.materials/texturebuilder/wrapt/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [AreEqualByContent](../../aspose.cad.fileformats.glb.materials/texturebuilder/areequalbycontent/)(TextureBuilder, TextureBuilder) |  |
| static [GetContentHashCode](../../aspose.cad.fileformats.glb.materials/texturebuilder/getcontenthashcode/)(TextureBuilder) |  |
| [WithCoordinateSet](../../aspose.cad.fileformats.glb.materials/texturebuilder/withcoordinateset/)(int) |  |
| [WithFallbackImage](../../aspose.cad.fileformats.glb.materials/texturebuilder/withfallbackimage/)(ImageBuilder) |  |
| [WithPrimaryImage](../../aspose.cad.fileformats.glb.materials/texturebuilder/withprimaryimage/)(ImageBuilder) |  |
| [WithSampler](../../aspose.cad.fileformats.glb.materials/texturebuilder/withsampler/)(TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) |  |
| [WithTransform](../../aspose.cad.fileformats.glb.materials/texturebuilder/withtransform/#withtransform)(Vector2, Vector2, float, int?) |  |
| [WithTransform](../../aspose.cad.fileformats.glb.materials/texturebuilder/withtransform/#withtransform_1)(float, float, float, float, float, int?) |  |

### 另请参阅

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Materials](../../aspose.cad.fileformats.glb.materials/)
* assembly [Aspose.CAD](../../)

