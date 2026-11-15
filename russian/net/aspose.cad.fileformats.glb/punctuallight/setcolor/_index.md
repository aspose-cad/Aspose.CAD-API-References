---
title: "PunctualLight.SetColor"
linktitle: "SetColor"
articleTitle: "SetColor"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод PunctualLight. Определяет цвет света, интенсивность и диапазон для текущего PunctualLight."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/punctuallight/setcolor/"
product_version: "26.9"
---
## PunctualLight.SetColor method

Определяет цвет света, интенсивность и диапазон для текущего [`PunctualLight`](../).

```csharp
public void SetColor(Vector3 color, float intensity = 1.0, float range = inf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| цвет | Vector3 | RGB‑значение цвета света в линейном пространстве. |
| интенсивность | Single | Яркость света в. Единицы измерения зависят от типа света. Точечные и прожекторные источники используют световую интенсивность в канделах (lm/sr), тогда как направленные источники используют освещённость в люксах (lm/m2). |
| диапазон | Single | Подсказка, определяющая предельное расстояние, при котором интенсивность света считается равной нулю. Поддерживается только для точечных и прожекторных источников. Должно быть > 0. Если не задано, диапазон считается бесконечным. |

### См. также

* class [PunctualLight](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

