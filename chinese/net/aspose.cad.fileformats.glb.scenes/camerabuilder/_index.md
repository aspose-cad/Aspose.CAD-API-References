---
title: "CameraBuilder 类"
linktitle: "CameraBuilder"
articleTitle: "CameraBuilder"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.CameraBuilder 类。表示相机对象。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.scenes/camerabuilder/"
keywords: "CameraBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CameraBuilder class

表示相机对象。

```csharp
public abstract class CameraBuilder : BaseBuilder
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [IsValid](../../aspose.cad.fileformats.glb.scenes/camerabuilder/isvalid/) { get; } | 获取一个值，指示相机参数是否正确。 |
| static [LocalDirection](../../aspose.cad.fileformats.glb.scenes/camerabuilder/localdirection/) { get; } |  |
| [Matrix](../../aspose.cad.fileformats.glb.scenes/camerabuilder/matrix/) { get; } | 获取相机参数的投影矩阵。 |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [ZFar](../../aspose.cad.fileformats.glb.scenes/camerabuilder/zfar/) { get; set; } | 获取或设置 Z 轴上的远平面距离。 |
| [ZNear](../../aspose.cad.fileformats.glb.scenes/camerabuilder/znear/) { get; set; } | 获取或设置 Z 轴上近裁剪面的距离。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [Clone](../../aspose.cad.fileformats.glb.scenes/camerabuilder/clone/)() |  |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [Orthographic](../../aspose.cad.fileformats.glb.scenes/camerabuilder.orthographic) |  |
| class [Perspective](../../aspose.cad.fileformats.glb.scenes/camerabuilder.perspective) |  |

## 备注

派生类型有：

 - [`Orthographic`](../camerabuilder.orthographic/)

 - [`Perspective`](../camerabuilder.perspective/)

### 另请参阅

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

