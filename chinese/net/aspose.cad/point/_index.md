---
title: "Point 结构体"
linktitle: "Point"
articleTitle: "Point"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Point 结构体。表示一对有序的整数 x 和 y 坐标，定义二维平面中的一个点。"
type: docs
weight: 710
url: "/net/aspose.cad/point/"
product_version: "26.9"
---
## Point struct

表示一对整数 x 和 y 坐标，定义二维平面中的一个点。

```csharp
public struct Point
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Point](point/)(int, int) | 使用指定的坐标初始化 `Point` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Empty { get; } | 获取一个 `Point` 结构的新实例，其 [`X`](./x/) 和 [`Y`](./y/) 值均设为零。 |
| IsEmpty { get; } | 获取一个值，指示此 `Point` 是否为空。 |
| X { get; set; } | 获取或设置此 `Point` 的 x 坐标。 |
| Y { get; set; } | 获取或设置此 `Point` 的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Add(Point, Size) | 将指定的 [`Size`](../size/) 添加到指定的 `Point`。 |
| Ceiling(PointF) | 通过将指定的 [`PointF`](../pointf/) 的值四舍五入到更高的整数，将其转换为 `Point`。 |
| Equals(object) | 指定此 `Point` 是否包含与指定对象相同的坐标。 |
| GetHashCode() | 返回此 `Point` 的哈希码。 |
| Offset(Point) | 按指定的 `Point` 平移此 `Point`。 |
| Offset(int, int) | 按指定的量平移此 `Point`。 |
| Round(PointF) | 通过将 `Point` 值四舍五入到最近的整数，将指定的 [`PointF`](../pointf/) 转换为 `Point` 对象。 |
| Subtract(Point, Size) | 返回从指定的 `Point` 中减去指定的 [`Size`](../size/) 的结果。 |
| ToString() | 将此 `Point` 转换为人类可读的字符串。 |
| Truncate(PointF) | 通过截断 `Point` 的值，将指定的 [`PointF`](../pointf/) 转换为 `Point`。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| operator #=zmR4zjIIHlowbRoENELxUY50= |  |
| operator + | 按给定的 [`Size`](../size/) 平移 `Point`。 |
| operator - | 按给定的 [`Size`](../size/) 的负值平移 `Point`。 |
| operator == | 比较两个 `Point` 对象。结果指示两个 `Point` 对象的 [`X`](./x/) 和 [`Y`](./y/) 属性的值是否相等。 |
| operator != | 比较两个 `Point` 对象。结果指示两个 `Point` 对象的 [`X`](./x/) 或 [`Y`](./y/) 属性的值是否不相等。 |
| operator Size | 将指定的 `Point` 结构转换为 [`Size`](../size/) 结构。 |
| operator PointF | 将指定的 `Point` 结构转换为 [`PointF`](../pointf/) 结构。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

