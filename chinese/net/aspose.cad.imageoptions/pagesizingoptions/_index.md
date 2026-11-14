---
title: "PageSizingOptions 类"
linktitle: "PageSizingOptions"
articleTitle: "PageSizingOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.PageSizingOptions 类。"
type: docs
weight: 340
url: "/net/aspose.cad.imageoptions/pagesizingoptions/"
keywords: "PageSizingOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PageSizingOptions class



```csharp
public class PageSizingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PageSizingOptions](pagesizingoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Depth](../../aspose.cad.imageoptions/pagesizingoptions/depth/) { get; set; } | 输出页面的深度。如果设置了此值，则不会使用源缩放和单位类型覆盖，因为页面大小已显式设置。 |
| [Height](../../aspose.cad.imageoptions/pagesizingoptions/height/) { get; set; } | 输出页面的高度。如果设置了此值，则不会使用源缩放和单位类型覆盖，因为页面大小已显式设置。 |
| [LayoutName](../../aspose.cad.imageoptions/pagesizingoptions/layoutname/) { get; set; } | 这些选项应应用于的页面名称。如果为 NULL，则列表中的第一个 PageSizingOptions 将应用于任何应导出但没有对应名称的 PageSizingOptions 的页面。 |
| [LegacySizingMode](../../aspose.cad.imageoptions/pagesizingoptions/legacysizingmode/) { get; set; } | 如果为 true，Aspose.CAD 将对输出格式使用传统尺寸模式。 |
| [Margins](../../aspose.cad.imageoptions/pagesizingoptions/margins/) { get; set; } | 当前页面的边距大小。如果通过 Width\\Height\\Depth 显式提供输出页面大小，则从尺寸中减去边距。如果输出页面大小是根据源尺寸计算的，则会添加边距。 |
| [MarginsUnitType](../../aspose.cad.imageoptions/pagesizingoptions/marginsunittype/) { get; set; } | 边距的单位类型。如果未设置，将默认使用输出格式的单位。 |
| [OverrideOutputUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overrideoutputunittype/) { get; set; } | 覆盖输出格式的测量单位。例如，PDF 的单位是点，等于英寸的 1/72。1×1 英寸的源将输出为 72×72 到 PDF。如果将 OverrideOutputUnitType 设置为 Inch，输出将为 1×1。 |
| [OverrideSourceUnitType](../../aspose.cad.imageoptions/pagesizingoptions/overridesourceunittype/) { get; set; } | 覆盖源页面的测量单位。如果源是 1×1 英寸，而此选项设置为 Meters，则假定源为 1×1 米。 |
| [SourceScaling](../../aspose.cad.imageoptions/pagesizingoptions/sourcescaling/) { get; set; } | 在不考虑单位的情况下，源尺寸应放大多少。如果源是 1×1 英寸，且 SourceScaling = 10，则源被解释为 10×10 英寸。 |
| [Width](../../aspose.cad.imageoptions/pagesizingoptions/width/) { get; set; } | 输出页面的宽度。如果设置了此值，则不会使用源缩放和单位类型覆盖，因为页面大小已显式设置。 |
| [Zoom](../../aspose.cad.imageoptions/pagesizingoptions/zoom/) { get; set; } | 这是一个缩放因子，用于使绘图稍微变小，以便将垂直和水平线适配到画布中。默认值为 1 - (0.0026 * 2)，因为在 Autocad 的 ZOOM EXTENTS 命令期间，每侧会留下约 0.26% 的间隙。 |

### 另请参阅

* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

