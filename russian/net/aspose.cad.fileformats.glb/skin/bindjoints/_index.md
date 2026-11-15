---
title: "Skin.BindJoints"
linktitle: "BindJoints"
articleTitle: "BindJoints"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Skin."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/skin/bindjoints/"
product_version: "26.9"
---
## BindJoints(params Node[]) {#bindjoints}



```csharp
public void BindJoints(params Node[] joints)
```

### См. также

* class [Node](../../node/)
* class [Skin](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## BindJoints(Matrix4x4, params Node[]) {#bindjoints_1}

Привязывает костный арматурный [`Node`](../../node/) к соответствующей скинованной сетке.

```csharp
public void BindJoints(Matrix4x4 meshBindTransform, params Node[] joints)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| meshBindTransform | Matrix4x4 | Матрица мирового преобразования сетки во время привязки. |
| joints | Node[] | Коллекция суставов [`Node`](../../node/). |

## Примечания

Этот метод использует значение [`WorldMatrix`](../../node/worldmatrix/) каждого сустава для вычисления обратной матрицы привязки.

### См. также

* class [Node](../../node/)
* class [Skin](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

