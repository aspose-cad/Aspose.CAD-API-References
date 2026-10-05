---
title: "Matrix4x4Double Struct"
linktitle: "Matrix4x4Double"
articleTitle: "Matrix4x4Double"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Transforms.Matrix4x4Double struct."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.transforms/matrix4x4double/"
product_version: "26.9"
---
## Matrix4x4Double struct



```csharp
public struct Matrix4x4Double : IEquatable<Matrix4x4Double>
```

## Constructors

| Name | Description |
| --- | --- |
| [Matrix4x4Double](matrix4x4double/)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Constructs a Matrix4x4 from the given components. |

## Properties

| Name | Description |
| --- | --- |
| Identity { get; } | Returns the multiplicative identity matrix. |

## Methods

| Name | Description |
| --- | --- |
| CreateFromQuaternion(Quaternion) | Creates a rotation matrix from the given Quaternion rotation value. |
| CreateScale(double, double, double) | Creates a scaling matrix. |
| CreateTranslation(double, double, double) | Creates a translation matrix. |
| Equals(Matrix4x4Double) | Returns a boolean indicating whether this matrix instance is equal to the other given matrix. |
| Equals(object) | Returns a boolean indicating whether the given Object is equal to this matrix instance. |
| GetHashCode() | Returns the hash code for this instance. |
| Invert(Matrix4x4Double, out Matrix4x4Double) | Attempts to calculate the inverse of the given matrix. If successful, result will contain the inverted matrix. |
| Multiply(Matrix4x4Double, Matrix4x4Double) | Multiplies a matrix by another matrix. |

## Fields

| Name | Description |
| --- | --- |
| M11 | Value at row 1, column 1 of the matrix. |
| M12 | Value at row 1, column 2 of the matrix. |
| M13 | Value at row 1, column 3 of the matrix. |
| M14 | Value at row 1, column 4 of the matrix. |
| M21 | Value at row 2, column 1 of the matrix. |
| M22 | Value at row 2, column 2 of the matrix. |
| M23 | Value at row 2, column 3 of the matrix. |
| M24 | Value at row 2, column 4 of the matrix. |
| M31 | Value at row 3, column 1 of the matrix. |
| M32 | Value at row 3, column 2 of the matrix. |
| M33 | Value at row 3, column 3 of the matrix. |
| M34 | Value at row 3, column 4 of the matrix. |
| M41 | Value at row 4, column 1 of the matrix. |
| M42 | Value at row 4, column 2 of the matrix. |
| M43 | Value at row 4, column 3 of the matrix. |
| M44 | Value at row 4, column 4 of the matrix. |

## Operators

| Name | Description |
| --- | --- |
| operator Matrix4x4 | Converts a `Matrix4x4Double` to a Matrix4x4 |
| operator Matrix4x4Double | converts from Matrix4x4 to `Matrix4x4Double` |
| operator == | Returns a boolean indicating whether the given two matrices are equal. |
| operator != | Returns a boolean indicating whether the given two matrices are not equal. |
| operator * | Multiplies a matrix by another matrix. |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

