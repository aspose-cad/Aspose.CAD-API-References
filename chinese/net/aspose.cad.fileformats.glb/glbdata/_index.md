---
title: "GlbData 类"
linktitle: "GlbData"
articleTitle: "GlbData"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.GlbData 类。glTF 资产的根对象。"
type: docs
weight: 200
url: "/net/aspose.cad.fileformats.glb/glbdata/"
keywords: "GlbData, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GlbData class

glTF 资源的根对象。

```csharp
public class GlbData : ExtraProperties
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Asset](../../aspose.cad.fileformats.glb/glbdata/asset/) { get; } |  |
| [DefaultScene](../../aspose.cad.fileformats.glb/glbdata/defaultscene/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [ExtensionsRequired](../../aspose.cad.fileformats.glb/glbdata/extensionsrequired/) { get; } |  |
| [ExtensionsUsed](../../aspose.cad.fileformats.glb/glbdata/extensionsused/) { get; } |  |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [IncompatibleExtensions](../../aspose.cad.fileformats.glb/glbdata/incompatibleextensions/) { get; } |  |
| [LogicalAccessors](../../aspose.cad.fileformats.glb/glbdata/logicalaccessors/) { get; } |  |
| [LogicalAnimations](../../aspose.cad.fileformats.glb/glbdata/logicalanimations/) { get; } |  |
| [LogicalBufferViews](../../aspose.cad.fileformats.glb/glbdata/logicalbufferviews/) { get; } |  |
| [LogicalBuffers](../../aspose.cad.fileformats.glb/glbdata/logicalbuffers/) { get; } |  |
| [LogicalCameras](../../aspose.cad.fileformats.glb/glbdata/logicalcameras/) { get; } |  |
| [LogicalImages](../../aspose.cad.fileformats.glb/glbdata/logicalimages/) { get; } |  |
| [LogicalMaterials](../../aspose.cad.fileformats.glb/glbdata/logicalmaterials/) { get; } |  |
| [LogicalMeshes](../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/) { get; } |  |
| [LogicalNodes](../../aspose.cad.fileformats.glb/glbdata/logicalnodes/) { get; } |  |
| [LogicalPunctualLights](../../aspose.cad.fileformats.glb/glbdata/logicalpunctuallights/) { get; } | 获取 [`PunctualLight`](../punctuallight/) 实例的集合。 |
| [LogicalScenes](../../aspose.cad.fileformats.glb/glbdata/logicalscenes/) { get; } |  |
| [LogicalSkins](../../aspose.cad.fileformats.glb/glbdata/logicalskins/) { get; } |  |
| [LogicalTextureSamplers](../../aspose.cad.fileformats.glb/glbdata/logicaltexturesamplers/) { get; } |  |
| [LogicalTextures](../../aspose.cad.fileformats.glb/glbdata/logicaltextures/) { get; } |  |
| [MeshQuantizationAllowed](../../aspose.cad.fileformats.glb/glbdata/meshquantizationallowed/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ApplyBasisTransform](../../aspose.cad.fileformats.glb/glbdata/applybasistransform/)(Matrix4x4, string) | 对模型的所有场景应用世界变换。 |
| [CalcMinMaxPoints](../../aspose.cad.fileformats.glb/glbdata/calcminmaxpoints/)(out Vector3, out Vector3) |  |
| [CreateAccessor](../../aspose.cad.fileformats.glb/glbdata/createaccessor/)(string) | 创建一个新的 [`Accessor`](../accessor/) 实例并将其添加到 LogicalAccessors。 |
| [CreateAnimation](../../aspose.cad.fileformats.glb/glbdata/createanimation/)(string) | 创建一个新的 [`Animation`](../animation/) 实例并将其添加到 [`LogicalAnimations`](./logicalanimations/)。 |
| [CreateBuffer](../../aspose.cad.fileformats.glb/glbdata/createbuffer/)(int) | 创建一个新的 [`Buffer`](../buffer/) 实例并将其添加到 [`LogicalBuffers`](./logicalbuffers/)。 |
| [CreateBufferView](../../aspose.cad.fileformats.glb/glbdata/createbufferview/)(int, int, BufferMode?) |  |
| [CreateCamera](../../aspose.cad.fileformats.glb/glbdata/createcamera/)(string) | 创建一个新的 [`Camera`](../camera/) 实例，并将其追加到 [`LogicalCameras`](./logicalcameras/)。 |
| [CreateImage](../../aspose.cad.fileformats.glb/glbdata/createimage/)(string) | 创建一个新的 [`Image`](../../aspose.cad/image/) 实例，并将其追加到 [`LogicalImages`](./logicalimages/)。 |
| [CreateLogicalNode](../../aspose.cad.fileformats.glb/glbdata/createlogicalnode/)() |  |
| [CreateMaterial](../../aspose.cad.fileformats.glb/glbdata/creatematerial/)(string) | 创建一个新的 [`Material`](../material/) 实例并将其追加到 [`LogicalMaterials`](./logicalmaterials/)。 |
| [CreateMesh](../../aspose.cad.fileformats.glb/glbdata/createmesh/)(string) | 创建一个新的 [`Mesh`](../mesh/) 实例并将其追加到 [`LogicalMeshes`](./logicalmeshes/)。 |
| static [CreateModel](../../aspose.cad.fileformats.glb/glbdata/createmodel/)() | 创建一个新的 `GlbData` 实例。 |
| [CreatePunctualLight](../../aspose.cad.fileformats.glb/glbdata/createpunctuallight/#createpunctuallight)(PunctualLightType) | 创建一个新的 [`PunctualLight`](../punctuallight/) 实例并将其添加到 [`LogicalPunctualLights`](./logicalpunctuallights/)。 |
| [CreatePunctualLight](../../aspose.cad.fileformats.glb/glbdata/createpunctuallight/#createpunctuallight_1)(string, PunctualLightType) | 创建一个新的 [`PunctualLight`](../punctuallight/) 实例，并将其添加到 [`LogicalPunctualLights`](./logicalpunctuallights/)。 |
| [CreateSkin](../../aspose.cad.fileformats.glb/glbdata/createskin/)(string) | 创建一个新的 [`Skin`](../skin/) 实例并将其添加到 [`LogicalSkins`](./logicalskins/)。 |
| [DeepClone](../../aspose.cad.fileformats.glb/glbdata/deepclone/)() | 创建此 `GlbData` 实例的完整克隆。 |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetJsonPreview](../../aspose.cad.fileformats.glb/glbdata/getjsonpreview/)() | 获取此 `GlbData` 的 JSON 文档。 |
| static [GetSatellitePaths](../../aspose.cad.fileformats.glb/glbdata/getsatellitepaths/)(string) | 获取给定 glTF 文件的卫星/依赖文件列表。包括二进制块和纹理图像。 |
| [IsolateMemory](../../aspose.cad.fileformats.glb/glbdata/isolatememory/)() | 刷新所有内部内存缓冲区。 |
| static [Load](../../aspose.cad.fileformats.glb/glbdata/load/)(Stream, ReadSettings) |  |
| static [LoadGlbImage](../../aspose.cad.fileformats.glb/glbdata/loadglbimage/)(string, ReadSettings) | 从指向 GLB 或 GLTF 文件的路径读取 `GlbData` 实例 |
| [MergeBuffers](../../aspose.cad.fileformats.glb/glbdata/mergebuffers/#mergebuffers)() | 将所有 [`LogicalBuffers`](./logicalbuffers/) 实例合并为一个大的实例。 |
| [MergeBuffers](../../aspose.cad.fileformats.glb/glbdata/mergebuffers/#mergebuffers_1)(int) | 将所有 [`LogicalBuffers`](./logicalbuffers/) 实例合并为 *maxSize* 大小的缓冲区。 |
| [MergeImages](../../aspose.cad.fileformats.glb/glbdata/mergeimages/)() | 将所有 [`LogicalImages`](./logicalimages/) 内容转移到 [`BufferView`](../bufferview/) 实例中 |
| static [ParseGLB](../../aspose.cad.fileformats.glb/glbdata/parseglb/)(ArraySegment&lt;byte&gt;, ReadSettings) | 从表示 GLB 文件的字节数组解析出一个 `GlbData` 实例 |
| static [ReadGLB](../../aspose.cad.fileformats.glb/glbdata/readglb/)(Stream, ReadSettings) | 从表示 GLB 文件的流读取 `GlbData` 实例 |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [Save](../../aspose.cad.fileformats.glb/glbdata/save/)(string, WriteSettings) | 根据 *filePath* 的扩展名，将此 `GlbData` 写入 GLTF 或 GLB 文件。 |
| [SaveGLB](../../aspose.cad.fileformats.glb/glbdata/saveglb/)(string, WriteSettings) | 将此 `GlbData` 以 GLB 格式写入文件。 |
| [SaveGLTF](../../aspose.cad.fileformats.glb/glbdata/savegltf/#savegltf)(string, WriteSettings) | 将此 `GlbData` 以 GLTF 格式写入文件。 |
| [SaveGLTF](../../aspose.cad.fileformats.glb/glbdata/savegltf/#savegltf_1)(Stream, Stream, Stream, string, WriteSettings) |  |
| [SaveGlbImage](../../aspose.cad.fileformats.glb/glbdata/saveglbimage/)(Stream, WriteSettings) |  |
| [SaveGltfImage](../../aspose.cad.fileformats.glb/glbdata/savegltfimage/)(Stream, WriteSettings) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseBuffer](../../aspose.cad.fileformats.glb/glbdata/usebuffer/)(byte[]) | 在 [`LogicalBuffers`](./logicalbuffers/) 处创建或复用一个 [`Buffer`](../buffer/) 实例。 |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview)(ArraySegment&lt;byte&gt;, int, BufferMode?) | 在 [`LogicalBufferViews`](./logicalbufferviews/) 处创建或复用一个 [`BufferView`](../bufferview/) 实例。 |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview_1)(Buffer, int, int?, int, BufferMode?) | 在 [`LogicalBufferViews`](./logicalbufferviews/) 处创建或复用一个 [`BufferView`](../bufferview/) 实例。 |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview_2)(byte[], int, int?, int, BufferMode?) | 在 [`LogicalBufferViews`](./logicalbufferviews/) 处创建或复用一个 [`BufferView`](../bufferview/) 实例。 |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |
| [UseImage](../../aspose.cad.fileformats.glb/glbdata/useimage/)(MemoryImage) | 创建或复用一个 [`Image`](../../aspose.cad/image/) 实例。 |
| [UseScene](../../aspose.cad.fileformats.glb/glbdata/usescene/#usescene)(int) | 在 [`LogicalScenes`](./logicalscenes/) 处创建或复用一个 [`Scene`](../scene/) 实例。 |
| [UseScene](../../aspose.cad.fileformats.glb/glbdata/usescene/#usescene_1)(string) | 在 [`LogicalScenes`](./logicalscenes/) 处创建或复用一个具有相同 *name* 的 [`Scene`](../scene/) 实例。 |
| [UseTexture](../../aspose.cad.fileformats.glb/glbdata/usetexture/#usetexture)(ImageGlb, TextureSampler) | 在 [`LogicalTextures`](./logicaltextures/) 处创建或复用一个 [`Texture`](../texture/) 实例。 |
| [UseTexture](../../aspose.cad.fileformats.glb/glbdata/usetexture/#usetexture_1)(ImageGlb, ImageGlb, TextureSampler) | 在 [`LogicalTextures`](./logicaltextures/) 处创建或复用一个 [`Texture`](../texture/) 实例。 |
| [UseTextureSampler](../../aspose.cad.fileformats.glb/glbdata/usetexturesampler/)(TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) | 在 [`LogicalTextureSamplers`](./logicaltexturesamplers/) 处创建或复用一个 [`TextureSampler`](../texturesampler/) 实例。 |
| static [Validate](../../aspose.cad.fileformats.glb/glbdata/validate/)(string) |  |
| [WriteGLB](../../aspose.cad.fileformats.glb/glbdata/writeglb/#writeglb)(WriteSettings) | 以 GLB 格式将此 `GlbData` 写入字节数组。 |
| [WriteGLB](../../aspose.cad.fileformats.glb/glbdata/writeglb/#writeglb_1)(Stream, WriteSettings) | 以 GLB 格式将此 `GlbData` 写入流。 |

### 另请参阅

* class [ExtraProperties](../extraproperties/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

