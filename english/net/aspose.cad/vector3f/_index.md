---
title: "Vector3F Struct"
linktitle: "Vector3F"
articleTitle: "Vector3F"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.Vector3F struct. Vector with 3 float parameters"
type: docs
weight: 940
url: "/net/aspose.cad/vector3f/"
product_version: "26.9"
---
## Vector3F struct

Vector with 3 float parameters

```csharp
public struct Vector3F : IEquatable<Vector3F>
```

## Constructors

| Name | Description |
| --- | --- |
| [Vector3F](vector3f/)(float, float, float) | Initializes a new instance of the `Vector3F` struct. |

## Properties

| Name | Description |
| --- | --- |
| B { get; set; } | Blue component |
| G { get; set; } | Green component |
| Item { get; } | Gets a coordinate at the specified index. |
| Length { get; } | Length |
| R { get; set; } | Red component |
| SquareLength { get; } | Square length |

## Methods

| Name | Description |
| --- | --- |
| CrossProduct(Vector3F, Vector3F) | Returns the cross product of two vectors. |
| DotProduct(Vector3F, Vector3F) | Returns the dot product of two vectors. |
| Equals(object) | Returns a boolean indicating whether the given Object is equal to this Vector3F instance. |
| Equals(Vector3F) | Returns a boolean indicating whether the given Vector3F is equal to this Vector3F instance. |
| GetHashCode() | Returns the hash code for this instance. |
| NewellFaceNormal(List&lt;Vector3F&gt;, List&lt;int&gt;) | Calculates normal of face by newell's method. |
| Normalized() | Creates normilized vector. |
| Reflect(Vector3F, Vector3F) | Calculates a reflected vector. |
| SafeNormalized() | Creates normilized vector safely(returns self if length is zero). |
| To2F() | Creates Vector2F. |
| ToVector4F(float) | Creates Vector4F. |
| XAxis() | Creates x-axis. |
| YAxis() | Creates y-axis. |
| ZAxis() | Creates z-axis. |
| Zero() | Creates vector with (0, 0, 0). |

## Fields

| Name | Description |
| --- | --- |
| X | X coordinate |
| Y | Y coordinate |
| Z | Z coordinate |

## Operators

| Name | Description |
| --- | --- |
| operator == | Returns a boolean indicating whether the two given vectors are equal. |
| operator != | Returns a boolean indicating whether the two given vectors are not equal. |
| operator - | Negates a given vector. |
| operator - | Subtracts the second vector from the first. |
| operator + | Adds two vectors together. |
| operator * | Multiplies vector by scalar value. |
| operator * | Multiplies vector by scalar value. |
| operator * | Subtracts the second vector from the first. |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

