---
title: "DxfOptions.OriginPosition"
linktitle: "OriginPosition"
articleTitle: "OriginPosition"
second_title: "Aspose.CAD for .NET API Reference"
description: "DxfOptions property. Gets or sets the origin position."
type: docs
weight: 90
url: "/net/aspose.cad.imageoptions/dxfoptions/originposition/"
product_version: "26.9"
---
## DxfOptions.OriginPosition property

Gets or sets the origin position.

```csharp
public Point3D OriginPosition { get; set; }
```

### Property Value

The origin (start) position of the items in the file
 By default it set to (0,0,0)
 For example
 DxfOptions options = new DxfOptions();
 options.OriginPosition = new Point3D(1000, 2000, 3000); //here is shift coordinates
 image.Save(filename + ".dxf", options);
 Result image will have items started with coordinates specified in OriginPosition

### See Also

* class [Point3D](../../../aspose.cad.primitives/point3d/)
* class [DxfOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

