---
title: "PointF 结构体"
linktitle: "PointF"
articleTitle: "PointF"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.PointF 结构体。表示一对有序的浮点数 x 和 y 坐标，定义二维平面中的一点。"
type: docs
weight: 720
url: "/net/aspose.cad/pointf/"
product_version: "26.9"
---
## PointF struct

表示一对浮点数 x 和 y 坐标，定义二维平面中的一个点。

```csharp
public struct PointF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PointF](pointf/)(float, float) | 使用指定坐标初始化 `PointF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Empty { get; } | 获取一个 `PointF` 结构的新实例，其 [`X`](./x/) 和 [`Y`](./y/) 值设为零。 |
| IsEmpty { get; } | 获取一个值，指示此 `PointF` 是否为空。 |
| X { get; set; } | 获取或设置此 `PointF` 的 x 坐标。 |
| Y { get; set; } | 获取或设置此 `PointF` 的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Add(PointF, Size) | 按指定的 [`Size`](../size/) 平移给定的 `PointF`。 |
| Add(PointF, SizeF) | 按指定的 [`SizeF`](../sizef/) 平移给定的 `PointF`。 |
| Equals(object) | 指定此 `PointF` 是否包含与指定对象相同的坐标。 |
| GetHashCode() | 返回此 `PointF` 结构的哈希码。 |
| Subtract(PointF, Size) | 按指定大小的相反方向平移 `PointF`。 |
| Subtract(PointF, SizeF) | 按指定大小的相反方向平移 `PointF`。 |
| ToPointApsArray(PointF[]) | 执行从 `PointF` 数组 到 `ApsPoint` 数组 的显式转换。 |
| ToString() | 将此 `PointF` 转换为可读的字符串。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| operator + | 按给定的 [`Size`](../size/) 平移 `PointF`。 |
| operator - | 按给定的 [`Size`](../size/) 的负值平移 `PointF`。 |
| operator + | 按指定的 [`SizeF`](../sizef/) 平移 `PointF`。 |
| operator - | 按指定的 [`SizeF`](../sizef/) 的负值平移 `PointF`。 |
| operator == | 比较两个 `PointF` 结构体。结果指示这两个 `PointF` 结构体的 [`X`](./x/) 和 [`Y`](./y/) 属性值是否相等。 |
| 运算符 != | 确定指定点的坐标是否不相等。 |
| operator #=zmR4zjIIHlowbRoENELxUY50= |  |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

