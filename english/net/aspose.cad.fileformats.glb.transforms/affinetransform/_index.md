---
title: "AffineTransform Struct"
linktitle: "AffineTransform"
articleTitle: "AffineTransform"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Transforms.AffineTransform struct. Represents an affine transform in 3D space, with two mutually exclusive representantions: As a ..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/affinetransform/"
product_version: "26.9"
---
## AffineTransform struct

Represents an affine transform in 3D space, with two mutually exclusive representantions:

 As a 4x3 Matrix. When [`IsMatrix`](./ismatrix/) is true.

 Publicly exposed as [`Matrix`](./matrix/).
 
 As a Scale/Rotation/Translation chain. When [`IsSRT`](./issrt/) is true.

 Publicly exposed as: [`Scale`](./scale/), [`Rotation`](./rotation/), [`Translation`](./translation/).

```csharp
public struct AffineTransform : IEquatable<AffineTransform>
```

## Constructors

| Name | Description |
| --- | --- |
| [AffineTransform](affinetransform/)(Vector3?, Quaternion?, Vector3?) | Initializes a new instance of the AffineTransform class. |

## Properties

| Name | Description |
| --- | --- |
| IsIdentity { get; } |  |
| IsLosslessDecomposable { get; } | Gets a value indicating whether this transform can be decomposed to SRT without precission loss. |
| IsMatrix { get; } | Gets a value indicating whether this `AffineTransform` represents a Matrix4x4. |
| IsSRT { get; } | Gets a value indicating whether this `AffineTransform` represents a SRT chain. |
| IsValid { get; } |  |
| Matrix { get; } | Gets the Matrix4x4 transform of the current `AffineTransform` |
| Rotation { get; } | Gets the rotation. |
| Scale { get; } | Gets the scale. |
| Translation { get; } | Gets the translation |

## Methods

| Name | Description |
| --- | --- |
| AreGeometricallyEquivalent(ref AffineTransform, ref AffineTransform, float) | Checks whether two transform represent the same geometric spatial transformation. |
| Blend(AffineTransform[], float[]) |  |
| CreateDecomposed(Matrix4x4) |  |
| CreateFromAny(Matrix4x4?, Vector3?, Quaternion?, Vector3?) |  |
| Equals(AffineTransform) |  |
| Equals(object) |  |
| GetDecomposed() | If this object represents a Matrix4x4, it returns a decomposed representation. |
| GetHashCode() |  |
| Multiply(ref AffineTransform, ref AffineTransform) | Multiplies *a* by *b*. |
| TransformNormal(Vector3, ref AffineTransform) | Transforms a vector normal by a specified transform. |
| TryDecompose(out AffineTransform) |  |
| TryDecompose(out Vector3, out Quaternion, out Vector3) |  |
| TryInvert(ref AffineTransform, out AffineTransform) | Inverts the specified transform. The return value indicates whether the operation succeeded. |
| WithRotation(Quaternion) |  |
| WithScale(Vector3) |  |
| WithTranslation(Vector3) |  |

## Fields

| Name | Description |
| --- | --- |
| Identity |  |

## Operators

| Name | Description |
| --- | --- |
| operator AffineTransform |  |
| operator AffineTransform |  |
| operator == |  |
| operator != |  |
| operator * |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

