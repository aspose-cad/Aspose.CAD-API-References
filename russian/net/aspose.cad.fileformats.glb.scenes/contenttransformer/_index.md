---
title: "Класс ContentTransformer"
linktitle: "ContentTransformer"
articleTitle: "ContentTransformer"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Scenes.ContentTransformer класс. Представляет преобразование содержимого. Применяет преобразование к базовому объекту содержимого (обычно..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb.scenes/contenttransformer/"
keywords: "ContentTransformer, Aspose.CAD.FileFormats.GLB.Scenes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ContentTransformer class

Представляет преобразование [`Content`](../instancebuilder/content/).

Применяет преобразование к базовому объекту содержимого (обычно к сетке, камере или свету)

```csharp
public abstract class ContentTransformer
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [Extras](../../aspose.cad.fileformats.glb.scenes/contenttransformer/extras/) { get; set; } | Получает или задает пользовательские данные этого объекта. |
| [HasRenderableContent](../../aspose.cad.fileformats.glb.scenes/contenttransformer/hasrenderablecontent/) { get; } | Возвращает значение, указывающее, реализует ли Content интерфейс `IRenderableContent` |
| [Morphings](../../aspose.cad.fileformats.glb.scenes/contenttransformer/morphings/) { get; } |  |
| abstract [Name](../../aspose.cad.fileformats.glb.scenes/contenttransformer/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [DeepClone](../../aspose.cad.fileformats.glb.scenes/contenttransformer/deepclone/)(DeepCloneContext) |  |
| abstract [GetArmatureRoot](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getarmatureroot/)() | Если этот `ContentTransformer` использует арматуру [`NodeBuilder`](../nodebuilder/), он возвращает корень арматуры. |
| [GetCameraAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getcameraasset/)() | Если этот `ContentTransformer` содержит [`CameraBuilder`](../camerabuilder/) |
| [GetLightAsset](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getlightasset/)() | Если этот `ContentTransformer` содержит [`LightBuilder`](../lightbuilder/) |
| abstract [GetPoseWorldMatrix](../../aspose.cad.fileformats.glb.scenes/contenttransformer/getposeworldmatrix/)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/#usemorphing)() |  |
| [UseMorphing](../../aspose.cad.fileformats.glb.scenes/contenttransformer/usemorphing/#usemorphing_1)(string) |  |

## Другие члены

| Имя | Описание |
| --- | --- |
| struct [DeepCloneContext](../../aspose.cad.fileformats.glb.scenes/contenttransformer.deepclonecontext) |  |

## Примечания

Базовый класс для:
[`FixedTransformer`](../fixedtransformer/)
[`RigidTransformer`](../rigidtransformer/)
[`SkinnedTransformer`](../skinnedtransformer/)

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../)

