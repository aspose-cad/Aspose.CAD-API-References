---
title: "Класс SceneInstance"
linktitle: "SceneInstance"
articleTitle: "SceneInstance"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.Runtime.SceneInstance. Представляет конкретное и независимое состояние SceneTemplate."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/"
keywords: "SceneInstance, Aspose.CAD.FileFormats.GLB.Runtime, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## SceneInstance class

Представляет конкретное и независимое состояние `SceneTemplate`.

```csharp
public sealed class SceneInstance : IReadOnlyList<DrawableInstance>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Armature](../../aspose.cad.fileformats.glb.runtime/sceneinstance/armature/) { get; } |  |
| [Count](../../aspose.cad.fileformats.glb.runtime/sceneinstance/count/) { get; } |  |
| [Item](../../aspose.cad.fileformats.glb.runtime/sceneinstance/item/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetDrawableInstance](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/)(int) | Возвращает объект [`DrawableInstance`](../drawableinstance/), где: - Name — это имя данного drawable‑instance. Изначально это было имя [`Node`](../../aspose.cad.fileformats.glb/node/). - MeshIndex — логический индекс [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) в [`LogicalMeshes`](../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/). - Transform — `IGeometryTransform`, который может использоваться для преобразования [`Mesh`](../../aspose.cad.fileformats.glb/mesh/) в мировое пространство. |
| [GetEnumerator](../../aspose.cad.fileformats.glb.runtime/sceneinstance/getenumerator/)() |  |

### См. также

* struct [DrawableInstance](../drawableinstance/)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../)

