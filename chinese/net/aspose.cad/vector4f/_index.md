---
title: "Vector4F 结构体"
linktitle: "Vector4F"
articleTitle: "Vector4F"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Vector4F 结构体。具有 4 个浮点参数的向量"
type: docs
weight: 950
url: "/net/aspose.cad/vector4f/"
product_version: "26.9"
---
## Vector4F struct

具有 4 个 float 参数的向量

```csharp
public struct Vector4F : IEquatable<Vector4F>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Vector4F](vector4f/)(float) | 初始化一个新的 `Vector4F` 结构体实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| A { get; set; } | Alpha 分量 |
| B { get; set; } | Blue 分量 |
| G { get; set; } | Green 分量 |
| Item { get; } | 获取指定索引处的坐标。 |
| Length { get; } | Length |
| R { get; set; } | Red 分量 |
| SquareLength { get; } | 平方长度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Equals(object) | 返回一个布尔值，指示给定的 Object 是否等于此 Vector4F 实例。 |
| Equals(Vector4F) | 返回一个布尔值，指示给定的 Vector4F 是否等于此 Vector4F 实例。 |
| GetHashCode() | 返回此实例的哈希码。 |
| Normalized() | 创建归一化向量。 |
| SafeNormalized() | 安全地创建归一化向量（如果长度为零则返回自身）。 |
| ToVector2F() | 创建 Vector2F。 |
| ToVector3F() | 创建 Vector3F。 |
| Zero() | 创建向量 (0, 0, 0)。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| W | W 坐标 |
| X | X 坐标 |
| Y | Y 坐标 |
| Z | Z 坐标 |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 == | 返回一个布尔值，指示给定的两个向量是否相等。 |
| 运算符 != | 返回一个布尔值，指示给定的两个向量是否不相等。 |
| operator - | 从第一个向量中减去第二个向量。 |
| operator + | 将两个向量相加。 |
| 运算符 * | 将向量乘以标量值。 |
| operator / | 将向量除以标量值。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

