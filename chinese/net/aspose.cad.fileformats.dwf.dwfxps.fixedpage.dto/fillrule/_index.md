---
title: "FillRule 枚举"
linktitle: "FillRule"
articleTitle: "FillRule"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.FillRule 枚举。填充规则。FillRule 属性指定填充算法。几何体的填充区域..."
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fillrule/"
product_version: "26.9"
---
## FillRule enumeration

填充规则。
FillRule 属性指定填充算法。
几何体的填充区域通过获取所有
包含的路径图形，并应用填充算法来确定封闭区域。
填充算法决定几何形状的交叉区域如何组合形成一个区域。

```csharp
public enum FillRule
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EvenOdd | `0` | 偶数奇数规则。此规则通过从点向任意方向射出一条射线至无穷大，并统计该射线穿过给定形状的线段数量，以确定画布上点的“内部性”。如果该数量为奇数，则点在内部；如果为偶数，则点在外部。这是文档标记中使用的默认规则。 |
| NonZero | `1` | 非零规则。此规则通过从点向任意方向射出射线至无穷大，然后检查形状的线段穿过射线的地点，以确定画布上点的“内部性”。从计数零开始，每当线段从左向右穿过射线时加一，每当路径线段从右向左穿过射线时减一。计数完成后，如果结果为零，则点在路径外部；否则在内部。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

