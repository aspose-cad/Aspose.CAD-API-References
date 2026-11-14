---
title: "Toolkit.WithSpotCone"
linktitle: "WithSpotCone"
articleTitle: "WithSpotCone"
second_title: "Aspose.CAD for .NET API 参考"
description: "Toolkit 方法。设置 Spot 光的锥形角度。"
type: docs
weight: 560
url: "/net/aspose.cad.fileformats.glb.toolkit/toolkit/withspotcone/"
product_version: "26.9"
---
## Toolkit.WithSpotCone method

设置 `Spot` 光的锥形角度。

```csharp
public static PunctualLight WithSpotCone(this PunctualLight light, float innerConeAngle, 
    float outerConeAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| light | PunctualLight | 此 [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) 实例。 |
| innerConeAngle | Single | 获取聚光灯中心开始衰减的角度（弧度）。必须大于或等于 0 且小于 *outerConeAngle*。 |
| outerConeAngle | Single | 获取角度（以弧度为单位），该角度是从聚光灯中心到衰减结束处的角度。必须大于 innerConeAngle 且小于或等于 PI / 2.0。 |

### 返回值

此 [`PunctualLight`](../../../aspose.cad.fileformats.glb/punctuallight/) 实例。

### 另请参阅

* class [PunctualLight](../../../aspose.cad.fileformats.glb/punctuallight/)
* class [Toolkit](../)
* namespace [Aspose.CAD.FileFormats.GLB.ToolKit](../../../aspose.cad.fileformats.glb.toolkit/)
* assembly [Aspose.CAD](../../../)

