---
title: "LineJoin 枚举"
linktitle: "LineJoin"
articleTitle: "LineJoin"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.LineJoin enum. 该线连接。指定线连接的外观。"
type: docs
weight: 160
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/linejoin/"
product_version: "26.9"
---
## LineJoin enumeration

该线连接。
指定线连接的外观。

```csharp
public enum LineJoin
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Miter | `0` | 斜接。指示要填充的区域包括投射到无限远的笔画交叉点，然后在特定距离处进行裁剪。笔画的交叉点在一条垂直于笔画之间角平分线的直线上被裁剪，裁剪距离等于笔画斜接限制值乘以笔画粗细值的一半。 |
| Bevel | `1` | 斜面。指示连接线的外部拐角应通过用一条连接每条笔画外部拐角的直线封闭拐角的三角区域来填充。 |
| Round | `2` | 圆角。指示连接线的外部拐角应通过用其中心点位于两条线交点、半径为笔画粗细值一半的圆形区域来填充。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

