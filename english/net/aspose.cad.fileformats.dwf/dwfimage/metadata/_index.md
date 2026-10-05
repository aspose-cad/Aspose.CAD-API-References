---
title: "DwfImage.Metadata"
linktitle: "Metadata"
articleTitle: "Metadata"
second_title: "Aspose.CAD for .NET API Reference"
description: "DwfImage property. Gets or sets the metadata information. Returns the array of metadata records from manifest and descriptors resources of Dwf/Dwfx package."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.dwf/dwfimage/metadata/"
product_version: "26.9"
---
## DwfImage.Metadata property

Gets or sets the metadata information.
 Returns the array of metadata records from manifest and descriptors resources of Dwf/Dwfx package.

```csharp
public DwfMetadata[] Metadata { get; set; }
```

## Examples

Retrieves all metadata records and modifies one of them.

```csharp
string file = "ExampleFile.dwf";
using (DwfImage image = (DwfImage) Aspose.CAD.Image.Load(file))
{
    string outFile = "ExampleFile_Changed.dwf";
    using (FileStream fs = new FileStream(outFile, FileMode.Create))
    {
        DwfMetadata[] metadata = image.Metadata;
        foreach (DwfMetadata dwfMetadata in metadata)
        {
            if (dwfMetadata.Category != "AutoCAD Drawing" || dwfMetadata.Name != "Creator")
            {
                continue;
            }

            dwfMetadata.Value = "Aspose CAD application";
        }

        image.Metadata = metadata;
        ImageOptionsBase options = new DwfOptions { OutputMode = CadOutputMode.Convert };
        image.Save(fs, jpegOptions);
    }
}
```

### See Also

* class [DwfMetadata](../../dwfmetadata/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

