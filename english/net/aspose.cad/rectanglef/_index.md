---
title: "RectangleF Struct"
linktitle: "RectangleF"
articleTitle: "RectangleF"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.RectangleF struct. Stores a set of four floating-point numbers that represent the location and size of a rectangle."
type: docs
weight: 770
url: "/net/aspose.cad/rectanglef/"
product_version: "26.9"
---
## RectangleF struct

Stores a set of four floating-point numbers that represent the location and size of a rectangle.

```csharp
public struct RectangleF
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleF](rectanglef/)(float, float, float, float) | Initializes a new instance of the `RectangleF` structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| Bottom { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y/) and [`Height`](./height/) of this `RectangleF` structure. |
| Empty { get; } | Gets a new instance of the `RectangleF` structure that has [`X`](./x/), [`Y`](./y/), [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| Height { get; set; } | Gets or sets the height of this `RectangleF` structure. |
| IsEmpty { get; } | Gets a value indicating whether the [`Width`](./width/) or [`Height`](./height/) property of this `RectangleF` has a value of zero. |
| Left { get; set; } | Gets or sets the x-coordinate of the left edge of this `RectangleF` structure. |
| Location { get; set; } | Gets or sets the coordinates of the upper-left corner of this `RectangleF` structure. |
| Right { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x/) and [`Width`](./width/) of this `RectangleF` structure. |
| Size { get; set; } | Gets or sets the size of this `RectangleF`. |
| Top { get; set; } | Gets or sets the y-coordinate of the top edge of this `RectangleF` structure. |
| Width { get; set; } | Gets or sets the width of this `RectangleF` structure. |
| X { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this `RectangleF` structure. |
| Y { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this `RectangleF` structure. |

## Methods

| Name | Description |
| --- | --- |
| Contains(PointF) | Determines if the specified point is contained within this `RectangleF` structure. |
| Contains(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this `RectangleF` structure. |
| Contains(float, float) | Determines if the specified point is contained within this `RectangleF` structure. |
| Equals(object) | Tests whether *obj* is a `RectangleF` with the same location and size of this `RectangleF`. |
| FromLeftTopRightBottom(float, float, float, float) | Creates a `RectangleF` structure with upper-left corner and lower-right corner at the specified locations. |
| FromPoints(PointF, PointF) | Creates a new [`Rectangle`](../rectangle/) from two points specified. Two verticles of the created [`Rectangle`](../rectangle/) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| GetHashCode() | Gets the hash code for this `RectangleF` structure. |
| Inflate(SizeF) | Inflates this `RectangleF` by the specified amount. |
| Inflate(float, float) | Inflates this `RectangleF` structure by the specified amount. |
| Inflate(RectangleF, float, float) | Creates and returns an inflated copy of the specified `RectangleF` structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| Intersect(RectangleF) | Replaces this `RectangleF` structure with the intersection of itself and the specified `RectangleF` structure. |
| Intersect(RectangleF, RectangleF) | Returns a `RectangleF` structure that represents the intersection of two rectangles. If there is no intersection, and empty `RectangleF` is returned. |
| IntersectsWith(RectangleF) | Determines if this rectangle intersects with *rect*. |
| Normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| Offset(PointF) | Adjusts the location of this rectangle by the specified amount. |
| Offset(float, float) | Adjusts the location of this rectangle by the specified amount. |
| ToString() | Converts the attributes of this `RectangleF` to a human-readable string. |
| Union(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |

## Operators

| Name | Description |
| --- | --- |
| operator == | Tests whether two `RectangleF` structures have equal location and size. |
| operator != | Tests whether two `RectangleF` structures differ in location or size. |
| operator * | Implements the operator *. |
| operator / | Implements the operator /. |
| operator RectangleF | Converts the specified Rectangle structure to a `RectangleF` structure. |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

