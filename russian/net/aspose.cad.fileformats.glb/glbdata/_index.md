---
title: "GlbData Класс"
linktitle: "GlbData"
articleTitle: "GlbData"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.GlbData класс. Корневой объект для glTF‑активов."
type: docs
weight: 200
url: "/net/aspose.cad.fileformats.glb/glbdata/"
keywords: "GlbData, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GlbData class

Корневой объект ресурса glTF.

```csharp
public class GlbData : ExtraProperties
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Asset](../../aspose.cad.fileformats.glb/glbdata/asset/) { get; } |  |
| [DefaultScene](../../aspose.cad.fileformats.glb/glbdata/defaultscene/) { get; set; } |  |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [ExtensionsRequired](../../aspose.cad.fileformats.glb/glbdata/extensionsrequired/) { get; } |  |
| [ExtensionsUsed](../../aspose.cad.fileformats.glb/glbdata/extensionsused/) { get; } |  |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
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
| [LogicalPunctualLights](../../aspose.cad.fileformats.glb/glbdata/logicalpunctuallights/) { get; } | Получает коллекцию экземпляров [`PunctualLight`](../punctuallight/). |
| [LogicalScenes](../../aspose.cad.fileformats.glb/glbdata/logicalscenes/) { get; } |  |
| [LogicalSkins](../../aspose.cad.fileformats.glb/glbdata/logicalskins/) { get; } |  |
| [LogicalTextureSamplers](../../aspose.cad.fileformats.glb/glbdata/logicaltexturesamplers/) { get; } |  |
| [LogicalTextures](../../aspose.cad.fileformats.glb/glbdata/logicaltextures/) { get; } |  |
| [MeshQuantizationAllowed](../../aspose.cad.fileformats.glb/glbdata/meshquantizationallowed/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyBasisTransform](../../aspose.cad.fileformats.glb/glbdata/applybasistransform/)(Matrix4x4, string) | Применяет мировое преобразование ко всем сценам модели. |
| [CalcMinMaxPoints](../../aspose.cad.fileformats.glb/glbdata/calcminmaxpoints/)(out Vector3, out Vector3) |  |
| [CreateAccessor](../../aspose.cad.fileformats.glb/glbdata/createaccessor/)(string) | Создаёт новый экземпляр [`Accessor`](../accessor/) и добавляет его в LogicalAccessors. |
| [CreateAnimation](../../aspose.cad.fileformats.glb/glbdata/createanimation/)(string) | Создаёт новый экземпляр [`Animation`](../animation/) и добавляет его в [`LogicalAnimations`](./logicalanimations/). |
| [CreateBuffer](../../aspose.cad.fileformats.glb/glbdata/createbuffer/)(int) | Создаёт новый экземпляр [`Buffer`](../buffer/) и добавляет его в [`LogicalBuffers`](./logicalbuffers/). |
| [CreateBufferView](../../aspose.cad.fileformats.glb/glbdata/createbufferview/)(int, int, BufferMode?) |  |
| [CreateCamera](../../aspose.cad.fileformats.glb/glbdata/createcamera/)(string) | Создаёт новый экземпляр [`Camera`](../camera/) и добавляет его в [`LogicalCameras`](./logicalcameras/). |
| [CreateImage](../../aspose.cad.fileformats.glb/glbdata/createimage/)(string) | Создаёт новый экземпляр [`Image`](../../aspose.cad/image/) и добавляет его в [`LogicalImages`](./logicalimages/). |
| [CreateLogicalNode](../../aspose.cad.fileformats.glb/glbdata/createlogicalnode/)() |  |
| [CreateMaterial](../../aspose.cad.fileformats.glb/glbdata/creatematerial/)(string) | Создаёт новый экземпляр [`Material`](../material/) и добавляет его в [`LogicalMaterials`](./logicalmaterials/). |
| [CreateMesh](../../aspose.cad.fileformats.glb/glbdata/createmesh/)(string) | Создаёт новый экземпляр [`Mesh`](../mesh/) и добавляет его в [`LogicalMeshes`](./logicalmeshes/). |
| static [CreateModel](../../aspose.cad.fileformats.glb/glbdata/createmodel/)() | Создаёт новый экземпляр `GlbData`. |
| [CreatePunctualLight](../../aspose.cad.fileformats.glb/glbdata/createpunctuallight/#createpunctuallight)(PunctualLightType) | Создаёт новый экземпляр [`PunctualLight`](../punctuallight/) и добавляет его в [`LogicalPunctualLights`](./logicalpunctuallights/). |
| [CreatePunctualLight](../../aspose.cad.fileformats.glb/glbdata/createpunctuallight/#createpunctuallight_1)(string, PunctualLightType) | Создаёт новый экземпляр [`PunctualLight`](../punctuallight/) и добавляет его в [`LogicalPunctualLights`](./logicalpunctuallights/). |
| [CreateSkin](../../aspose.cad.fileformats.glb/glbdata/createskin/)(string) | Создаёт новый экземпляр [`Skin`](../skin/) и добавляет его в [`LogicalSkins`](./logicalskins/). |
| [DeepClone](../../aspose.cad.fileformats.glb/glbdata/deepclone/)() | Создаёт полную копию этого экземпляра `GlbData`. |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [GetJsonPreview](../../aspose.cad.fileformats.glb/glbdata/getjsonpreview/)() | Получает JSON‑документ этого `GlbData`. |
| static [GetSatellitePaths](../../aspose.cad.fileformats.glb/glbdata/getsatellitepaths/)(string) | Получает список вспомогательных/зависимых файлов для указанного glTF‑файла. Включает бинарные блобы и текстурные изображения. |
| [IsolateMemory](../../aspose.cad.fileformats.glb/glbdata/isolatememory/)() | Обновляет все внутренние буферы памяти. |
| static [Load](../../aspose.cad.fileformats.glb/glbdata/load/)(Stream, ReadSettings) |  |
| static [LoadGlbImage](../../aspose.cad.fileformats.glb/glbdata/loadglbimage/)(string, ReadSettings) | Читает экземпляр `GlbData` из пути, указывающего на файл GLB или GLTF |
| [MergeBuffers](../../aspose.cad.fileformats.glb/glbdata/mergebuffers/#mergebuffers)() | Объединяет все экземпляры [`LogicalBuffers`](./logicalbuffers/) в один большой. |
| [MergeBuffers](../../aspose.cad.fileformats.glb/glbdata/mergebuffers/#mergebuffers_1)(int) | Объединяет все экземпляры [`LogicalBuffers`](./logicalbuffers/) в буферы размером *maxSize*. |
| [MergeImages](../../aspose.cad.fileformats.glb/glbdata/mergeimages/)() | Переносит всё содержимое [`LogicalImages`](./logicalimages/) в экземпляры [`BufferView`](../bufferview/). |
| static [ParseGLB](../../aspose.cad.fileformats.glb/glbdata/parseglb/)(ArraySegment&lt;byte&gt;, ReadSettings) | Разбирает экземпляр `GlbData` из массива байтов, представляющего файл GLB. |
| static [ReadGLB](../../aspose.cad.fileformats.glb/glbdata/readglb/)(Stream, ReadSettings) | Читает экземпляр `GlbData` из потока, представляющего файл GLB. |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [Save](../../aspose.cad.fileformats.glb/glbdata/save/)(string, WriteSettings) | Записывает этот `GlbData` в файл в формате GLTF или GLB в зависимости от расширения *filePath*. |
| [SaveGLB](../../aspose.cad.fileformats.glb/glbdata/saveglb/)(string, WriteSettings) | Записывает этот `GlbData` в файл в формате GLB. |
| [SaveGLTF](../../aspose.cad.fileformats.glb/glbdata/savegltf/#savegltf)(string, WriteSettings) | Записывает этот `GlbData` в файл в формате GLTF. |
| [SaveGLTF](../../aspose.cad.fileformats.glb/glbdata/savegltf/#savegltf_1)(Stream, Stream, Stream, string, WriteSettings) |  |
| [SaveGlbImage](../../aspose.cad.fileformats.glb/glbdata/saveglbimage/)(Stream, WriteSettings) |  |
| [SaveGltfImage](../../aspose.cad.fileformats.glb/glbdata/savegltfimage/)(Stream, WriteSettings) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseBuffer](../../aspose.cad.fileformats.glb/glbdata/usebuffer/)(byte[]) | Создаёт или переиспользует экземпляр [`Buffer`](../buffer/) в [`LogicalBuffers`](./logicalbuffers/). |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview)(ArraySegment&lt;byte&gt;, int, BufferMode?) | Создаёт или переиспользует экземпляр [`BufferView`](../bufferview/) в [`LogicalBufferViews`](./logicalbufferviews/). |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview_1)(Buffer, int, int?, int, BufferMode?) | Создаёт или переиспользует экземпляр [`BufferView`](../bufferview/) в [`LogicalBufferViews`](./logicalbufferviews/). |
| [UseBufferView](../../aspose.cad.fileformats.glb/glbdata/usebufferview/#usebufferview_2)(byte[], int, int?, int, BufferMode?) | Создаёт или переиспользует экземпляр [`BufferView`](../bufferview/) в [`LogicalBufferViews`](./logicalbufferviews/). |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |
| [UseImage](../../aspose.cad.fileformats.glb/glbdata/useimage/)(MemoryImage) | Создаёт или переиспользует экземпляр [`Image`](../../aspose.cad/image/). |
| [UseScene](../../aspose.cad.fileformats.glb/glbdata/usescene/#usescene)(int) | Создаёт или переиспользует экземпляр [`Scene`](../scene/) в [`LogicalScenes`](./logicalscenes/). |
| [UseScene](../../aspose.cad.fileformats.glb/glbdata/usescene/#usescene_1)(string) | Создаёт или переиспользует экземпляр [`Scene`](../scene/), имеющий то же *name*, в [`LogicalScenes`](./logicalscenes/). |
| [UseTexture](../../aspose.cad.fileformats.glb/glbdata/usetexture/#usetexture)(ImageGlb, TextureSampler) | Создаёт или переиспользует экземпляр [`Texture`](../texture/) в [`LogicalTextures`](./logicaltextures/). |
| [UseTexture](../../aspose.cad.fileformats.glb/glbdata/usetexture/#usetexture_1)(ImageGlb, ImageGlb, TextureSampler) | Создаёт или переиспользует экземпляр [`Texture`](../texture/) в [`LogicalTextures`](./logicaltextures/). |
| [UseTextureSampler](../../aspose.cad.fileformats.glb/glbdata/usetexturesampler/)(TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) | Создаёт или переиспользует экземпляр [`TextureSampler`](../texturesampler/) в [`LogicalTextureSamplers`](./logicaltexturesamplers/). |
| static [Validate](../../aspose.cad.fileformats.glb/glbdata/validate/)(string) |  |
| [WriteGLB](../../aspose.cad.fileformats.glb/glbdata/writeglb/#writeglb)(WriteSettings) | Записывает этот `GlbData` в массив байтов в формате GLB. |
| [WriteGLB](../../aspose.cad.fileformats.glb/glbdata/writeglb/#writeglb_1)(Stream, WriteSettings) | Записывает этот `GlbData` в поток в формате GLB. |

### См. также

* class [ExtraProperties](../extraproperties/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

