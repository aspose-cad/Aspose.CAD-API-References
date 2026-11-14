---
title: "ContentTransformer 类"
linktitle: "ContentTransformer"
articleTitle: "ContentTransformer"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.ContentTransformer 类。表示内容的变换。对底层内容对象（通常...）应用变换。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb.scenes/contenttransformer/"
keywords: "ContentTransformer, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ContentTransformer class

表示 [`Content`](../instancebuilder/content/) 的变换。

对底层内容对象（通常是网格、相机或灯光）应用变换。

```csharp
public abstract class ContentTransformer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Extras](../../aspose.cad.fileformats.glb.scenes/contenttransformer/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [HasRenderableContent](../../aspose.cad.fileformats.glb.scenes/contenttransformer/hasrenderablecontent/) { get; } | 获取一个值，指示 Content 是否实现了 `IRenderableContent` |
| [Morphings](../../aspose.cad.fileformats.glb.scenes/contenttransformer/morphings/) { get; } |  |
| abstract [Name](../../aspose.cad.fileformats.glb.scenes/contenttransformer/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [DeepClone](../../aspose.cad.fileformats.glb.scenes/contenttransformer/deepclone/)(DeepCloneContext) |  |
| abstract [GetArmatureRoot](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getarmatureroot/)() | 如果此 `ContentTransformer` 使用 [`NodeBuilder`](../nodebuilder/) 骨架，则返回该骨架的根节点。 |
| [GetCameraAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getcameraasset/)() | 如果此 `ContentTransformer` 包含一个 [`CameraBuilder`](../camerabuilder/) |
| [GetLightAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getlightasset/)() | 如果此 `ContentTransformer` 包含一个 [`LightBuilder`](../lightbuilder/) |
| abstract [GetPoseWorldMatrix](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getposeworldmatrix/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/#usemorphing)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/#usemorphing_1)(string) |  |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| struct [DeepCloneContext](../../aspose.cad.fileformats.glb.scenes/contenttransformer.deepclonecontext) |  |

## 备注

基类：
[`FixedTransformer`](../fixedtransformer/)
[`RigidTransformer`](../rigidtransformer/)
[`SkinnedTransformer`](../skinnedtransformer/)

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

