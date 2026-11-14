---
title: "LineCap 枚举"
linktitle: "LineCap"
articleTitle: "LineCap"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.LineCap 枚举。线帽。指定线帽的外观。"
type: docs
weight: 150
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/linecap/"
product_version: "26.9"
---
## LineCap enumeration

线帽。
指定线帽的外观。

```csharp
public enum LineCap
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Flat | `0` | 平直。线段的长度是指在曲线上，线段末端的平直线与形状轮廓的两个交点之间的近似距离。长度大于 0 的线段会被绘制，长度为 0 的退化线段则不绘制。 |
| Round | `1` | 圆形。线段的长度是指在曲线上，线段末端的平直线（未附加圆形帽）与形状轮廓的两个交点之间的近似距离。帽子被绘制为附着在线段两端的半圆。圆形帽的边界不会被扭曲以贴合轮廓，而是通过有效的渲染变换进行转换。长度为 0 的退化线段会被绘制为圆形。 |
| Square | `2` | 方形。线段的长度是指在曲线上，线段末端的平直线（未附加方形帽）与形状轮廓的两个交点之间的近似距离。帽子被绘制为附着在线段两端的半方形。方形帽的边界不会弯曲以贴合轮廓，而是通过有效的渲染变换进行转换。长度为 0 的退化线段会被绘制为方形。如果长度为 0 的线段出现在路径的连接处或非常靠近连接处，则渲染分辨率的差异以及坐标计算精度的差异可能导致不同消费者之间的线帽方向不一致。 |
| Triangle | `3` | 三角形。线段的长度是指在曲线上，线段末端的平直线（未附加三角形帽）与形状轮廓的两个交点之间的近似距离。帽子被绘制为底部贴合线段两端的三角形。三角形帽的边界不会被扭曲以贴合轮廓，而是通过有效的渲染变换进行转换。三角形的高度为笔画宽度的一半。长度为 0 的退化线段会被绘制为菱形。如果长度为 0 的线段出现在路径的连接处或非常靠近连接处，则渲染分辨率的差异以及坐标计算精度的差异可能导致不同消费者之间的线帽方向不一致。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

