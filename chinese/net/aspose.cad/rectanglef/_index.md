---
title: "RectangleF 结构体"
linktitle: "RectangleF"
articleTitle: "RectangleF"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.RectangleF 结构体。存储一组四个浮点数，表示矩形的位置和大小。"
type: docs
weight: 770
url: "/net/aspose.cad/rectanglef/"
product_version: "26.9"
---
## RectangleF struct

存储一组四个浮点数，表示矩形的位置和大小。

```csharp
public struct RectangleF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RectangleF](rectanglef/)(float, float, float, float) | 使用指定的位置和大小初始化 `RectangleF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Bottom { get; set; } | 获取或设置此 `RectangleF` 结构的 y 坐标，该坐标是 [`Y`](./y/) 与 [`Height`](./height/) 的和。 |
| Empty { get; } | 获取一个 `RectangleF` 结构的新实例，其 [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) 和 [`Height`](./height/) 值均为零。 |
| Height { get; set; } | 获取或设置此 `RectangleF` 结构的高度。 |
| IsEmpty { get; } | 获取一个值，指示此 `RectangleF` 的 [`Width`](./width/) 或 [`Height`](./height/) 属性是否为零。 |
| Left { get; set; } | 获取或设置此 `RectangleF` 结构左边缘的 x 坐标。 |
| Location { get; set; } | 获取或设置此 `RectangleF` 结构左上角的坐标。 |
| Right { get; set; } | 获取或设置此 `RectangleF` 结构的 x 坐标，该坐标为 [`X`](./x/) 与 [`Width`](./width/) 的和。 |
| Size { get; set; } | 获取或设置此 `RectangleF` 的大小。 |
| Top { get; set; } | 获取或设置此 `RectangleF` 结构上边缘的 y 坐标。 |
| Width { get; set; } | 获取或设置此 `RectangleF` 结构的宽度。 |
| X { get; set; } | 获取或设置此 `RectangleF` 结构左上角的 x 坐标。 |
| Y { get; set; } | 获取或设置此 `RectangleF` 结构左上角的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Contains(PointF) | 确定指定的点是否包含在此 `RectangleF` 结构中。 |
| Contains(RectangleF) | 确定由 *rect* 表示的矩形区域是否完全包含在此 `RectangleF` 结构中。 |
| Contains(float, float) | 确定指定的点是否包含在此 `RectangleF` 结构中。 |
| Equals(object) | 测试 *obj* 是否为具有与此 `RectangleF` 相同位置和大小的 `RectangleF`。 |
| FromLeftTopRightBottom(float, float, float, float) | 创建一个 `RectangleF` 结构，其左上角和右下角位于指定的位置。 |
| FromPoints(PointF, PointF) | 从指定的两个点创建一个新的[`Rectangle`](../rectangle/)。创建的[`Rectangle`](../rectangle/)的两个顶点将等于传入的 *point1* 和 *point2*。这些通常是相对的顶点。 |
| GetHashCode() | 获取此 `RectangleF` 结构的哈希码。 |
| Inflate(SizeF) | 将此 `RectangleF` 按指定量膨胀。 |
| Inflate(float, float) | 按指定的量膨胀此 `RectangleF` 结构。 |
| Inflate(RectangleF, float, float) | 创建并返回指定 `RectangleF` 结构的膨胀副本。该副本按指定的量膨胀。原始矩形保持不变。 |
| Intersect(RectangleF) | 用自身与指定 `RectangleF` 结构的交集替换此 `RectangleF` 结构。 |
| Intersect(RectangleF, RectangleF) | 返回一个表示两个矩形交集的 `RectangleF` 结构。如果没有交集，则返回一个空的 `RectangleF`。 |
| IntersectsWith(RectangleF) | 确定此矩形是否与 *rect* 相交。 |
| Normalize() | 通过使其宽度和高度为正、左侧小于右侧、顶部小于底部来标准化矩形。 |
| Offset(PointF) | 按指定的量调整此矩形的位置。 |
| Offset(float, float) | 按指定的量调整此矩形的位置。 |
| ToString() | 将此 `RectangleF` 的属性转换为人类可读的字符串。 |
| Union(RectangleF, RectangleF) | 创建能够容纳两个矩形并形成并集的最小可能的第三个矩形。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 == | 测试两个 `RectangleF` 结构的位置和大小是否相等。 |
| 运算符 != | 测试两个 `RectangleF` 结构的位置或大小是否不同。 |
| 运算符 * | 实现运算符 *。 |
| operator / | 实现运算符 /。 |
| 运算符 RectangleF | 将指定的 Rectangle 结构转换为 `RectangleF` 结构。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

