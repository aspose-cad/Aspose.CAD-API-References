---
title: "UnknownResource 类"
linktitle: "UnknownResource"
articleTitle: "UnknownResource"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Psd.Resources.UnknownResource 类。未知资源。当资源块未被识别时，将创建此资源块。"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.psd.resources/unknownresource/"
keywords: "UnknownResource, Aspose.CAD.FileFormats.Psd.Resources, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## UnknownResource class

未知资源。当资源块未被识别时，将创建此资源块。

```csharp
public sealed class UnknownResource : ResourceBlock
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Data](../../aspose.cad.fileformats.psd.resources/unknownresource/data/) { get; } | 获取资源数据。 |
| override [DataSize](../../aspose.cad.fileformats.psd.resources/unknownresource/datasize/) { get; } | 获取资源数据的字节大小。 |
| [ID](../../aspose.cad.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| override [MinimalVersion](../../aspose.cad.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
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

