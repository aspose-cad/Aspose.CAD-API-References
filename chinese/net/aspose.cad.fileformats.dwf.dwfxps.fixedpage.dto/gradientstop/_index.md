---
title: "GradientStop 类"
linktitle: "GradientStop"
articleTitle: "GradientStop"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.GradientStop 类。渐变停止点。GradientStop 元素被 LinearGradientBrush 和 R... 使用。"
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/"
keywords: "GradientStop, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GradientStop class

渐变停止点。
GradientStop 元素被 [LinearGradientBrush](../lineargradientbrush/) 和 [RadialGradientBrush](../radialgradientbrush/) 两个元素用于定义位置
以及渲染渐变时颜色渐变的范围。
对于线性渐变画刷，偏移值 0.0 映射到渐变的起始点，
而偏移值 1.0 映射到结束点。
中间的偏移值在这两点之间进行插值，以确定其位置。
对于径向渐变画刷，偏移值 0.0 映射到渐变的起始位置。
偏移值 1.0 映射到由中心确定的椭圆周长，
x 半径和 y 半径。0.0 到 1.0 之间的偏移值位于这些点之间插值得到的位置。

```csharp
public class GradientStop
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GradientStop](gradientstop/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/color/) { get; set; } | 获取或设置颜色。指定渐变停止点的颜色。 |
| [Offset](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/offset/) { get; set; } | 获取或设置偏移量。指定渐变偏移量。偏移量表示在渐变进程中的一个点，在该点指定颜色。渐变进程中偏移量之间的颜色将被插值。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

