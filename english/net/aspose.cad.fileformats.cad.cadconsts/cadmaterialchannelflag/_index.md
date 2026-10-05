---
title: "CadMaterialChannelFlag Enum"
linktitle: "CadMaterialChannelFlag"
articleTitle: "CadMaterialChannelFlag"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialChannelFlag enum. Flags indicating which texture channels are active for a CadMaterial. Multiple flags can be..."
type: docs
weight: 300
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialchannelflag/"
product_version: "26.9"
---
## CadMaterialChannelFlag enumeration

Flags indicating which texture channels are active for a [`CadMaterial`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterial/). Multiple flags can be combined.

```csharp
[Flags]
public enum CadMaterialChannelFlag : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No texture channels are active. |
| UseDiffuse | `1` | The diffuse texture channel is active. |
| UseSpecular | `2` | The specular texture channel is active. |
| UseReflection | `4` | The reflection texture channel is active. |
| UseOpacity | `8` | The opacity texture channel is active. |
| UseBump | `10` | The bump texture channel is active. |
| UseRefraction | `20` | The refraction texture channel is active. |
| UseAll | `3F` | All texture channels are active. |

### See Also

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

