---
title: "ResourceBlock 类"
linktitle: "ResourceBlock"
articleTitle: "ResourceBlock"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Psd.ResourceBlock 类。资源块。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.psd/resourceblock/"
keywords: "ResourceBlock, Aspose.CAD.FileFormats.Psd, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ResourceBlock class

资源块。

```csharp
public abstract class ResourceBlock
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [DataSize](../../aspose.cad.fileformats.psd/resourceblock/datasize/) { get; } | 获取资源数据的字节大小。 |
| [ID](../../aspose.cad.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| abstract [MinimalVersion](../../aspose.cad.fileformats.psd/resourceblock/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
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

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [ResourceBlockState](../../aspose.cad.fileformats.psd/resourceblock.resourceblockstate) | 表示资源块状态。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Psd](../../aspose.cad.fileformats.psd/)
* assembly [Aspose.CAD](../../)

