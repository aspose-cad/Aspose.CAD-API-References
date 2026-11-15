---
title: "Node.GetWorldMatrix"
linktitle: "GetWorldMatrix"
articleTitle: "GetWorldMatrix"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Node. Возвращает world matrix этого узла в заданной анимации в указанное время."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.glb/node/getworldmatrix/"
product_version: "26.9"
---
## Node.GetWorldMatrix method

Получает мировую матрицу этого node в заданной анимации в указанное время.

```csharp
public Matrix4x4 GetWorldMatrix(Animation animation, float time)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| анимация | Анимация | анимацию для выборки. |
| время | Single | смещение времени внутри анимации. |

### Возвращаемое значение

выборочный transform.

## Примечания

Это удобный метод, но он медленный, лучше кэшировать [`GetCurveSamplers`](../getcurvesamplers/).

### См. также

* class [Animation](../../animation/)
* class [Node](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

