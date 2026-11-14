---
title: "RigidTransformer 类"
linktitle: "RigidTransformer"
articleTitle: "RigidTransformer"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.RigidTransformer 类。表示 Content 的变换。将单个 NodeBuilder 的变换应用于底层..."
type: docs
weight: 140
url: "/net/aspose.cad.fileformats.glb.scenes/rigidtransformer/"
keywords: "RigidTransformer, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## RigidTransformer class

表示 [`Content`](../instancebuilder/content/) 的变换。

将单个 [`NodeBuilder`](../nodebuilder/) 的变换应用于底层内容。

```csharp
public class RigidTransformer : ContentTransformer, #=zYrJm9M2cUuIf<Scene>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Extras](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/extras/) { get; set; } |  |
| [HasRenderableContent](../../aspose.cad.fileformats.glb.scenes/contenttransformer/hasrenderablecontent/) { get; } | 获取一个值，指示 Content 是否实现了 `IRenderableContent` |
| [Morphings](../../aspose.cad.fileformats.glb.scenes/contenttransformer/morphings/) { get; } |  |
| override [Name](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/name/) { get; set; } |  |
| [Transform](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/transform/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [DeepClone](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/deepclone/)(DeepCloneContext) |  |
| override [GetArmatureRoot](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/getarmatureroot/)() |  |
| [GetCameraAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getcameraasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`CameraBuilder`](../camerabuilder/) |
| [GetLightAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getlightasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`LightBuilder`](../lightbuilder/) |
| override [GetPoseWorldMatrix](../../aspose.cad.fileformats.glb.scenes/rigidtransformer/getposeworldmatrix/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)(string) |  |

### 另请参阅

* class [ContentTransformer](../contenttransformer/)
* class [Scene](../../aspose.cad.fileformats.glb/scene/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

