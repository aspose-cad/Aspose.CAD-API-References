---
title: "Projection.CreatePerspectiveMatrix"
linktitle: "CreatePerspectiveMatrix"
articleTitle: "CreatePerspectiveMatrix"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Projection. Вычисляет перспективную проекционную матрицу."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/projection/createperspectivematrix/"
product_version: "26.9"
---
## Projection.CreatePerspectiveMatrix method

Вычисляет перспективную матрицу проекции.

```csharp
public static Matrix4x4 CreatePerspectiveMatrix(float aspectRatio, float yfov, float znear, 
    float zfar = inf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| aspectRatio | Single | Соотношение сторон между горизонталью и вертикалью. (необязательно) |
| yfov | Single | Вертикальное поле зрения в радианах. |
| znear | Single | Расстояние до ближней плоскости по оси Z. |
| zfar | Single | Расстояние до дальней плоскости по оси Z. При желании это значение может быть положительной бесконечностью |

### Возвращаемое значение

Матрица проекции

### См. также

* class [Projection](../)
* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../../)

