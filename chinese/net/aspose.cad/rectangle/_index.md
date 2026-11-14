---
title: "Rectangle 结构体"
linktitle: "Rectangle"
articleTitle: "Rectangle"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Rectangle 结构体。存储一组四个整数，表示矩形的位置和大小。"
type: docs
weight: 760
url: "/net/aspose.cad/rectangle/"
product_version: "26.9"
---
## Rectangle struct

存储一组四个整数，表示矩形的位置和大小。

```csharp
public struct Rectangle
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Rectangle](rectangle/)(int, int, int, int) | 使用指定的位置和大小初始化 `Rectangle` 结构体的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Bottom { get; set; } | 获取或设置此 `Rectangle` 结构体的 y 坐标，该坐标是 [`Y`](./y/) 和 [`Height`](./height/) 属性值的和。 |
| Empty { get; } | 获取一个新的 `Rectangle` 结构体实例，其 [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) 和 [`Height`](./height/) 值均为零。 |
| Height { get; set; } | 获取或设置此 `Rectangle` 结构体的高度。 |
| IsEmpty { get; } | 获取一个值，指示此 `Rectangle` 的所有数值属性是否为零。 |
| Left { get; set; } | 获取或设置此 `Rectangle` 结构体左边缘的 x 坐标。 |
| Location { get; set; } | 获取或设置此 `Rectangle` 结构体左上角的坐标。 |
| Right { get; set; } | 获取或设置此 `Rectangle` 结构体的 x 坐标，该坐标是 [`X`](./x/) 和 [`Width`](./width/) 属性值的和。 |
| Size { get; set; } | 获取或设置此 `Rectangle` 的大小。 |
| Top { get; set; } | 获取或设置此 `Rectangle` 结构体顶部边缘的 y 坐标。 |
| Width { get; set; } | 获取或设置此 `Rectangle` 结构体的宽度。 |
| X { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 x 坐标。 |
| Y { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Ceiling(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 结构转换为 `Rectangle` 结构，方法是将 [`RectangleF`](../rectanglef/) 的值向上取整为下一个整数。 |
| Contains(Point) | 确定指定的点是否包含在此 `Rectangle` 结构中。 |
| Contains(Rectangle) | 确定由 *rect* 表示的矩形区域是否完全包含在此 `Rectangle` 结构中。 |
| Contains(int, int) | 确定指定的点是否包含在此 `Rectangle` 结构中。 |
| Equals(object) | 测试 *obj* 是否为具有与此 `Rectangle` 结构相同位置和大小的 `Rectangle` 结构。 |
| FromLeftTopRightBottom(int, int, int, int) | 使用指定的边缘位置创建一个 `Rectangle` 结构。 |
| FromPoints(Point, Point) | 创建一个由指定的两个点构成的新 `Rectangle`。创建的 `Rectangle` 的两条垂直边将等于传入的 *point1* 和 *point2*。这些通常是相对的顶点。 |
| GetHashCode() | 返回此 `Rectangle` 结构的哈希码。 |
| Inflate(Size) | 按指定的量膨胀此 `Rectangle`。 |
| Inflate(int, int) | 按指定的量膨胀此 `Rectangle`。 |
| Inflate(Rectangle, int, int) | 创建并返回指定 `Rectangle` 结构的膨胀副本。该副本按指定的量进行膨胀。原始 `Rectangle` 结构保持不变。 |
| Intersect(Rectangle) | 用自身与指定的 `Rectangle` 的交集替换此 `Rectangle`。 |
| Intersect(Rectangle, Rectangle) | 返回一个第三个 `Rectangle` 结构，表示两个其他 `Rectangle` 结构的交集。如果没有交集，则返回一个空的 `Rectangle`。 |
| IntersectsWith(Rectangle) | 确定此矩形是否与 *rect* 相交。 |
| Normalize() | 通过使其宽度和高度为正、左侧小于右侧、顶部小于底部来标准化矩形。 |
| Offset(Point) | 按指定的量调整此矩形的位置。 |
| Offset(int, int) | 按指定的量调整此矩形的位置。 |
| Round(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 转换为 `Rectangle`，通过将 [`RectangleF`](../rectanglef/) 的值四舍五入到最近的整数值。 |
| ToString() | 将此 `Rectangle` 的属性转换为人类可读的字符串。 |
| Truncate(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 转换为 `Rectangle`，通过截断 [`RectangleF`](../rectanglef/) 的值。 |
| Union(Rectangle, Rectangle) | 获取一个包含两个 `Rectangle` 结构并集的 `Rectangle` 结构。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 == | 测试两个 `Rectangle` 结构的位置和大小是否相等。 |
| 运算符 != | 测试两个 `Rectangle` 结构的位置或大小是否不同。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

