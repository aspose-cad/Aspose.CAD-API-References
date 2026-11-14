---
title: "NodeBuilder 类"
linktitle: "NodeBuilder"
articleTitle: "NodeBuilder"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Scenes.NodeBuilder 类。定义骨架内的节点对象。"
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.glb.scenes/nodebuilder/"
keywords: "NodeBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## NodeBuilder class

定义装甲结构中的节点对象。

```csharp
public class NodeBuilder : BaseBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [NodeBuilder](nodebuilder/#constructor)() | 默认构造函数。 |
| [NodeBuilder](nodebuilder/#constructor_1)(string) | 初始化 NodeBuilder 类的新实例。 |
| [NodeBuilder](nodebuilder/#constructor_2)(string, JsonContent) | 初始化 NodeBuilder 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimationTracksNames](../../aspose.cad.fileformats.glb.scenes/nodebuilder/animationtracksnames/) { get; } |  |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | 获取或设置此对象的自定义数据。 |
| [HasAnimations](../../aspose.cad.fileformats.glb.scenes/nodebuilder/hasanimations/) { get; } | 获取一个值，指示此 `NodeBuilder` 是否具有动画。 |
| [LocalMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/localmatrix/) { get; set; } | 获取或设置此 `NodeBuilder` 的本地变换 Matrix4x4。 |
| [LocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/localtransform/) { get; set; } | 获取或设置此 `NodeBuilder` 的本地缩放、旋转和位移。 |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Parent](../../aspose.cad.fileformats.glb.scenes/nodebuilder/parent/) { get; } |  |
| [Root](../../aspose.cad.fileformats.glb.scenes/nodebuilder/root/) { get; } |  |
| [Rotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/rotation/) { get; } | 获取当前的旋转变换，若无则返回 null。 |
| [Scale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/scale/) { get; } | 获取当前的缩放变换，若无则返回 null。 |
| [Translation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/translation/) { get; } | 获取当前的位移变换，若无则返回 null。 |
| [VisualChildren](../../aspose.cad.fileformats.glb.scenes/nodebuilder/visualchildren/) { get; } |  |
| [WorldMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/worldmatrix/) { get; set; } | 获取或设置此 `NodeBuilder` 的世界变换 Matrix4x4。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddNode](../../aspose.cad.fileformats.glb.scenes/nodebuilder/addnode/)(NodeBuilder) |  |
| [CreateNode](../../aspose.cad.fileformats.glb.scenes/nodebuilder/createnode/)(string) |  |
| [DeepClone](../../aspose.cad.fileformats.glb.scenes/nodebuilder/deepclone/)() |  |
| static [Flatten](../../aspose.cad.fileformats.glb.scenes/nodebuilder/flatten/)(NodeBuilder) |  |
| [GetInverseBindMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getinversebindmatrix/)(Matrix4x4?) |  |
| [GetLocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getlocaltransform/)(string, float) |  |
| [GetWorldMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getworldmatrix/)(string, float) |  |
| static [IsValidArmature](../../aspose.cad.fileformats.glb.scenes/nodebuilder/isvalidarmature/)(IEnumerable&lt;NodeBuilder&gt;) | 检查关节集合是否可用于对网格进行蒙皮。 |
| [SetLocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/setlocaltransform/)(AffineTransform, bool) | 设置此节点的本地变换。可选地，可以防止子节点受到此节点变换更改的影响。 |
| [SetRotationTrack](../../aspose.cad.fileformats.glb.scenes/nodebuilder/setrotationtrack/)(string, ICurveSampler&lt;Quaternion&gt;) |  |
| [SetScaleTrack](../../aspose.cad.fileformats.glb.scenes/nodebuilder/setscaletrack/)(string, ICurveSampler&lt;Vector3&gt;) |  |
| [SetTranslationTrack](../../aspose.cad.fileformats.glb.scenes/nodebuilder/settranslationtrack/)(string, ICurveSampler&lt;Vector3&gt;) |  |
| [UseRotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/userotation/#userotation)() |  |
| [UseRotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/userotation/#userotation_1)(string) |  |
| [UseScale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/usescale/#usescale)() |  |
| [UseScale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/usescale/#usescale_1)(string) |  |
| [UseTranslation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/usetranslation/#usetranslation)() |  |
| [UseTranslation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/usetranslation/#usetranslation_1)(string) |  |
| [WithLocalRotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocalrotation/#withlocalrotation)(Quaternion) |  |
| [WithLocalRotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocalrotation/#withlocalrotation_1)(string, IReadOnlyDictionary&lt;float, Quaternion&gt;) |  |
| [WithLocalScale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocalscale/#withlocalscale)(Vector3) |  |
| [WithLocalScale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocalscale/#withlocalscale_1)(string, IReadOnlyDictionary&lt;float, Vector3&gt;) |  |
| [WithLocalTranslation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocaltranslation/#withlocaltranslation)(Vector3) |  |
| [WithLocalTranslation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/withlocaltranslation/#withlocaltranslation_1)(string, IReadOnlyDictionary&lt;float, Vector3&gt;) |  |

### 另请参阅

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

