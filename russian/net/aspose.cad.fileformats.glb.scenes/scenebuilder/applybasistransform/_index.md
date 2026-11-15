---
title: "SceneBuilder.ApplyBasisTransform"
linktitle: "ApplyBasisTransform"
articleTitle: "ApplyBasisTransform"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод SceneBuilder. Применяет преобразование к этому SceneBuilder."
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.glb.scenes/scenebuilder/applybasistransform/"
product_version: "26.9"
---
## SceneBuilder.ApplyBasisTransform method

Применяет преобразование к этому [`SceneBuilder`](../).

```csharp
public void ApplyBasisTransform(Matrix4x4 basisTransform, string basisNodeName = "BasisTransform")
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| basisTransform | Matrix4x4 | Преобразование для применения. |
| basisNodeName | String | Имя фиктивного корневого узла. |

## Примечания

В некоторых случаях невозможно применить
 *basisTransform* to the nodes in the scene.

В этих случаях создаётся фиктивный узел, и эти
узлы становятся дочерними этого фиктивного узла.
 
 

Этот метод полезен для переключения осей (Z‑UP или Y‑UP) и режима правой или левой системы координат.
 
 

Этот метод следует вызывать в конце, когда сцена полностью создана.

### См. также

* class [SceneBuilder](../)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../../)

