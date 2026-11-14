---
title: "VectorRasterizationOptions 类"
linktitle: "VectorRasterizationOptions"
articleTitle: "VectorRasterizationOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.VectorRasterizationOptions 类。向量光栅化选项。"
type: docs
weight: 580
url: "/net/aspose.cad.imageoptions/vectorrasterizationoptions/"
keywords: "VectorRasterizationOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## VectorRasterizationOptions class

矢量光栅化选项。

```csharp
public abstract class VectorRasterizationOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [ContentAsBitmap](../../aspose.cad.imageoptions/vectorrasterizationoptions/contentasbitmap/) { get; set; } | 获取或设置一个值，指示绘图内容是否以图像形式表示在 Pdf 中。仅适用于 CAD 到 Pdf 的导出。默认值为 false。 |
| [DrawColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | 获取或设置前景颜色。 |
| [EmbedBackground](../../aspose.cad.imageoptions/vectorrasterizationoptions/embedbackground/) { get; set; } | 获取或设置是否应将与输出格式默认背景颜色不同的颜色背景（PDF 和 SVG 为白色，光栅为透明）嵌入输出图像（如果不嵌入，背景将使用输出渲染系统的默认值，但依赖背景颜色的内容将使用指定的背景颜色进行渲染）。 |
| [GraphicsOptions](../../aspose.cad.imageoptions/vectorrasterizationoptions/graphicsoptions/) { get; set; } | 获取或设置在 pdf 中渲染位图的选项（如果 ContentAsBitmap 设置为 true）。 |
| [LayoutPageSizes](../../aspose.cad.imageoptions/vectorrasterizationoptions/layoutpagesizes/) { get; set; } | 获取或设置布局页面尺寸。 |
| [LineScale](../../aspose.cad.imageoptions/vectorrasterizationoptions/linescale/) { get; set; } | 获取或设置相对于原始粗细的线宽缩放因子值。如果希望在导出时将线宽增加 2 倍，则需要将该值设为 2。如果希望在导出时将线宽减小 4 倍，则需要将该值设为 0.25。 |
| [Margins](../../aspose.cad.imageoptions/vectorrasterizationoptions/margins/) { get; set; } | 获取或设置边距。 |
| [PageDepth](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagedepth/) { get; set; } | 获取或设置页面深度。 |
| [PageHeight](../../aspose.cad.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | 获取或设置页面高度。 |
| [PageSize](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | 获取或设置页面大小。 |
| [PageWidth](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | 获取或设置页面宽度。 |
| [RelativePosition](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativeposition/) { get; set; } | 导出区域左上角相对于整个文档图像的位置，使用相对单位——0,0 为左上角，1,1 为文档图像的底部。 |
| [RelativeScale](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativescale/) { get; set; } | 导出区域相对于整个文档图像的比例。计算方式为导出区域对应维度与导出文档较大维度的比率。 |
| [UnitType](../../aspose.cad.imageoptions/vectorrasterizationoptions/unittype/) { get; set; } | 获取或设置导出结果的单位类型。 |

### 另请参阅

* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

