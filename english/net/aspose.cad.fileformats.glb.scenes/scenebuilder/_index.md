---
title: "SceneBuilder Class"
linktitle: "SceneBuilder"
articleTitle: "SceneBuilder"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Scenes.SceneBuilder class. Represents the root scene for models, cameras and lights."
type: docs
weight: 150
url: "/net/aspose.cad.fileformats.glb.scenes/scenebuilder/"
keywords: "SceneBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneBuilder class

Represents the root scene for models, cameras and lights.

```csharp
public class SceneBuilder : BaseBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [SceneBuilder](scenebuilder/)(string) | Initializes a new instance of the SceneBuilder class. |

## Properties

| Name | Description |
| --- | --- |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | Gets or sets the custom data of this object. |
| [Instances](../../aspose.cad.fileformats.glb.scenes/scenebuilder/instances/) { get; } | Gets all the instances in this scene. |
| [Materials](../../aspose.cad.fileformats.glb.scenes/scenebuilder/materials/) { get; } | Gets all the unique material references shared by all the meshes in this scene. |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | Gets or sets the display text name, or null. |

## Methods

| Name | Description |
| --- | --- |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera)(CameraBuilder, AffineTransform) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_1)(CameraBuilder, NodeBuilder) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_2)(CameraBuilder, Vector3, Vector3) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight)(LightBuilder, AffineTransform) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight_1)(LightBuilder, NodeBuilder) |  |
| [AddNode](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addnode/)(NodeBuilder) |  |
| [AddScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addscene/)(SceneBuilder, Matrix4x4) | Copies the instances from *scene* to this `SceneBuilder` |
| [ApplyBasisTransform](../../aspose.cad.fileformats.glb.scenes/scenebuilder/applybasistransform/)(Matrix4x4, string) | Applies a tranform the this `SceneBuilder`. |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom)(GlbData) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_1)(IEnumerable&lt;Scene&gt;) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_2)(Scene) |  |
| [DeepClone](../../aspose.cad.fileformats.glb.scenes/scenebuilder/deepclone/)(bool) |  |
| [FindArmatures](../../aspose.cad.fileformats.glb.scenes/scenebuilder/findarmatures/)() | Gets all the unique armatures used by this `SceneBuilder`. |
| static [LoadAllScenes](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loadallscenes/)(string, ReadSettings) |  |
| static [LoadDefaultScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loaddefaultscene/)(string, ReadSettings) |  |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2)() | Converts this `SceneBuilder` instance into a [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) instance. |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_1)(SceneBuilderSchema2Settings) | Converts this `SceneBuilder` instance into a [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) instance. |
| static [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_2)(IEnumerable&lt;SceneBuilder&gt;, SceneBuilderSchema2Settings) | Converts a collection of `SceneBuilder` instances to a single [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/) instance. |

### See Also

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

