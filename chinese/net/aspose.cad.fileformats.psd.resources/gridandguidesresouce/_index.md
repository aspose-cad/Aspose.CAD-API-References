---
title: "GridAndGuidesResouce 类"
linktitle: "GridAndGuidesResouce"
articleTitle: "GridAndGuidesResouce"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Psd.Resources.GridAndGuidesResouce 类。表示网格和参考线资源。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.psd.resources/gridandguidesresouce/"
keywords: "GridAndGuidesResouce, Aspose.CAD.FileFormats.Psd.Resources, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GridAndGuidesResouce class

表示网格和参考线资源。

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | 初始化 `GridAndGuidesResouce` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [DataSize](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | 获取资源数据的字节大小。 |
| [GridCycleX](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | 获取或设置水平网格周期。默认值为 576。 |
| [GridCycleY](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | 获取或设置垂直网格周期。默认值为 576。 |
| [GuideCount](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | 获取参考线资源块计数。 |
| [HeaderVersion](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | 获取或设置头部版本。此值应始终为 1。 |
| [ID](../../aspose.cad.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| override [MinimalVersion](../../aspose.cad.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.cad.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。 |
| [Signature](../../aspose.cad.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为 '8BIM'。 |
| [Size](../../aspose.cad.fileformats.psd/resourceblock/size/) { get; } | 获取资源块的字节大小（包括其数据）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Save](../../aspose.cad.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| virtual [ValidateValues](../../aspose.cad.fileformats.psd/resourceblock/validatevalues/)() | 验证资源值。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ResouceBlockSignature](../../aspose.cad.fileformats.psd/resourceblock/resouceblocksignature/) | 资源签名。 |

### 另请参阅

* class [ResourceBlock](../../aspose.cad.fileformats.psd/resourceblock/)
* namespace [Aspose.CAD.FileFormats.Psd.Resources](../../aspose.cad.fileformats.psd.resources/)
* assembly [Aspose.CAD](../../)

