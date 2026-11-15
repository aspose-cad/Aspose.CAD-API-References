---
title: "Toolkit.WithColor"
linktitle: "WithColor"
articleTitle: "WithColor"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Toolkit. Определяет цвет света, интенсивность и диапазон для текущего PunctualLight."
type: docs
weight: 570
url: "/net/aspose.cad.fileformats.glb.toolkit/toolkit/withcolor/"
product_version: "26.9"
---
## Toolkit.WithColor method

Определяет цвет света, интенсивность и диапазон для текущего [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/).

```csharp
public static PunctualLight WithColor(this PunctualLight light, Vector3 color, 
    float intensity = 1.0, float range = inf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| light | PunctualLight | Этот [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) экземпляр. |
| цвет | Vector3 | RGB‑значение цвета света в линейном пространстве. |
| интенсивность | Single | Яркость света в. Единицы измерения зависят от типа света. Точечные и прожекторные источники используют световую интенсивность в канделах (lm/sr), тогда как направленные источники используют освещённость в люксах (lm/m2). |
| диапазон | Single | Подсказка, определяющая предельное расстояние, при котором интенсивность света считается равной нулю. Поддерживается только для точечных и прожекторных источников. Должно быть > 0. Если не задано, диапазон считается бесконечным. |

### Возвращаемое значение

Этот [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) экземпляр.

### См. также

* class [PunctualLight](../../../aspose.cad.fileformats.glb/punctuallight/)
* class [Toolkit](../)
* namespace [Aspose.CAD.FileFormats.GLB.ToolKit](../../../aspose.cad.fileformats.glb.toolkit/)
* assembly [Aspose.CAD](../../../)

