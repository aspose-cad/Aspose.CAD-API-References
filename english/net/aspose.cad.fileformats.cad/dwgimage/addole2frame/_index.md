---
title: "DwgImage.AddOle2Frame"
linktitle: "AddOle2Frame"
articleTitle: "AddOle2Frame"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwgImage method. Adds an OLE2FRAME entity to the drawing using BMP image data."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.cad/dwgimage/addole2frame/"
product_version: "26.9"
---
## DwgImage.AddOle2Frame method

Adds an OLE2FRAME entity to the drawing using BMP image data.

```csharp
public void AddOle2Frame(byte[] imageData, Cad3DPoint insertPoint = null, double? width = default, 
    double? height = default, bool lockAspectRatio = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageData | Byte[] | Byte array containing 24-bit BMP image data. |
| insertPoint | Cad3DPoint | Insertion point of the OLE2FRAME entity. |
| width | Nullable`1 | Width of the OLE2FRAME. |
| height | Nullable`1 | Height of the OLE2FRAME. |
| lockAspectRatio | Boolean | If true, maintains the image aspect ratio by adjusting height based on width or vice versa. |

### See Also

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

