---
title: "Matrix4x4Double 结构体"
linktitle: "Matrix4x4Double"
articleTitle: "Matrix4x4Double"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Transforms.Matrix4x4Double 结构体。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.transforms/matrix4x4double/"
product_version: "26.9"
---
## Matrix4x4Double struct



```csharp
public struct Matrix4x4Double : IEquatable<Matrix4x4Double>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix4x4Double](matrix4x4double/)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | 根据给定的组件构造一个 Matrix4x4。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Identity { get; } | 返回乘法单位矩阵。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| CreateFromQuaternion(Quaternion) | 根据给定的 Quaternion 旋转值创建旋转矩阵。 |
| CreateScale(double, double, double) | 创建缩放矩阵。 |
| CreateTranslation(double, double, double) | 创建平移矩阵。 |
| Equals(Matrix4x4Double) | 返回布尔值，指示此矩阵实例是否等于给定的另一个矩阵。 |
| Equals(object) | 返回布尔值，指示给定的对象是否等于此矩阵实例。 |
| GetHashCode() | 返回此实例的哈希码。 |
| Invert(Matrix4x4Double, out Matrix4x4Double) | 尝试计算给定矩阵的逆矩阵。如果成功，result 将包含逆矩阵。 |
| Multiply(Matrix4x4Double, Matrix4x4Double) | 将一个矩阵乘以另一个矩阵。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| M11 | 矩阵第1行第1列的值。 |
| M12 | 矩阵第1行第2列的值。 |
| M13 | 矩阵第1行第3列的值。 |
| M14 | 矩阵第1行第4列的值。 |
| M21 | 矩阵第2行第1列的值。 |
| M22 | 矩阵第2行第2列的值。 |
| M23 | 矩阵第2行第3列的值。 |
| M24 | 矩阵第2行第4列的值。 |
| M31 | 矩阵第3行第1列的值。 |
| M32 | 矩阵第3行第2列的值。 |
| M33 | 矩阵第3行第3列的值。 |
| M34 | 矩阵第 3 行第 4 列的值。 |
| M41 | 矩阵第 4 行第 1 列的值。 |
| M42 | 矩阵第 4 行第 2 列的值。 |
| M43 | 矩阵第 4 行第 3 列的值。 |
| M44 | 矩阵第 4 行第 4 列的值。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 Matrix4x4 | 将 `Matrix4x4Double` 转换为 Matrix4x4 |
| 运算符 Matrix4x4Double | 将 Matrix4x4 转换为 `Matrix4x4Double` |
| 运算符 == | 返回一个布尔值，指示给定的两个矩阵是否相等。 |
| 运算符 != | 返回一个布尔值，指示给定的两个矩阵是否不相等。 |
| 运算符 * | 将一个矩阵乘以另一个矩阵。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

