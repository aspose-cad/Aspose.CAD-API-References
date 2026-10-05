---
title: "ValidationContext Struct"
linktitle: "ValidationContext"
articleTitle: "ValidationContext"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Validation.ValidationContext struct. Utility class used in the process of model validation."
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.glb.validation/validationcontext/"
product_version: "26.9"
---
## ValidationContext struct

Utility class used in the process of model validation.

```csharp
public struct ValidationContext
```

## Constructors

| Name | Description |
| --- | --- |
| [ValidationContext](validationcontext/)(ValidationResult) | Initializes a new instance of the ValidationContext class. |

## Properties

| Name | Description |
| --- | --- |
| Root { get; } |  |
| TryFix { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| AreEqual(ValueLocation, TValue, TValue) |  |
| AreJoints(ValueLocation, IList&lt;Vector4&gt;, int) |  |
| AreNormals(ValueLocation, IList&lt;Vector3&gt;) |  |
| ArePositions(ValueLocation, IList&lt;Vector3&gt;) |  |
| AreRotations(ValueLocation, IList&lt;Quaternion&gt;) |  |
| AreSameReference(ValueLocation, TRef, TRef) |  |
| AreTangents(ValueLocation, IList&lt;Vector4&gt;) |  |
| EnumsAreEqual(ValueLocation, TValue, TValue) |  |
| GetContext(JsonSerializable) |  |
| IsAnyOf(ValueLocation, AttributeFormat, params AttributeFormat[]) |  |
| IsAnyOf(ValueLocation, T, params T[]) |  |
| IsDefaultOrWithin(ValueLocation, TValue?, TValue, TValue) |  |
| IsDefined(ValueLocation, T) |  |
| IsDefined(ValueLocation, T?) |  |
| IsGreater(ValueLocation, TValue, TValue) |  |
| IsGreaterOrEqual(ValueLocation, TValue, TValue) |  |
| IsInRange(ValueLocation, T, T, T) |  |
| IsJsonSerializable(ValueLocation, object) |  |
| IsLess(ValueLocation, TValue, TValue) |  |
| IsLessOrEqual(ValueLocation, TValue, TValue) |  |
| IsMatrix(ValueLocation, ref Matrix4x4, bool, bool) |  |
| IsMatrix4x3(ValueLocation, ref Matrix4x4, bool, bool) |  |
| IsMultipleOf(ValueLocation, int, int) |  |
| IsNormal(ValueLocation, ref Vector3, ExceptionSeverity) |  |
| IsNullOrInRange(ValueLocation, int?, int, IReadOnlyList&lt;T&gt;) |  |
| IsNullOrIndex(ValueLocation, int?, IReadOnlyList&lt;T&gt;) |  |
| IsNullOrMatrix(ValueLocation, Matrix4x4?, bool, bool) |  |
| IsNullOrMatrix4x3(ValueLocation, Matrix4x4?, bool, bool) |  |
| IsNullOrValidURI(ValueLocation, string, params string[]) |  |
| IsPosition(ValueLocation, ref Vector3) |  |
| IsRotation(ValueLocation, ref Quaternion) |  |
| IsSetCollection(ValueLocation, IEnumerable&lt;T&gt;) |  |
| IsTrue(ValueLocation, bool, string, ExceptionSeverity) |  |
| IsUndefined(ValueLocation, T) |  |
| IsUndefined(ValueLocation, T?) |  |
| IsValidURI(ValueLocation, string, params string[]) |  |
| MustBeNull(ValueLocation, object) |  |
| NonNegative(ValueLocation, int?) |  |
| NotNull(ValueLocation, object) |  |
| That(Action) |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Validation](../../aspose.cad.fileformats.glb.validation/)
* assembly [Aspose.CAD](../../)

