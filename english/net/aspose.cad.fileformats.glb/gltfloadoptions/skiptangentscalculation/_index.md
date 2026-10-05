---
title: "GltfLoadOptions.SkipTangentsCalculation"
linktitle: "SkipTangentsCalculation"
articleTitle: "SkipTangentsCalculation"
second_title: "Aspose.CAD for .NET API Reference"
description: "GltfLoadOptions property. Whether to skip tangents maps calculation for GLTF/GLB format. Default value: False."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skiptangentscalculation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipTangentsCalculation property

Whether to skip tangents maps calculation for GLTF/GLB format.
 Default value: False.

```csharp
public bool SkipTangentsCalculation { get; set; }
```

## Examples

Turning on the option for skipping tangents maps calculation.

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipTangentsCalculation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### See Also

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

