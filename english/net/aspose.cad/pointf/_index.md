---
title: "PointF Struct"
linktitle: "PointF"
articleTitle: "PointF"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.PointF struct. Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane."
type: docs
weight: 720
url: "/net/aspose.cad/pointf/"
product_version: "26.9"
---
## PointF struct

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

```csharp
public struct PointF
```

## Constructors

| Name | Description |
| --- | --- |
| [PointF](pointf/)(float, float) | Initializes a new instance of the `PointF` structure with the specified coordinates. |

## Properties

| Name | Description |
| --- | --- |
| Empty { get; } | Gets a new instance of the `PointF` structure that has [`X`](./x/) and [`Y`](./y/) values set to zero. |
| IsEmpty { get; } | Gets a value indicating whether this `PointF` is empty. |
| X { get; set; } | Gets or sets the x-coordinate of this `PointF`. |
| Y { get; set; } | Gets or sets the y-coordinate of this `PointF`. |

## Methods

| Name | Description |
| --- | --- |
| Add(PointF, Size) | Translates a given `PointF` by the specified [`Size`](../size/). |
| Add(PointF, SizeF) | Translates a given `PointF` by a specified [`SizeF`](../sizef/). |
| Equals(object) | Specifies whether this `PointF` contains the same coordinates as the specified Object. |
| GetHashCode() | Returns a hash code for this `PointF` structure. |
| Subtract(PointF, Size) | Translates a `PointF` by the negative of a specified size. |
| Subtract(PointF, SizeF) | Translates a `PointF` by the negative of a specified size. |
| ToPointApsArray(PointF[]) | Performs an explicit conversion from `PointF` arr to `ApsPoint` arr. |
| ToString() | Converts this `PointF` to a human readable string. |

## Operators

| Name | Description |
| --- | --- |
| operator + | Translates a `PointF` by a given [`Size`](../size/). |
| operator - | Translates a `PointF` by the negative of a given [`Size`](../size/). |
| operator + | Translates the `PointF` by the specified [`SizeF`](../sizef/). |
| operator - | Translates a `PointF` by the negative of a specified [`SizeF`](../sizef/). |
| operator == | Compares two `PointF` structures. The result specifies whether the values of the [`X`](./x/) and [`Y`](./y/) properties of the two `PointF` structures are equal. |
| operator != | Determines whether the coordinates of the specified points are not equal. |
| operator #=zmR4zjIIHlowbRoENELxUY50= |  |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

