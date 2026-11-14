---
title: "ValidationContext 结构体"
linktitle: "ValidationContext"
articleTitle: "ValidationContext"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Validation.ValidationContext 结构体。用于模型验证过程的实用类。"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.glb.validation/validationcontext/"
product_version: "26.9"
---
## ValidationContext struct

用于模型验证过程的实用类。

```csharp
public struct ValidationContext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ValidationContext](validationcontext/)(ValidationResult) | 初始化 ValidationContext 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Root { get; } |  |
| TryFix { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| AreEqual(ValueLocation, TValue, TValue) |  |
| AreJoints(ValueLocation, IList&lt;Vector4&gt;, int) |  |
| AreNormals(ValueLocation, IList&lt;Vector3&gt;) |  |
| ArePositions(ValueLocation, IList&lt;Vector3&gt;) |  |
| AreRotations(ValueLocation, IList&lt;Quaternion&gt;) |  |
| AreSameReference(ValueLocation, TRef, TRef) |  |
| AreTangents(ValueLocation, IList&lt;Vector4&gt;) |  |
| EnumsAreEqual(ValueLocation, TValue, TValue) |  |
| 获取上下文(JsonSerializable) |  |
| 是否为任意(ValueLocation, AttributeFormat, params AttributeFormat[]) |  |
| 是否为任意(ValueLocation, T, params T[]) |  |
| 是否为默认或在范围内(ValueLocation, TValue?, TValue, TValue) |  |
| 是否已定义(ValueLocation, T) |  |
| 是否已定义(ValueLocation, T?) |  |
| 是否大于(ValueLocation, TValue, TValue) |  |
| 是否大于或等于(ValueLocation, TValue, TValue) |  |
| 是否在范围内(ValueLocation, T, T, T) |  |
| 是否为JSON可序列化(ValueLocation, object) |  |
| 是否小于(ValueLocation, TValue, TValue) |  |
| 是否小于或等于(ValueLocation, TValue, TValue) |  |
| 是否为矩阵(ValueLocation, ref Matrix4x4, bool, bool) |  |
| 是否为4x3矩阵(ValueLocation, ref Matrix4x4, bool, bool) |  |
| 是否为...的倍数(ValueLocation, int, int) |  |
| 是否为正规(ValueLocation, ref Vector3, ExceptionSeverity) |  |
| 是否为null或在范围内(ValueLocation, int?, int, IReadOnlyList<T>) |  |
| 是否为null或索引(ValueLocation, int?, IReadOnlyList<T>) |  |
| 是否为null或矩阵(ValueLocation, Matrix4x4?, bool, bool) |  |
| 是否为null或4x3矩阵(ValueLocation, Matrix4x4?, bool, bool) |  |
| 是否为null或有效URI(ValueLocation, string, params string[]) |  |
| 是否为位置(ValueLocation, ref Vector3) |  |
| 是否为旋转(ValueLocation, ref Quaternion) |  |
| 是否为已设置集合(ValueLocation, IEnumerable<T>) |  |
| 是否为真(ValueLocation, bool, string, ExceptionSeverity) |  |
| IsUndefined(ValueLocation, T) |  |
| IsUndefined(ValueLocation, T?) |  |
| IsValidURI(ValueLocation, string, params string[]) |  |
| MustBeNull(ValueLocation, object) |  |
| NonNegative(ValueLocation, int?) |  |
| NotNull(ValueLocation, object) |  |
| That(Action) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Validation](../../aspose.cad.fileformats.glb.validation/)
* assembly [Aspose.CAD](../../)

