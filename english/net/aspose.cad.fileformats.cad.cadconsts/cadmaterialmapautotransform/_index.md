---
title: "CadMaterialMapAutoTransform Enum"
linktitle: "CadMaterialMapAutoTransform"
articleTitle: "CadMaterialMapAutoTransform"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapAutoTransform enum. Specifies the automatic transform method for a CadMaterialMap."
type: docs
weight: 330
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmapautotransform/"
product_version: "26.9"
---
## CadMaterialMapAutoTransform enumeration

Specifies the automatic transform method for a [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/).

```csharp
[Flags]
public enum CadMaterialMapAutoTransform : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Inherit | `0` | Inherit the auto transform setting from the parent. |
| None | `1` | No automatic transform is applied. |
| TransformObject | `2` | Multiply the mapper transform by a transform that scales by the bounds of the current object and translates to the origin of the current object |
| Model | `4` | Multiply the mapper transform by the model (block) transform. |

### See Also

* [AutoTransform](../autotransform/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

