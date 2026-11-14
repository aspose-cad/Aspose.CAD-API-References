---
title: "CadRasterizationOptions 类"
linktitle: "CadRasterizationOptions"
articleTitle: "CadRasterizationOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.CadRasterizationOptions 类。Cad 光栅化选项。"
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/"
keywords: "CadRasterizationOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadRasterizationOptions class

Cad 光栅化选项。

```csharp
public class CadRasterizationOptions : VectorRasterizationOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadRasterizationOptions](cadrasterizationoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutomaticLayoutsScaling](../../aspose.cad.imageoptions/cadrasterizationoptions/automaticlayoutsscaling/) { get; set; } | 获取或设置一个值，指示布局是否应自动缩放。 |
| [BackgroundColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [ContentAsBitmap](../../aspose.cad.imageoptions/vectorrasterizationoptions/contentasbitmap/) { get; set; } | 获取或设置一个值，指示绘图内容是否以图像形式表示在 Pdf 中。仅适用于 CAD 到 Pdf 的导出。默认值为 false。 |
| [CtbSources](../../aspose.cad.imageoptions/cadrasterizationoptions/ctbsources/) { get; set; } | 获取或设置 CTB 源。 |
| [DrawColor](../../aspose.cad.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | 获取或设置前景颜色。 |
| [DrawType](../../aspose.cad.imageoptions/cadrasterizationoptions/drawtype/) { get; set; } | 获取或设置绘图类型。 |
| [EmbedBackground](../../aspose.cad.imageoptions/vectorrasterizationoptions/embedbackground/) { get; set; } | 获取或设置是否应将与输出格式默认背景颜色不同的颜色背景（PDF 和 SVG 为白色，光栅为透明）嵌入输出图像（如果不嵌入，背景将使用输出渲染系统的默认值，但依赖背景颜色的内容将使用指定的背景颜色进行渲染）。 |
| [ExportAllLayoutContent](../../aspose.cad.imageoptions/cadrasterizationoptions/exportalllayoutcontent/) { get; set; } | 获取或设置是否导出布局上位于绘图区域之外的实体。 |
| [GraphicsOptions](../../aspose.cad.imageoptions/vectorrasterizationoptions/graphicsoptions/) { get; set; } | 获取或设置在 pdf 中渲染位图的选项（如果 ContentAsBitmap 设置为 true）。 |
| [Layers](../../aspose.cad.imageoptions/cadrasterizationoptions/layers/) { get; set; } | 获取或设置要导出的 DXF 文件图层。 |
| [LayoutPageSizes](../../aspose.cad.imageoptions/vectorrasterizationoptions/layoutpagesizes/) { get; set; } | 获取或设置布局页面尺寸。 |
| [LayoutPlotAreas](../../aspose.cad.imageoptions/cadrasterizationoptions/layoutplotareas/) { get; set; } |  |
| [Layouts](../../aspose.cad.imageoptions/cadrasterizationoptions/layouts/) { get; set; } | 获取或设置 layoutName。 |
| [LineScale](../../aspose.cad.imageoptions/vectorrasterizationoptions/linescale/) { get; set; } | 获取或设置相对于原始粗细的线宽缩放因子值。如果希望在导出时将线宽增加 2 倍，则需要将该值设为 2。如果希望在导出时将线宽减小 4 倍，则需要将该值设为 0.25。 |
| [Margins](../../aspose.cad.imageoptions/vectorrasterizationoptions/margins/) { get; set; } | 获取或设置边距。 |
| [NoScaling](../../aspose.cad.imageoptions/cadrasterizationoptions/noscaling/) { get; set; } | 获取或设置导出时不进行缩放。 |
| [ObserverPoint](../../aspose.cad.imageoptions/cadrasterizationoptions/observerpoint/) { get; set; } | 获取或设置观察点。 |
| [PageDepth](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagedepth/) { get; set; } | 获取或设置页面深度。 |
| [PageHeight](../../aspose.cad.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | 获取或设置页面高度。 |
| [PageSize](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | 获取或设置页面大小。 |
| [PageSizingOptions](../../aspose.cad.imageoptions/cadrasterizationoptions/pagesizingoptions/) { get; set; } | 每页输出尺寸选项 |
| [PageWidth](../../aspose.cad.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | 获取或设置页面宽度。 |
| [PdfProductLocation](../../aspose.cad.imageoptions/cadrasterizationoptions/pdfproductlocation/) { get; set; } | PDF 产品位置 |
| [PenOptions](../../aspose.cad.imageoptions/cadrasterizationoptions/penoptions/) { get; set; } | 获取或设置笔选项。 |
| [Quality](../../aspose.cad.imageoptions/cadrasterizationoptions/quality/) { get; set; } | 获取或设置质量。 |
| [RelativePosition](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativeposition/) { get; set; } | 导出区域左上角相对于整个文档图像的位置，使用相对单位——0,0 为左上角，1,1 为文档图像的底部。 |
| [RelativeScale](../../aspose.cad.imageoptions/vectorrasterizationoptions/relativescale/) { get; set; } | 导出区域相对于整个文档图像的比例。计算方式为导出区域对应维度与导出文档较大维度的比率。 |
| [RenderMode](../../aspose.cad.imageoptions/cadrasterizationoptions/rendermode/) { get; set; } | 获取或设置 DXF/DWG 绘图的渲染模式：向量（适用于 2D 绘图，默认）或光栅（适用于导出 3D 模型）。 |
| [RenderMode3D](../../aspose.cad.imageoptions/cadrasterizationoptions/rendermode3d/) { get; set; } | 获取或设置 3D 渲染模式。 |
| [ScaleMethod](../../aspose.cad.imageoptions/cadrasterizationoptions/scalemethod/) { get; set; } | 获取或设置图像大小自动调整的缩放方法。 |
| [ShxCodePages](../../aspose.cad.imageoptions/cadrasterizationoptions/shxcodepages/) { get; set; } | 获取或设置 SHX 源。 |
| [ShxFonts](../../aspose.cad.imageoptions/cadrasterizationoptions/shxfonts/) { get; set; } | 获取或设置导出时使用的 SHX 字体路径。 |
| [ShxSources](../../aspose.cad.imageoptions/cadrasterizationoptions/shxsources/) { get; set; } | 获取或设置 SHX 源。 |
| [UnitType](../../aspose.cad.imageoptions/vectorrasterizationoptions/unittype/) { get; set; } | 获取或设置导出结果的单位类型。 |
| [VisibilityMode](../../aspose.cad.imageoptions/cadrasterizationoptions/visibilitymode/) { get; set; } | 获取或设置对象可见性检查模式 |
| [Zoom](../../aspose.cad.imageoptions/cadrasterizationoptions/zoom/) { get; set; } | 获取或设置缩放因子。允许相对于画布大小缩放绘图。值为 1 表示完全适配，值小于 1 可保留边距，值大于 1 可放大绘图。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DEFAULT_ZOOM_FACTOR](../../aspose.cad.imageoptions/cadrasterizationoptions/default_zoom_factor/) |  |
| [RenderResult](../../aspose.cad.imageoptions/cadrasterizationoptions/renderresult/) | 渲染结果处理程序。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| delegate [CadRenderHandler](../../aspose.cad.imageoptions/cadrasterizationoptions.cadrenderhandler) | 用于创建处理程序以捕获 CadRenderResult 的委托 |

### 另请参阅

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

