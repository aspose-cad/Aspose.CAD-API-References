---
title: "CadRasterizationOptions.Zoom"
linktitle: "Zoom"
articleTitle: "Zoom"
second_title: "Aspose.CAD for .NET API Reference"
description: "CadRasterizationOptions property. Gets or sets zoom factor. Allows to zoom drawing relatively to canvas size. Value of 1 corresponds to exact fit, value belo..."
type: docs
weight: 20
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/zoom/"
product_version: "26.9"
---
## CadRasterizationOptions.Zoom property

Gets or sets zoom factor. Allows to zoom drawing relatively to canvas size. Value of 1 corresponds to exact fit, value below 1 allows to preserve margins, value above 1 allows to scale drawing up.

```csharp
public float Zoom { get; set; }
```

## Examples

Sets up zoom to keep whole drawing borders visible

```csharp
using (CadImage cadImage = (CadImage)Image.Load(GetPath(fileName)))
{
    JpegOptions options = new JpegOptions();
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.Zoom = 0.9f;
    options.VectorRasterizationOptions = rasterizationOptions;
    cadImage.Save(outFile, options);
}
```

### See Also

* class [CadRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

