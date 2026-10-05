---
title: "Point Struct"
linktitle: "Point"
articleTitle: "Point"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.Point struct. Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane."
type: docs
weight: 710
url: "/net/aspose.cad/point/"
product_version: "26.9"
---
## Point struct

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

```csharp
public struct Point
```

## Constructors

| Name | Description |
| --- | --- |
| [Point](point/)(int, int) | Initializes a new instance of the `Point` structure with the specified coordinates. |

## Properties

| Name | Description |
| --- | --- |
| Empty { get; } | Gets a new instance of the `Point` structure that has [`X`](./x/) and [`Y`](./y/) values set to zero. |
| IsEmpty { get; } | Gets a value indicating whether this `Point` is empty. |
| X { get; set; } | Gets or sets the x-coordinate of this `Point`. |
| Y { get; set; } | Gets or sets the y-coordinate of this `Point`. |

## Methods

| Name | Description |
| --- | --- |
| Add(Point, Size) | Adds the specified [`Size`](../size/) to the specified `Point`. |
| Ceiling(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by rounding the values of the [`PointF`](../pointf/) to the next higher integer values. |
| Equals(object) | Specifies whether this `Point` contains the same coordinates as the specified Object. |
| GetHashCode() | Returns a hash code for this `Point`. |
| Offset(Point) | Translates this `Point` by the specified `Point`. |
| Offset(int, int) | Translates this `Point` by the specified amount. |
| Round(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` object by rounding the `Point` values to the nearest integer. |
| Subtract(Point, Size) | Returns the result of subtracting specified [`Size`](../size/) from the specified `Point`. |
| ToString() | Converts this `Point` to a human-readable string. |
| Truncate(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by truncating the values of the `Point`. |

## Operators

| Name | Description |
| --- | --- |
| operator #=zmR4zjIIHlowbRoENELxUY50= |  |
| operator + | Translates a `Point` by a given [`Size`](../size/). |
| operator - | Translates a `Point` by the negative of a given [`Size`](../size/). |
| operator == | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) and [`Y`](./y/) properties of the two `Point` objects are equal. |
| operator != | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) or [`Y`](./y/) properties of the two `Point` objects are unequal. |
| operator Size | Converts the specified `Point` structure to a [`Size`](../size/) structure. |
| operator PointF | Converts the specified `Point` structure to the [`PointF`](../pointf/) structure. |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

