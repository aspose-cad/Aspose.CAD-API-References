---
title: "SceneBuilder 类"
linktitle: "SceneBuilder"
articleTitle: "SceneBuilder"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.SceneBuilder 类。表示模型、相机和灯光的根场景。"
type: docs
weight: 150
url: "/net/aspose.cad.fileformats.glb.scenes/scenebuilder/"
keywords: "SceneBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneBuilder class

表示模型、相机和灯光的根场景。

```csharp
public class SceneBuilder : BaseBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SceneBuilder](scenebuilder/)(string) | 初始化 SceneBuilder 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [Instances](../../aspose.cad.fileformats.glb.scenes/scenebuilder/instances/) { get; } | 获取此场景中的所有实例。 |
| [Materials](../../aspose.cad.fileformats.glb.scenes/scenebuilder/materials/) { get; } | 获取此场景中所有网格共享的唯一材质引用。 |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera)(CameraBuilder, AffineTransform) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_1)(CameraBuilder, NodeBuilder) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_2)(CameraBuilder, Vector3, Vector3) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight)(LightBuilder, AffineTransform) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight_1)(LightBuilder, NodeBuilder) |  |
| [AddNode](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addnode/)(NodeBuilder) |  |
| [AddScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addscene/)(SceneBuilder, Matrix4x4) | 将实例从 *scene* 复制到此 `SceneBuilder` |
| [ApplyBasisTransform](../../aspose.cad.fileformats.glb.scenes/scenebuilder/applybasistransform/)(Matrix4x4, string) | 对这个 `SceneBuilder` 应用变换。 |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom)(GlbData) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_1)(IEnumerable&lt;Scene&gt;) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_2)(Scene) |  |
| [DeepClone](../../aspose.cad.fileformats.glb.scenes/scenebuilder/deepclone/)(bool) |  |
| [FindArmatures](../../aspose.cad.fileformats.glb.scenes/scenebuilder/findarmatures/)() | 获取此 `SceneBuilder` 使用的所有唯一骨架。 |
| static [LoadAllScenes](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loadallscenes/)(string, ReadSettings) |  |
| static [LoadDefaultScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loaddefaultscene/)(string, ReadSettings) |  |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2)() | 将此 `SceneBuilder` 实例转换为 [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) 实例。 |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_1)(SceneBuilderSchema2Settings) | 将此 `SceneBuilder` 实例转换为 [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) 实例。 |
| static [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_2)(IEnumerable&lt;SceneBuilder&gt;, SceneBuilderSchema2Settings) | 将一组 `SceneBuilder` 实例转换为单个 [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) 实例。 |

### 另请参阅

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

