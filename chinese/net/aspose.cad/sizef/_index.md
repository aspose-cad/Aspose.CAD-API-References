---
title: "SizeF 结构"
linktitle: "SizeF"
articleTitle: "SizeF"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.SizeF 结构。存储一对有序的浮点数，通常是矩形的宽度和高度。"
type: docs
weight: 830
url: "/net/aspose.cad/sizef/"
product_version: "26.9"
---
## SizeF struct

存储一对浮点数，通常表示矩形的宽度和高度。

```csharp
public struct SizeF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SizeF](sizef/)(SizeF) | 从指定的 `SizeF` 初始化 `SizeF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Depth { get; set; } | 获取或设置深度。 |
| Empty { get; } | 获取一个 `SizeF` 结构的新实例，其 [`Width`](./width/) 和 [`Height`](./height/) 值设为零。 |
| Height { get; set; } | 获取或设置此 `SizeF` 的垂直分量。 |
| IsEmpty { get; } | 获取一个值，指示此 `SizeF` 的宽度和高度是否为零。 |
| Width { get; set; } | 获取或设置此 `SizeF` 的水平分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Add(SizeF, SizeF) | 将一个 `SizeF` 结构的宽度和高度添加到另一个 `SizeF` 结构的宽度和高度。 |
| Equals(object) | 测试指定的对象是否为具有与此 `SizeF` 相同尺寸的 `SizeF`。 |
| GetHashCode() | 返回此 [`Size`](../size/) 结构的哈希码。 |
| Subtract(SizeF, SizeF) | 从另一个 `SizeF` 结构的宽度和高度中减去一个 `SizeF` 结构的宽度和高度。 |
| ToPointF() | 将 `SizeF` 转换为 [`PointF`](../pointf/)。 |
| ToSize() | 将 `SizeF` 转换为带有截断尺寸值的 [`Size`](../size/) 结构。 |
| ToString() | 创建一个可读的字符串来表示此 `SizeF`。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| operator + | 将一个 `SizeF` 结构的宽度和高度添加到另一个 `SizeF` 结构的宽度和高度。 |
| operator - | 从另一个 `SizeF` 结构的宽度和高度中减去一个 `SizeF` 结构的宽度和高度。 |
| 运算符 == | 测试两个 `SizeF` 结构是否相等。 |
| 运算符 != | 测试两个 `SizeF` 结构是否不同。 |
| operator PointF | 将指定的 `SizeF` 转换为 [`PointF`](../pointf/)。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

