---
title: "MaterialBuilder 类"
linktitle: "MaterialBuilder"
articleTitle: "MaterialBuilder"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Materials.MaterialBuilder 类。表示材质实例结构的根对象。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.glb.materials/materialbuilder/"
keywords: "MaterialBuilder, Aspose.CAD.FileFormats.GLB.Materials, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## MaterialBuilder class

表示材质实例结构的根对象。

```csharp
public class MaterialBuilder : BaseBuilder, ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MaterialBuilder](materialbuilder/#constructor)(MaterialBuilder) | 初始化 MaterialBuilder 类的新实例。 |
| [MaterialBuilder](materialbuilder/#constructor_1)(string) | 初始化 MaterialBuilder 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlphaCutoff](../../aspose.cad.fileformats.glb.materials/materialbuilder/alphacutoff/) { get; set; } |  |
| [AlphaMode](../../aspose.cad.fileformats.glb.materials/materialbuilder/alphamode/) { get; set; } |  |
| [Channels](../../aspose.cad.fileformats.glb.materials/materialbuilder/channels/) { get; } |  |
| [CompatibilityFallback](../../aspose.cad.fileformats.glb.materials/materialbuilder/compatibilityfallback/) { get; set; } |  |
| static [ContentComparer](../../aspose.cad.fileformats.glb.materials/materialbuilder/contentcomparer/) { get; } |  |
| [DoubleSided](../../aspose.cad.fileformats.glb.materials/materialbuilder/doublesided/) { get; set; } | 获取或设置一个值，指示是否必须从两侧渲染三角形。 |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [IndexOfRefraction](../../aspose.cad.fileformats.glb.materials/materialbuilder/indexofrefraction/) { get; set; } |  |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| static [ReferenceComparer](../../aspose.cad.fileformats.glb.materials/materialbuilder/referencecomparer/) { get; } |  |
| [ShaderStyle](../../aspose.cad.fileformats.glb.materials/materialbuilder/shaderstyle/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [AreEqualByContent](../../aspose.cad.fileformats.glb.materials/materialbuilder/areequalbycontent/)(MaterialBuilder, MaterialBuilder) |  |
| [Clone](../../aspose.cad.fileformats.glb.materials/materialbuilder/clone/)() |  |
| static [CreateDefault](../../aspose.cad.fileformats.glb.materials/materialbuilder/createdefault/)() |  |
| [GetChannel](../../aspose.cad.fileformats.glb.materials/materialbuilder/getchannel/#getchannel)(KnownChannel) |  |
| [GetChannel](../../aspose.cad.fileformats.glb.materials/materialbuilder/getchannel/#getchannel_1)(string) |  |
| static [GetContentHashCode](../../aspose.cad.fileformats.glb.materials/materialbuilder/getcontenthashcode/)(MaterialBuilder) |  |
| [RemoveChannel](../../aspose.cad.fileformats.glb.materials/materialbuilder/removechannel/)(KnownChannel) |  |
| [UseChannel](../../aspose.cad.fileformats.glb.materials/materialbuilder/usechannel/#usechannel)(KnownChannel) |  |
| [UseChannel](../../aspose.cad.fileformats.glb.materials/materialbuilder/usechannel/#usechannel_1)(string) |  |
| [WithAlpha](../../aspose.cad.fileformats.glb.materials/materialbuilder/withalpha/)(AlphaMode, float) |  |
| [WithBaseColor](../../aspose.cad.fileformats.glb.materials/materialbuilder/withbasecolor/#withbasecolor)(Vector4) |  |
| [WithBaseColor](../../aspose.cad.fileformats.glb.materials/materialbuilder/withbasecolor/#withbasecolor_1)(ImageBuilder, Vector4?) |  |
| [WithChannelImage](../../aspose.cad.fileformats.glb.materials/materialbuilder/withchannelimage/#withchannelimage)(KnownChannel, ImageBuilder) |  |
| [WithChannelImage](../../aspose.cad.fileformats.glb.materials/materialbuilder/withchannelimage/#withchannelimage_1)(string, ImageBuilder) |  |
| [WithChannelParam](../../aspose.cad.fileformats.glb.materials/materialbuilder/withchannelparam/)(KnownChannel, KnownProperty, object) |  |
| [WithClearCoat](../../aspose.cad.fileformats.glb.materials/materialbuilder/withclearcoat/)(ImageBuilder, float) |  |
| [WithClearCoatNormal](../../aspose.cad.fileformats.glb.materials/materialbuilder/withclearcoatnormal/)(ImageBuilder) |  |
| [WithClearCoatRoughness](../../aspose.cad.fileformats.glb.materials/materialbuilder/withclearcoatroughness/)(ImageBuilder, float) |  |
| [WithDoubleSide](../../aspose.cad.fileformats.glb.materials/materialbuilder/withdoubleside/)(bool) |  |
| [WithEmissive](../../aspose.cad.fileformats.glb.materials/materialbuilder/withemissive/#withemissive)(Vector3, float) |  |
| [WithEmissive](../../aspose.cad.fileformats.glb.materials/materialbuilder/withemissive/#withemissive_1)(ImageBuilder, Vector3?, float) |  |
| [WithFallback](../../aspose.cad.fileformats.glb.materials/materialbuilder/withfallback/)(MaterialBuilder) | 为当前 `MaterialBuilder` 定义一个回退的 `MaterialBuilder` 实例。 |
| [WithIridiscence](../../aspose.cad.fileformats.glb.materials/materialbuilder/withiridiscence/)(ImageBuilder, float, float) |  |
| [WithIridiscenceThickness](../../aspose.cad.fileformats.glb.materials/materialbuilder/withiridiscencethickness/)(ImageBuilder, float, float) |  |
| [WithMetallicRoughness](../../aspose.cad.fileformats.glb.materials/materialbuilder/withmetallicroughness/#withmetallicroughness)(float?, float?) |  |
| [WithMetallicRoughness](../../aspose.cad.fileformats.glb.materials/materialbuilder/withmetallicroughness/#withmetallicroughness_1)(ImageBuilder, float?, float?) |  |
| [WithMetallicRoughnessFallback](../../aspose.cad.fileformats.glb.materials/materialbuilder/withmetallicroughnessfallback/)(ImageBuilder, Vector4?, ImageBuilder, float?, float?) |  |
| [WithMetallicRoughnessShader](../../aspose.cad.fileformats.glb.materials/materialbuilder/withmetallicroughnessshader/)() | 将 [`ShaderStyle`](./shaderstyle/) 设置为使用 [`SHADERPBRMETALLICROUGHNESS`](./shaderpbrmetallicroughness/)。 |
| [WithNormal](../../aspose.cad.fileformats.glb.materials/materialbuilder/withnormal/)(ImageBuilder, float) |  |
| [WithOcclusion](../../aspose.cad.fileformats.glb.materials/materialbuilder/withocclusion/)(ImageBuilder, float) |  |
| [WithShader](../../aspose.cad.fileformats.glb.materials/materialbuilder/withshader/)(string) | 设置 [`ShaderStyle`](./shaderstyle/)。 |
| [WithSpecularColor](../../aspose.cad.fileformats.glb.materials/materialbuilder/withspecularcolor/)(ImageBuilder, Vector3?) |  |
| [WithSpecularFactor](../../aspose.cad.fileformats.glb.materials/materialbuilder/withspecularfactor/)(ImageBuilder, float) |  |
| [WithTransmission](../../aspose.cad.fileformats.glb.materials/materialbuilder/withtransmission/)(ImageBuilder, float) |  |
| [WithUnlitShader](../../aspose.cad.fileformats.glb.materials/materialbuilder/withunlitshader/)() | 将 [`ShaderStyle`](./shaderstyle/) 设置为使用 [`SHADERUNLIT`](./shaderunlit/)。 |
| [WithVolumeAttenuation](../../aspose.cad.fileformats.glb.materials/materialbuilder/withvolumeattenuation/)(Vector3, float) |  |
| [WithVolumeThickness](../../aspose.cad.fileformats.glb.materials/materialbuilder/withvolumethickness/)(ImageBuilder, float) |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SHADERPBRMETALLICROUGHNESS](../../aspose.cad.fileformats.glb.materials/materialbuilder/shaderpbrmetallicroughness/) |  |
| const [SHADERPBRSPECULARGLOSSINESS](../../aspose.cad.fileformats.glb.materials/materialbuilder/shaderpbrspecularglossiness/) |  |
| const [SHADERUNLIT](../../aspose.cad.fileformats.glb.materials/materialbuilder/shaderunlit/) |  |

### 另请参阅

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Materials](../../aspose.cad.fileformats.glb.materials/)
* assembly [Aspose.CAD](../../)

