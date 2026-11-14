---
title: "PunctualLight.SetSpotCone"
linktitle: "SetSpotCone"
articleTitle: "SetSpotCone"
second_title: "Aspose.CAD for .NET API 参考"
description: "PunctualLight 方法。设置 Spot 光的锥形角度。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb/punctuallight/setspotcone/"
product_version: "26.9"
---
## PunctualLight.SetSpotCone method

设置 `Spot` 光的锥形角度。

```csharp
public void SetSpotCone(float innerConeAngle, float outerConeAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| innerConeAngle | Single | 获取聚光灯中心开始衰减的角度（弧度）。必须大于或等于 0 且小于 *outerConeAngle*。 |
| outerConeAngle | Single | 获取角度（以弧度为单位），该角度是从聚光灯中心到衰减结束处的角度。必须大于 innerConeAngle 且小于或等于 PI / 2.0。 |

### 另请参阅

* class [PunctualLight](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

