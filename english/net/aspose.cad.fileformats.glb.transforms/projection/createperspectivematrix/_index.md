---
title: "Projection.CreatePerspectiveMatrix"
linktitle: "CreatePerspectiveMatrix"
articleTitle: "CreatePerspectiveMatrix"
second_title: "Aspose.CAD for .NET API Reference"
description: "Projection method. Calculates a perspective projection matrix."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/projection/createperspectivematrix/"
product_version: "26.9"
---
## Projection.CreatePerspectiveMatrix method

Calculates a perspective projection matrix.

```csharp
public static Matrix4x4 CreatePerspectiveMatrix(float aspectRatio, float yfov, float znear, 
    float zfar = inf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| aspectRatio | Single | The aspect ratio between horizontal and vertical. (optional) |
| yfov | Single | The vertical field of view, in radians. |
| znear | Single | Distance to the near pane in the Z axis. |
| zfar | Single | Distance to the far plane in the Z axis. Optionally, this value can be positive infinity |

### Return Value

A projection matrix

### See Also

* class [Projection](../)
* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../../)

