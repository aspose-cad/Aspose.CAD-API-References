---
title: "PolyBezier Class"
linktitle: "PolyBezier"
articleTitle: "PolyBezier"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cgm.Commands.PolyBezier class. Class=4, ElementId=26"
type: docs
weight: 1680
url: "/net/aspose.cad.fileformats.cgm.commands/polybezier/"
keywords: "PolyBezier, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PolyBezier class

Class=4, ElementId=26

```csharp
public class PolyBezier : Command
```

## Constructors

| Name | Description |
| --- | --- |
| [PolyBezier](polybezier/#constructor)(CgmFile) | Initializes a new instance of the PolyBezier class. |
| [PolyBezier](polybezier/#constructor_1)(CgmFile, int, IEnumerable&lt;BezierCurve&gt;) | Initializes a new instance of the PolyBezier class. |

## Properties

| Name | Description |
| --- | --- |
| [ContinuityIndicator](../../aspose.cad.fileformats.cgm.commands/polybezier/continuityindicator/) { get; set; } | 1: discontinuous, 2: continuous, >2: reserved for registered values |
| [Curves](../../aspose.cad.fileformats.cgm.commands/polybezier/curves/) { get; set; } |  |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| override [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/polybezier/readfrombinary/)(IBinaryReader) |  |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/command/tostring/)() |  |
| override [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/polybezier/writeasbinary/)(IBinaryWriter) |  |
| override [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/polybezier/writeascleartext/)(IClearTextWriter) |  |

### See Also

* class [Command](../command/)
* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

