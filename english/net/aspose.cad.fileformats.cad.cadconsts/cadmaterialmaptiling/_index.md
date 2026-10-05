---
title: "CadMaterialMapTiling Enum"
linktitle: "CadMaterialMapTiling"
articleTitle: "CadMaterialMapTiling"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapTiling enum. Specifies the tiling method for a CadMaterialMap."
type: docs
weight: 360
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmaptiling/"
product_version: "26.9"
---
## CadMaterialMapTiling enumeration

Specifies the tiling method for a [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/).

```csharp
public enum CadMaterialMapTiling : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Inherit | `0` | Inherit the tiling setting from the parent. |
| Tile | `1` | Repeats material map along image axis (default). |
| Crop | `2` | Crops material map below 0.0 and above 1.0 in image axis. |
| Clamp | `3` | Clamps material map to between 0.0 and 1.0 in image axis. |
| Mirror | `4` | The grip operation is mirror. |

### See Also

* [Tiling](../tiling/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

