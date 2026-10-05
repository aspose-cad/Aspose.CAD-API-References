---
title: "VectorRasterizationOptions.LineScale"
linktitle: "LineScale"
articleTitle: "LineScale"
second_title: "Aspose.CAD for .NET API Reference"
description: "VectorRasterizationOptions property. Gets or sets a value of the line thickness scaling factor relative to the original thickness. If you want the line thick..."
type: docs
weight: 130
url: "/net/aspose.cad.imageoptions/vectorrasterizationoptions/linescale/"
product_version: "26.9"
---
## VectorRasterizationOptions.LineScale property

Gets or sets a value of the line thickness scaling factor relative to the original thickness.
 If you want the line thickness to be increased by 2 times during export, then you need to set the value to 2.
 If you want the line thickness to be reduced by 4 times during export, then you need to set the value to 0.25.

```csharp
public float LineScale { get; set; }
```

## Examples

Reads an image file in PLT format and saves the image in SVG format with .

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.plt", fileName);
string outFile = string.Format("{0}.svg", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (Image image = Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    ImageOptionsBase options = new SvgOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
                                             {
                                                 LineScale = 0.25f
                                             };

    image.Save(stream, options);
}
```

### See Also

* class [VectorRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

