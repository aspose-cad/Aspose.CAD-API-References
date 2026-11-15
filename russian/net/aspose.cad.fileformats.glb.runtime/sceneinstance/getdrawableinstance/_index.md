---
title: "SceneInstance.GetDrawableInstance"
linktitle: "GetDrawableInstance"
articleTitle: "GetDrawableInstance"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод SceneInstance. Возвращает объект DrawableInstance, где: - Name — это имя данного drawable‑instance. Изначально это было имя Node. - MeshIndex i..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb.runtime/sceneinstance/getdrawableinstance/"
product_version: "26.9"
---
## SceneInstance.GetDrawableInstance method

Возвращает объект [`DrawableInstance`](../../drawableinstance/), где:
 - Name is the name of this drawable instance. Originally, it was the name of [`Node`](../../../aspose.cad.fileformats.glb/node/).
 - MeshIndex is the logical Index of a [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) in [`LogicalMeshes`](../../../aspose.cad.fileformats.glb/glbdata/logicalmeshes/).
 - Transform is an `IGeometryTransform` that can be used to transform the [`Mesh`](../../../aspose.cad.fileformats.glb/mesh/) into world space.

```csharp
public DrawableInstance GetDrawableInstance(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | Int32 | Индекс ссылки на drawable, от 0 до DrawableInstancesCount |

### Возвращаемое значение

[`DrawableInstance`](../../drawableinstance/) object.

### См. также

* struct [DrawableInstance](../../drawableinstance/)
* class [SceneInstance](../)
* namespace [Aspose.CAD.FileFormats.GLB.Runtime](../../../aspose.cad.fileformats.glb.runtime/)
* assembly [Aspose.CAD](../../../)

