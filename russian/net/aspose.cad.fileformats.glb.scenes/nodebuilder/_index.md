---
title: "Класс NodeBuilder"
linktitle: "NodeBuilder"
articleTitle: "NodeBuilder"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Scenes.NodeBuilder класс. Определяет объект узла внутри арматуры."
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.glb.scenes/nodebuilder/"
keywords: "NodeBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## NodeBuilder class

Определяет объект узла внутри арматуры.

```csharp
public class NodeBuilder : BaseBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NodeBuilder](nodebuilder/#constructor)() | Конструктор по умолчанию. |
| [NodeBuilder](nodebuilder/#constructor_1)(string) | Инициализирует новый экземпляр класса NodeBuilder. |
| [NodeBuilder](nodebuilder/#constructor_2)(string, JsonContent) | Инициализирует новый экземпляр класса NodeBuilder. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AnimationTracksNames](../../aspose.cad.fileformats.glb.scenes/nodebuilder/animationtracksnames/) { get; } |  |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | Получает или задает пользовательские данные этого объекта. |
| [HasAnimations](../../aspose.cad.fileformats.glb.scenes/nodebuilder/hasanimations/) { get; } | Получает значение, указывающее, имеет ли этот `NodeBuilder` анимацию. |
| [LocalMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/localmatrix/) { get; set; } | Получает или задает локальное преобразование Matrix4x4 этого `NodeBuilder`. |
| [LocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/localtransform/) { get; set; } | Получает или задает локальные масштаб, вращение и трансляцию этого `NodeBuilder`. |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Parent](../../aspose.cad.fileformats.glb.scenes/nodebuilder/parent/) { get; } |  |
| [Root](../../aspose.cad.fileformats.glb.scenes/nodebuilder/root/) { get; } |  |
| [Rotation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/rotation/) { get; } | Получает текущее преобразование вращения или null. |
| [Scale](../../aspose.cad.fileformats.glb.scenes/nodebuilder/scale/) { get; } | Получает текущее преобразование масштаба или null. |
| [Translation](../../aspose.cad.fileformats.glb.scenes/nodebuilder/translation/) { get; } | Получает текущее преобразование трансляции или null. |
| [VisualChildren](../../aspose.cad.fileformats.glb.scenes/nodebuilder/visualchildren/) { get; } |  |
| [WorldMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/worldmatrix/) { get; set; } | Получает или задает мировое преобразование Matrix4x4 этого `NodeBuilder`. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddNode](../../aspose.cad.fileformats.glb.scenes/nodebuilder/addnode/)(NodeBuilder) |  |
| [CreateNode](../../aspose.cad.fileformats.glb.scenes/nodebuilder/createnode/)(string) |  |
| [DeepClone](../../aspose.cad.fileformats.glb.scenes/nodebuilder/deepclone/)() |  |
| static [Flatten](../../aspose.cad.fileformats.glb.scenes/nodebuilder/flatten/)(NodeBuilder) |  |
| [GetInverseBindMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getinversebindmatrix/)(Matrix4x4?) |  |
| [GetLocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getlocaltransform/)(string, float) |  |
| [GetWorldMatrix](../../aspose.cad.fileformats.glb.scenes/nodebuilder/getworldmatrix/)(string, float) |  |
| static [IsValidArmature](../../aspose.cad.fileformats.glb.scenes/nodebuilder/isvalidarmature/)(IEnumerable&lt;NodeBuilder&gt;) | Проверяет, может ли коллекция суставов использоваться для скиннинга сетки. |
| [SetLocalTransform](../../aspose.cad.fileformats.glb.scenes/nodebuilder/setlocaltransform/)(AffineTransform, bool) | Устанавливает локальное преобразование этого узла. При желании можно сохранить дочерние элементы от воздействия изменения преобразования этого узла. |
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

### См. также

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

