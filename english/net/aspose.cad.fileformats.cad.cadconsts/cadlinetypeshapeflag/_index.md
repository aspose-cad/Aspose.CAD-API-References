---
title: "CadLineTypeShapeFlag Enum"
linktitle: "CadLineTypeShapeFlag"
articleTitle: "CadLineTypeShapeFlag"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadLineTypeShapeFlag enum. Linetype shape flag."
type: docs
weight: 280
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadlinetypeshapeflag/"
product_version: "26.9"
---
## CadLineTypeShapeFlag enumeration

Linetype shape flag.

```csharp
[Flags]
public enum CadLineTypeShapeFlag : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No flags set. A simple linetype element: dash, dot or space. |
| RotationIsAbsolute | `1` | The rotation angle of the embedded text or shape is absolute with respect to the origin. |
| IsText | `2` | The linetype element contains an embedded text string. |
| IsShape | `4` | The linetype element contains an embedded shape (referenced by shape number from a SHX file). |
| RotationIsUpright | `8` | The embedded text or shape is displayed upright (easy-to-read orientation). |

### See Also

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

