---
title: "Vector4F Struct"
linktitle: "Vector4F"
articleTitle: "Vector4F"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.Vector4F struct. Vector with 4 float parameters"
type: docs
weight: 950
url: "/net/aspose.cad/vector4f/"
product_version: "26.9"
---
## Vector4F struct

Vector with 4 float parameters

```csharp
public struct Vector4F : IEquatable<Vector4F>
```

## Constructors

| Name | Description |
| --- | --- |
| [Vector4F](vector4f/)(float) | Initializes a new instance of the `Vector4F` struct. |

## Properties

| Name | Description |
| --- | --- |
| A { get; set; } | Alpha component |
| B { get; set; } | Blue component |
| G { get; set; } | Green component |
| Item { get; } | Gets a coordinate at the specified index. |
| Length { get; } | Length |
| R { get; set; } | Red component |
| SquareLength { get; } | Square length |

## Methods

| Name | Description |
| --- | --- |
| Equals(object) | Returns a boolean indicating whether the given Object is equal to this Vector4F instance. |
| Equals(Vector4F) | Returns a boolean indicating whether the given Vector4F is equal to this Vector4F instance. |
| GetHashCode() | Returns the hash code for this instance. |
| Normalized() | Creates normilized vector. |
| SafeNormalized() | Creates normilized vector safely(returns self if length is zero). |
| ToVector2F() | Creates Vector2F. |
| ToVector3F() | Creates Vector3F. |
| Zero() | Creates vector with (0, 0, 0). |

## Fields

| Name | Description |
| --- | --- |
| W | W coordinate |
| X | X coordinate |
| Y | Y coordinate |
| Z | Z coordinate |

## Operators

| Name | Description |
| --- | --- |
| operator == | Returns a boolean indicating whether the two given vectors are equal. |
| operator != | Returns a boolean indicating whether the two given vectors are not equal. |
| operator - | Subtracts the second vector from the first. |
| operator + | Adds two vectors together. |
| operator * | Multiplies vector by scalar value. |
| operator / | Divides vector by scalar value. |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

