---
title: "AnimatableProperty<T> 类"
linktitle: "AnimatableProperty<T>"
articleTitle: "AnimatableProperty<T>"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Animations.AnimatableProperty 类。表示可以使用 ICurveSampler 动画的属性值。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.animations/animatableproperty-1/"
keywords: "AnimatableProperty<T>, Aspose.CAD.FileFormats.GLB.Animations, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## AnimatableProperty&lt;T&gt; class

表示可以使用 `ICurveSampler` 动画化的属性值。

```csharp
public class AnimatableProperty<T>
    where T : struct
```

| 参数 | 描述 |
| --- | --- |
| T | 该值的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsAnimated](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/isanimated/) { get; } |  |
| [Tracks](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/tracks/) { get; } |  |
| [Value](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/value/) { get; set; } | 获取或设置此实例的默认值。当动画被禁用或没有可用的动画轨道时，将返回此值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/clone/)() |  |
| [GetValueAt](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/getvalueat/)(string, float) | 在给定的 *offset* 和给定的 *track* 上评估此 `AnimatableProperty` 的值。 |
| [RemoveTrack](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/removetrack/)(string) | 移除动画 *track*。 |
| [SetTrack](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/settrack/)(string, ICurveSampler&lt;T&gt;) | 为给定的轨道分配动画曲线。 |
| [SetValue](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/setvalue/)(params float[]) |  |
| [UseTrackBuilder](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/usetrackbuilder/)(string) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Animations](../../aspose.cad.fileformats.glb.animations/)
* assembly [Aspose.CAD](../../)

