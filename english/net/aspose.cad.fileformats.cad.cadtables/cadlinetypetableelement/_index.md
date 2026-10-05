---
title: "CadLineTypeTableElement Class"
linktitle: "CadLineTypeTableElement"
articleTitle: "CadLineTypeTableElement"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadTables.CadLineTypeTableElement class. Represents a single element of a linetype pattern defined in CadLineTypeTableObject."
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/"
keywords: "CadLineTypeTableElement, Aspose.CAD.FileFormats.Cad.CadTables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadLineTypeTableElement class

Represents a single element of a linetype pattern defined in [`CadLineTypeTableObject`](../cadlinetypetableobject/).

```csharp
public class CadLineTypeTableElement
```

## Constructors

| Name | Description |
| --- | --- |
| [CadLineTypeTableElement](cadlinetypetableelement/)() | Initializes a new instance of the `CadLineTypeTableElement` class. |

## Properties

| Name | Description |
| --- | --- |
| [DashDotLength](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/dashdotlength/) { get; set; } | Length of the element: positive = dash, negative = space, zero = dot. |
| [Offset](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/offset/) { get; set; } | X,Y offset of the embedded text or shape from the line. |
| [RotationAngle](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/rotationangle/) { get; set; } | Rotation angle of the embedded text or shape. |
| [Scale](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/scale/) { get; set; } | Scale factor of the embedded text or shape. |
| [ShapeFlag](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/shapeflag/) { get; set; } | Flags indicating the element type and rotation mode. |
| [ShapeNumber](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/shapenumber/) { get; set; } | Shape number from the SHX file, or text offset in the string area for text elements. |
| [StyleHandle](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/stylehandle/) { get; set; } | Handle of the referenced text style or SHX font. Used when [`ShapeFlag`](./shapeflag/) has IsText or IsShape. |
| [Text](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/text/) { get; set; } | Embedded text string. Used when [`ShapeFlag`](./shapeflag/) has IsText. |

### See Also

* namespace [Aspose.CAD.FileFormats.Cad.CadTables](../../aspose.cad.fileformats.cad.cadtables/)
* assembly [Aspose.CAD](../../)

