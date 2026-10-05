---
title: "Size Struct"
linktitle: "Size"
articleTitle: "Size"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.Size struct. Represents size."
type: docs
weight: 820
url: "/net/aspose.cad/size/"
product_version: "26.9"
---
## Size struct

Represents size.

```csharp
public struct Size
```

## Constructors

| Name | Description |
| --- | --- |
| [Size](size/)(Point) | Initializes a new instance of the `Size` structure from the specified [`Point`](../point/). |

## Properties

| Name | Description |
| --- | --- |
| Empty { get; } | Gets a new instance of the `Size` structure that has [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| Height { get; set; } | Gets or sets the vertical component of this `Size`. |
| IsEmpty { get; } | Gets a value indicating whether this `Size` has width and height of 0. |
| Width { get; set; } | Gets or sets the horizontal component of this `Size`. |

## Methods

| Name | Description |
| --- | --- |
| Add(Size, Size) | Adds the width and height of one `Size` structure to the width and height of another `Size` structure. |
| Ceiling(SizeF) | Converts the specified [`SizeF`](../sizef/) structure to a `Size` structure by rounding the values of the `Size` structure to the next higher integer values. |
| Equals(object) | Tests to see whether the specified object is a `Size` with the same dimensions as this `Size`. |
| GetHashCode() | Returns a hash code for this `Size` structure. |
| Round(SizeF) | Converts the specified [`SizeF`](../sizef/) structure to a `Size` structure by rounding the values of the [`SizeF`](../sizef/) structure to the nearest integer values. |
| Subtract(Size, Size) | Subtracts the width and height of one `Size` structure from the width and height of another `Size` structure. |
| ToString() | Creates a human-readable string that represents this `Size`. |
| Truncate(SizeF) | Converts the specified [`SizeF`](../sizef/) structure to a `Size` structure by truncating the values of the [`SizeF`](../sizef/) structure to the next lower integer values. |

## Operators

| Name | Description |
| --- | --- |
| operator SizeF | Converts the specified `Size` to a [`SizeF`](../sizef/). |
| operator + | Adds the width and height of one `Size` structure to the width and height of another `Size` structure. |
| operator - | Subtracts the width and height of one `Size` structure from the width and height of another `Size` structure. |
| operator == | Tests whether two `Size` structures are equal. |
| operator != | Tests whether two `Size` structures are different. |
| operator Point | Converts the specified `Size` to a [`Point`](../point/). |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

