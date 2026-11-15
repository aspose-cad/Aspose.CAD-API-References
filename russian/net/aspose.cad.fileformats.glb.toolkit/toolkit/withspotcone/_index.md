---
title: "Toolkit.WithSpotCone"
linktitle: "WithSpotCone"
articleTitle: "WithSpotCone"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Toolkit. Устанавливает углы конуса для Spot-света."
type: docs
weight: 560
url: "/net/aspose.cad.fileformats.glb.toolkit/toolkit/withspotcone/"
product_version: "26.9"
---
## Toolkit.WithSpotCone method

Устанавливает углы конуса для света `Spot`.

```csharp
public static PunctualLight WithSpotCone(this PunctualLight light, float innerConeAngle, 
    float outerConeAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| light | PunctualLight | Этот [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) экземпляр. |
| innerConeAngle | Single | Получает угол в радианах от центра прожектора, где начинается падение. Должен быть больше или равен 0 и меньше outerConeAngle. |
| outerConeAngle | Single | Получает угол в радианах от центра прожектора, где заканчивается падение. Должен быть больше innerConeAngle и меньше или равен PI / 2.0. |

### Возвращаемое значение

Этот [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) экземпляр.

### См. также

* class [PunctualLight](../../../aspose.cad.fileformats.glb/punctuallight/)
* class [Toolkit](../)
* namespace [Aspose.CAD.FileFormats.GLB.ToolKit](../../../aspose.cad.fileformats.glb.toolkit/)
* assembly [Aspose.CAD](../../../)

