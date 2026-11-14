---
title: "SkinnedTransformer 类"
linktitle: "SkinnedTransformer"
articleTitle: "SkinnedTransformer"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.SkinnedTransformer 类。表示内容的变换。将多个 NodeBuilder 的变换应用于底层..."
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.glb.scenes/skinnedtransformer/"
keywords: "SkinnedTransformer, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SkinnedTransformer class

表示 [`Content`](../instancebuilder/content/) 的变换。

将多个 [`NodeBuilder`](../nodebuilder/) 的变换应用于底层内容。

```csharp
public class SkinnedTransformer : ContentTransformer, #=zYrJm9M2cUuIf<Scene>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Extras](../../aspose.cad.fileformats.glb.scenes/skinnedtransformer/extras/) { get; set; } |  |
| [HasRenderableContent](../../aspose.cad.fileformats.glb.scenes/contenttransformer/hasrenderablecontent/) { get; } | 获取一个值，指示 Content 是否实现了 `IRenderableContent` |
| [Morphings](../../aspose.cad.fileformats.glb.scenes/contenttransformer/morphings/) { get; } |  |
| override [Name](../../aspose.cad.fileformats.glb.scenes/skinnedtransformer/name/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [DeepClone](../../aspose.cad.fileformats.glb.scenes/skinnedtransformer/deepclone/)(DeepCloneContext) |  |
| override [GetArmatureRoot](../../aspose.cad.fileformats.glb.scenes/skinnedtransformer/getarmatureroot/)() |  |
| [GetCameraAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getcameraasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`CameraBuilder`](../camerabuilder/) |
| [GetLightAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getlightasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`LightBuilder`](../lightbuilder/) |
| override [GetPoseWorldMatrix](../../aspose.cad.fileformats.glb.scenes/skinnedtransformer/getposeworldmatrix/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)(string) |  |

### 另请参阅

* class [ContentTransformer](../contenttransformer/)
* class [Scene](../../aspose.cad.fileformats.glb/scene/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

