---
title: "PunctualLight.SetColor"
linktitle: "SetColor"
articleTitle: "SetColor"
second_title: "Aspose.CAD for .NET API 参考"
description: "PunctualLight 方法。为当前 PunctualLight 定义光的颜色、强度和范围。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/punctuallight/setcolor/"
product_version: "26.9"
---
## PunctualLight.SetColor method

为当前 [`PunctualLight`](../) 定义光的颜色、强度和范围。

```csharp
public void SetColor(Vector3 color, float intensity = 1.0, float range = inf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 | Vector3 | 线性空间中光的颜色的 RGB 值。 |
| 强度 | Single | 光的亮度。其定义的单位取决于光的类型。点光和聚光灯使用坎德拉 (lm/sr) 的光强度，而方向光使用勒克斯 (lm/m2) 的照度。 |
| 范围 | Single | 提示，定义光强度可视为已降至零的距离截断。仅支持点光和聚光灯。必须 &gt; 0。未定义时，范围视为无限。 |

### 另请参阅

* class [PunctualLight](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

