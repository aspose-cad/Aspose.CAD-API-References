---
title: "AffineTransform 结构体"
linktitle: "AffineTransform"
articleTitle: "AffineTransform"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Transforms.AffineTransform 结构体。表示三维空间中的仿射变换，具有两种相互排斥的表示方式：作为 ..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/affinetransform/"
product_version: "26.9"
---
## AffineTransform struct

表示三维空间中的仿射变换，具有两种相互排斥的表示方式：

作为 4x3 矩阵。当 [`IsMatrix`](./ismatrix/) 为 true 时。

公开为 [`Matrix`](./matrix/)。
 
作为 缩放/旋转/平移 链。当 [`IsSRT`](./issrt/) 为 true 时。

公开为：[`Scale`](./scale/)、[`Rotation`](./rotation/)、[`Translation`](./translation/)。

```csharp
public struct AffineTransform : IEquatable<AffineTransform>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AffineTransform](affinetransform/)(Vector3?, Quaternion?, Vector3?) | 初始化 AffineTransform 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| IsIdentity { get; } |  |
| IsLosslessDecomposable { get; } | 获取一个值，指示此变换是否可以在不损失精度的情况下分解为 SRT。 |
| IsMatrix { get; } | 获取一个值，指示此 `AffineTransform` 是否表示 Matrix4x4。 |
| IsSRT { get; } | 获取一个值，指示此 `AffineTransform` 是否表示 SRT 链。 |
| IsValid { get; } |  |
| Matrix { get; } | 获取当前 `AffineTransform` 的 Matrix4x4 变换 |
| Rotation { get; } | 获取旋转。 |
| Scale { get; } | 获取缩放。 |
| Translation { get; } | 获取平移 |

## 方法

| 名称 | 描述 |
| --- | --- |
| AreGeometricallyEquivalent(ref AffineTransform, ref AffineTransform, float) | 检查两个变换是否表示相同的几何空间变换。 |
| Blend(AffineTransform[], float[]) |  |
| CreateDecomposed(Matrix4x4) |  |
| CreateFromAny(Matrix4x4?, Vector3?, Quaternion?, Vector3?) |  |
| Equals(AffineTransform) |  |
| Equals(object) |  |
| GetDecomposed() | 如果此对象表示 Matrix4x4，则返回其分解表示。 |
| GetHashCode() |  |
| Multiply(ref AffineTransform, ref AffineTransform) | 将 *a* 乘以 *b*。 |
| TransformNormal(Vector3, ref AffineTransform) | 使用指定的变换转换向量法线。 |
| TryDecompose(out AffineTransform) |  |
| TryDecompose(out Vector3, out Quaternion, out Vector3) |  |
| TryInvert(ref AffineTransform, out AffineTransform) | 对指定的变换进行求逆。返回值指示操作是否成功。 |
| WithRotation(Quaternion) |  |
| WithScale(Vector3) |  |
| WithTranslation(Vector3) |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| 单位矩阵 |  |

## Operators

| 名称 | 描述 |
| --- | --- |
| operator AffineTransform |  |
| operator AffineTransform |  |
| 运算符 == |  |
| 运算符 != |  |
| 运算符 * |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

