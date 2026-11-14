---
title: "Vector3F 结构体"
linktitle: "Vector3F"
articleTitle: "Vector3F"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Vector3F 结构体。具有 3 个浮点参数的向量。"
type: docs
weight: 940
url: "/net/aspose.cad/vector3f/"
product_version: "26.9"
---
## Vector3F struct

具有 3 个 float 参数的向量

```csharp
public struct Vector3F : IEquatable<Vector3F>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Vector3F](vector3f/)(float, float, float) | 初始化 `Vector3F` 结构体的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| B { get; set; } | Blue 分量 |
| G { get; set; } | Green 分量 |
| Item { get; } | 获取指定索引处的坐标。 |
| Length { get; } | Length |
| R { get; set; } | Red 分量 |
| SquareLength { get; } | 平方长度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| CrossProduct(Vector3F, Vector3F) | 返回两个向量的叉积。 |
| DotProduct(Vector3F, Vector3F) | 返回两个向量的点积。 |
| Equals(object) | 返回一个布尔值，指示给定的 Object 是否等于此 Vector3F 实例。 |
| Equals(Vector3F) | 返回一个布尔值，指示给定的 Vector3F 是否等于此 Vector3F 实例。 |
| GetHashCode() | 返回此实例的哈希码。 |
| NewellFaceNormal(List&lt;Vector3F&gt;, List&lt;int&gt;) | 使用 Newell 方法计算面的法线。 |
| Normalized() | 创建归一化向量。 |
| Reflect(Vector3F, Vector3F) | 计算反射向量。 |
| SafeNormalized() | 安全地创建归一化向量（如果长度为零则返回自身）。 |
| To2F() | 创建 Vector2F。 |
| ToVector4F(float) | 创建 Vector4F。 |
| XAxis() | 创建 x 轴。 |
| YAxis() | 创建 y 轴。 |
| ZAxis() | 创建 z 轴。 |
| Zero() | 创建向量 (0, 0, 0)。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| X | X 坐标 |
| Y | Y 坐标 |
| Z | Z 坐标 |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 == | 返回一个布尔值，指示给定的两个向量是否相等。 |
| 运算符 != | 返回一个布尔值，指示给定的两个向量是否不相等。 |
| operator - | 对给定向量取负。 |
| operator - | 从第一个向量中减去第二个向量。 |
| operator + | 将两个向量相加。 |
| 运算符 * | 将向量乘以标量值。 |
| 运算符 * | 将向量乘以标量值。 |
| 运算符 * | 从第一个向量中减去第二个向量。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

