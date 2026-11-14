---
title: "Point3D 类"
linktitle: "Point3D"
articleTitle: "Point3D"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Primitives.Point3D 类。表示用于处理 3D 点及其特殊操作的类。"
type: docs
weight: 30
url: "/net/aspose.cad.primitives/point3d/"
keywords: "Point3D, Aspose.CAD.Primitives, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Point3D class

表示用于处理 3D 点及其特殊操作的类。

```csharp
public class Point3D : Point2D
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Point3D](point3d/#constructor)() | 初始化 Point3D 类的新实例 |
| [Point3D](point3d/#constructor_1)(double, double) | 初始化 Point3D 类的新实例 |
| [Point3D](point3d/#constructor_2)(double, double, double) | 初始化 Point3D 类的新实例 |
| [Point3D](point3d/#constructor_3)(double, double, double, double) | 初始化 Point3D 类的新实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateArray](../../aspose.cad.primitives/point3d/coordinatearray/) { get; } |  |
| [W](../../aspose.cad.primitives/point3d/w/) { get; set; } | 获取或设置 W 坐标 |
| [X](../../aspose.cad.primitives/point2d/x/) { get; set; } | 获取或设置 x。 |
| [Y](../../aspose.cad.primitives/point2d/y/) { get; set; } | 获取或设置 y。 |
| [Z](../../aspose.cad.primitives/point3d/z/) { get; set; } | 获取或设置 Z 坐标 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Copy](../../aspose.cad.primitives/point3d/copy/)() | 创建当前点的副本 |
| static [CrossProduct](../../aspose.cad.primitives/point3d/crossproduct/)(Point3D, Point3D) | 获取点的叉积 |
| [Distance](../../aspose.cad.primitives/point2d/distance/)(Point2D) |  |
| [Distance](../../aspose.cad.primitives/point3d/distance/#distance)(Point3D) |  |
| static [Distance](../../aspose.cad.primitives/point3d/distance/#distance_1)(Point3D, Point3D) | 获取点之间的距离 |
| static [DotProduct](../../aspose.cad.primitives/point3d/dotproduct/)(Point3D, Point3D) | 获取两个向量之间的点积。 |
| [Equality](../../aspose.cad.primitives/point3d/equality/)(object) | 执行 3D 点的真实比较 |
| override [Equals](../../aspose.cad.primitives/point3d/equals/#equals)(object) | 允许比较 3D 点。 |
| override [Equals](../../aspose.cad.primitives/point3d/equals/#equals_1)(Point2D) | 重写 2D 点的 Equals 方法，使调用的比较为 3D |
| [EqualsSoft](../../aspose.cad.primitives/point3d/equalssoft/)(object, double) | 允许使用指定阈值比较 3D 点。 |
| override [GetHashCode](../../aspose.cad.primitives/point3d/gethashcode/)() | 返回对象的哈希码。 |
| static [NormalVector](../../aspose.cad.primitives/point3d/normalvector/)(Point3D, Point3D, Point3D) | 获取平面的法向量。 |
| [Normalize](../../aspose.cad.primitives/point3d/normalize/)() | 对指定的原点进行归一化。 |
| static [Spherical](../../aspose.cad.primitives/point3d/spherical/)(double, double, double) | 获取球坐标系中的点 |
| [operator ==](../../aspose.cad.primitives/point3d/op_equality/) | 允许比较 3D 点。 |
| [operator !=](../../aspose.cad.primitives/point3d/op_inequality/) | 允许比较 3D 点。 |
| [operator -](../../aspose.cad.primitives/point3d/op_subtraction/) | 实现运算符 -。 |
| [operator +](../../aspose.cad.primitives/point3d/op_addition/) | 实现运算符 +。 |
| [operator *](../../aspose.cad.primitives/point3d/op_multiply/) | 实现运算符 *。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Zero](../../aspose.cad.primitives/point3d/zero/) |  |

### 另请参阅

* class [Point2D](../point2d/)
* namespace [Aspose.CAD.Primitives](../../aspose.cad.primitives/)
* assembly [Aspose.CAD](../../)

