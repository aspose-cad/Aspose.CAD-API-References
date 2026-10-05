---
title: "SizeF Struct"
linktitle: "SizeF"
articleTitle: "SizeF"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.SizeF struct. Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle."
type: docs
weight: 830
url: "/net/aspose.cad/sizef/"
product_version: "26.9"
---
## SizeF struct

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

```csharp
public struct SizeF
```

## Constructors

| Name | Description |
| --- | --- |
| [SizeF](sizef/)(SizeF) | Initializes a new instance of the `SizeF` structure from the specified `SizeF`. |

## Properties

| Name | Description |
| --- | --- |
| Depth { get; set; } | Gets or sets the depth. |
| Empty { get; } | Gets a new instance of the `SizeF` structure that has [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| Height { get; set; } | Gets or sets the vertical component of this `SizeF`. |
| IsEmpty { get; } | Gets a value indicating whether this `SizeF` has zero width and height. |
| Width { get; set; } | Gets or sets the horizontal component of this `SizeF`. |

## Methods

| Name | Description |
| --- | --- |
| Add(SizeF, SizeF) | Adds the width and height of one `SizeF` structure to the width and height of another `SizeF` structure. |
| Equals(object) | Tests to see whether the specified object is a `SizeF` with the same dimensions as this `SizeF`. |
| GetHashCode() | Returns a hash code for this [`Size`](../size/) structure. |
| Subtract(SizeF, SizeF) | Subtracts the width and height of one `SizeF` structure from the width and height of another `SizeF` structure. |
| ToPointF() | Converts a `SizeF` to a [`PointF`](../pointf/). |
| ToSize() | Converts a `SizeF` to a [`Size`](../size/) structure with truncated size values. |
| ToString() | Creates a human-readable string that represents this `SizeF`. |

## Operators

| Name | Description |
| --- | --- |
| operator + | Adds the width and height of one `SizeF` structure to the width and height of another `SizeF` structure. |
| operator - | Subtracts the width and height of one `SizeF` structure from the width and height of another `SizeF` structure. |
| operator == | Tests whether two `SizeF` structures are equal. |
| operator != | Tests whether two `SizeF` structures are different. |
| operator PointF | Converts the specified `SizeF` to a [`PointF`](../pointf/). |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

