---
title: "GltfLoadOptions.SkipValidation"
linktitle: "SkipValidation"
articleTitle: "SkipValidation"
second_title: "Aspose.CAD for .NET API Reference"
description: "GltfLoadOptions property. Whether to skip validation for GLTF/GLB format. Default value: False."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skipvalidation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipValidation property

Whether to skip validation for GLTF/GLB format.
 Default value: False.

```csharp
public bool SkipValidation { get; set; }
```

## Examples

Turning on the option for skipping Validation.

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipValidation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### See Also

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

