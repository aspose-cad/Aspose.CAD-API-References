---
title: "FixedTransformer 类"
linktitle: "FixedTransformer"
articleTitle: "FixedTransformer"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.FixedTransformer 类。表示 Content 的变换。对底层内容应用固定的 `Matrix4x4` 变换。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.glb.scenes/fixedtransformer/"
keywords: "FixedTransformer, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## FixedTransformer class

表示 [`Content`](../instancebuilder/content/) 的变换。

对底层内容应用固定的 `Matrix4x4` 变换。

```csharp
public class FixedTransformer : ContentTransformer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChildTransform](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/childtransform/) { get; set; } |  |
| override [Extras](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/extras/) { get; set; } |  |
| [HasRenderableContent](../../aspose.cad.fileformats.glb.scenes/contenttransformer/hasrenderablecontent/) { get; } | 获取一个值，指示 Content 是否实现了 `IRenderableContent` |
| [Morphings](../../aspose.cad.fileformats.glb.scenes/contenttransformer/morphings/) { get; } |  |
| override [Name](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/name/) { get; set; } |  |
| [ParentNode](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/parentnode/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [DeepClone](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/deepclone/)(DeepCloneContext) |  |
| override [GetArmatureRoot](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/getarmatureroot/)() |  |
| [GetCameraAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getcameraasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`CameraBuilder`](../camerabuilder/) |
| [GetLightAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getlightasset/)() | 如果此 [`ContentTransformer`](../contenttransformer/) 包含一个 [`LightBuilder`](../lightbuilder/) |
| override [GetPoseWorldMatrix](../../aspose.cad.fileformats.glb.scenes/fixedtransformer/getposeworldmatrix/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/)(string) |  |

### 另请参阅

* class [ContentTransformer](../contenttransformer/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

