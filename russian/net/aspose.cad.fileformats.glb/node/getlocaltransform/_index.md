---
title: "Node.GetLocalTransform"
linktitle: "GetLocalTransform"
articleTitle: "GetLocalTransform"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Node. Получает локальное преобразование этого узла в заданной анимации в указанное время."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb/node/getlocaltransform/"
product_version: "26.9"
---
## Node.GetLocalTransform method

Получает локальное преобразование этого node в заданной анимации в указанное время.

```csharp
public AffineTransform GetLocalTransform(Animation animation, float time)
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

* struct [AffineTransform](../../../aspose.cad.fileformats.glb.transforms/affinetransform/)
* class [Animation](../../animation/)
* class [Node](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

