---
title: "Класс SceneBuilder"
linktitle: "SceneBuilder"
articleTitle: "SceneBuilder"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Scenes.SceneBuilder класс. Представляет корневую сцену для моделей, камер и источников света."
type: docs
weight: 150
url: "/net/aspose.cad.fileformats.glb.scenes/scenebuilder/"
keywords: "SceneBuilder, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneBuilder class

Представляет корневую сцену для моделей, камер и светильников.

```csharp
public class SceneBuilder : BaseBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SceneBuilder](scenebuilder/)(string) | Инициализирует новый экземпляр класса SceneBuilder. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Extras](../../aspose.cad.fileformats.glb.geometry/basebuilder/extras/) { get; set; } | Получает или задает пользовательские данные этого объекта. |
| [Instances](../../aspose.cad.fileformats.glb.scenes/scenebuilder/instances/) { get; } | Получает все экземпляры в этой сцене. |
| [Materials](../../aspose.cad.fileformats.glb.scenes/scenebuilder/materials/) { get; } | Получает все уникальные ссылки на материалы, общие для всех мешей в этой сцене. |
| [Name](../../aspose.cad.fileformats.glb.geometry/basebuilder/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera)(CameraBuilder, AffineTransform) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_1)(CameraBuilder, NodeBuilder) |  |
| [AddCamera](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addcamera/#addcamera_2)(CameraBuilder, Vector3, Vector3) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight)(LightBuilder, AffineTransform) |  |
| [AddLight](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addlight/#addlight_1)(LightBuilder, NodeBuilder) |  |
| [AddNode](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addnode/)(NodeBuilder) |  |
| [AddScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/addscene/)(SceneBuilder, Matrix4x4) | Копирует экземпляры из *scene* в этот `SceneBuilder` |
| [ApplyBasisTransform](../../aspose.cad.fileformats.glb.scenes/scenebuilder/applybasistransform/)(Matrix4x4, string) | Применяет преобразование к этому `SceneBuilder`. |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom)(GlbData) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_1)(IEnumerable&lt;Scene&gt;) |  |
| static [CreateFrom](../../aspose.cad.fileformats.glb.scenes/scenebuilder/createfrom/#createfrom_2)(Scene) |  |
| [DeepClone](../../aspose.cad.fileformats.glb.scenes/scenebuilder/deepclone/)(bool) |  |
| [FindArmatures](../../aspose.cad.fileformats.glb.scenes/scenebuilder/findarmatures/)() | Получает все уникальные арматуры, используемые этим `SceneBuilder`. |
| static [LoadAllScenes](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loadallscenes/)(string, ReadSettings) |  |
| static [LoadDefaultScene](../../aspose.cad.fileformats.glb.scenes/scenebuilder/loaddefaultscene/)(string, ReadSettings) |  |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2)() | Преобразует этот экземпляр `SceneBuilder` в экземпляр [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/). |
| [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_1)(SceneBuilderSchema2Settings) | Преобразует этот экземпляр `SceneBuilder` в экземпляр [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/). |
| static [ToGltf2](../../aspose.cad.fileformats.glb.scenes/scenebuilder/togltf2/#togltf2_2)(IEnumerable&lt;SceneBuilder&gt;, SceneBuilderSchema2Settings) | Преобразует коллекцию экземпляров `SceneBuilder` в один экземпляр [`GlbImage`](../../aspose.cad.fileformats.glb/glbimage/). |

### См. также

* class [BaseBuilder](../../aspose.cad.fileformats.glb.geometry/basebuilder/)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

