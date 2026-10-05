---
title: "Rectangle Struct"
linktitle: "Rectangle"
articleTitle: "Rectangle"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.Rectangle struct. Stores a set of four integers that represent the location and size of a rectangle."
type: docs
weight: 760
url: "/net/aspose.cad/rectangle/"
product_version: "26.9"
---
## Rectangle struct

Stores a set of four integers that represent the location and size of a rectangle.

```csharp
public struct Rectangle
```

## Constructors

| Name | Description |
| --- | --- |
| [Rectangle](rectangle/)(int, int, int, int) | Initializes a new instance of the `Rectangle` structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| Bottom { get; set; } | Gets or sets the y-coordinate that is the sum of the [`Y`](./y/) and [`Height`](./height/) property values of this `Rectangle` structure. |
| Empty { get; } | Gets a new instance of the `Rectangle` structure that has [`X`](./x/), [`Y`](./y/), [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| Height { get; set; } | Gets or sets the height of this `Rectangle` structure. |
| IsEmpty { get; } | Gets a value indicating whether all numeric properties of this `Rectangle` have values of zero. |
| Left { get; set; } | Gets or sets the x-coordinate of the left edge of this `Rectangle` structure. |
| Location { get; set; } | Gets or sets the coordinates of the upper-left corner of this `Rectangle` structure. |
| Right { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x/) and [`Width`](./width/) property values of this `Rectangle` structure. |
| Size { get; set; } | Gets or sets the size of this `Rectangle`. |
| Top { get; set; } | Gets or sets the y-coordinate of the top edge of this `Rectangle` structure. |
| Width { get; set; } | Gets or sets the width of this `Rectangle` structure. |
| X { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this `Rectangle` structure. |
| Y { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this `Rectangle` structure. |

## Methods

| Name | Description |
| --- | --- |
| Ceiling(RectangleF) | Converts the specified [`RectangleF`](../rectanglef/) structure to a `Rectangle` structure by rounding the [`RectangleF`](../rectanglef/) values to the next higher integer values. |
| Contains(Point) | Determines if the specified point is contained within this `Rectangle` structure. |
| Contains(Rectangle) | Determines if the rectangular region represented by *rect* is entirely contained within this `Rectangle` structure. |
| Contains(int, int) | Determines if the specified point is contained within this `Rectangle` structure. |
| Equals(object) | Tests whether *obj* is a `Rectangle` structure with the same location and size of this `Rectangle` structure. |
| FromLeftTopRightBottom(int, int, int, int) | Creates a `Rectangle` structure with the specified edge locations. |
| FromPoints(Point, Point) | Creates a new `Rectangle` from two points specified. Two verticales of the created `Rectangle` will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| GetHashCode() | Returns the hash code for this `Rectangle` structure. |
| Inflate(Size) | Inflates this `Rectangle` by the specified amount. |
| Inflate(int, int) | Inflates this `Rectangle` by the specified amount. |
| Inflate(Rectangle, int, int) | Creates and returns an inflated copy of the specified `Rectangle` structure. The copy is inflated by the specified amount. The original `Rectangle` structure remains unmodified. |
| Intersect(Rectangle) | Replaces this `Rectangle` with the intersection of itself and the specified `Rectangle`. |
| Intersect(Rectangle, Rectangle) | Returns a third `Rectangle` structure that represents the intersection of two other `Rectangle` structures. If there is no intersection, an empty `Rectangle` is returned. |
| IntersectsWith(Rectangle) | Determines if this rectangle intersects with *rect*. |
| Normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| Offset(Point) | Adjusts the location of this rectangle by the specified amount. |
| Offset(int, int) | Adjusts the location of this rectangle by the specified amount. |
| Round(RectangleF) | Converts the specified [`RectangleF`](../rectanglef/) to a `Rectangle` by rounding the [`RectangleF`](../rectanglef/) values to the nearest integer values. |
| ToString() | Converts the attributes of this `Rectangle` to a human-readable string. |
| Truncate(RectangleF) | Converts the specified [`RectangleF`](../rectanglef/) to a `Rectangle` by truncating the [`RectangleF`](../rectanglef/) values. |
| Union(Rectangle, Rectangle) | Gets a `Rectangle` structure that contains the union of two `Rectangle` structures. |

## Operators

| Name | Description |
| --- | --- |
| operator == | Tests whether two `Rectangle` structures have equal location and size. |
| operator != | Tests whether two `Rectangle` structures differ in location or size. |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

