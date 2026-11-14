---
title: "Size 结构体"
linktitle: "Size"
articleTitle: "Size"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Size 结构体。表示尺寸。"
type: docs
weight: 820
url: "/net/aspose.cad/size/"
product_version: "26.9"
---
## Size struct

表示大小。

```csharp
public struct Size
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Size](size/)(Point) | 从指定的 [`Point`](../point/) 初始化 `Size` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Empty { get; } | 获取一个 `Size` 结构的新实例，其 [`Width`](./width/) 和 [`Height`](./height/) 值设为零。 |
| Height { get; set; } | 获取或设置此 `Size` 的垂直分量。 |
| IsEmpty { get; } | 获取一个值，指示此 `Size` 的宽度和高度是否为 0。 |
| Width { get; set; } | 获取或设置此 `Size` 的水平分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| Add(Size, Size) | 将一个 `Size` 结构的宽度和高度添加到另一个 `Size` 结构的宽度和高度。 |
| Ceiling(SizeF) | 将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构，通过将 `Size` 结构的值向上取整到下一个更高的整数值。 |
| Equals(object) | 测试指定的对象是否为具有与此 `Size` 相同尺寸的 `Size`。 |
| GetHashCode() | 返回此 `Size` 结构的哈希码。 |
| Round(SizeF) | 将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构，通过将 [`SizeF`](../sizef/) 结构的值四舍五入到最近的整数值。 |
| Subtract(Size, Size) | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |
| ToString() | 创建一个可读的字符串来表示此 `Size`。 |
| Truncate(SizeF) | 将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构，通过将 [`SizeF`](../sizef/) 结构的值截断为下一个更低的整数值。 |

## Operators

| 名称 | 描述 |
| --- | --- |
| operator SizeF | 将指定的 `Size` 转换为 [`SizeF`](../sizef/)。 |
| operator + | 将一个 `Size` 结构的宽度和高度添加到另一个 `Size` 结构的宽度和高度。 |
| operator - | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |
| 运算符 == | 测试两个 `Size` 结构是否相等。 |
| 运算符 != | 测试两个 `Size` 结构是否不同。 |
| operator Point | 将指定的 `Size` 转换为 [`Point`](../point/)。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

