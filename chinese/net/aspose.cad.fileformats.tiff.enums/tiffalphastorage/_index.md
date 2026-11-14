---
title: "TiffAlphaStorage 枚举"
linktitle: "TiffAlphaStorage"
articleTitle: "TiffAlphaStorage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Tiff.Enums.TiffAlphaStorage 枚举。指定 tiff 文档的 alpha 存储方式。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.tiff.enums/tiffalphastorage/"
product_version: "26.9"
---
## TiffAlphaStorage enumeration

指定 tiff 文档的 alpha 存储方式。

```csharp
public enum TiffAlphaStorage : ushort
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Unspecified | `0` | alpha 未指定，已存储在 tiff 文件中。 |
| Associated | `1` | alpha 值以预乘形式存储。恢复 alpha 时可能会出现一些四舍五入效应，恢复后的值可能与原始值不同。 |
| Unassociated | `2` | alpha 值以非关联形式存储。这意味着恢复的 alpha 与存储到 tiff 中的完全相同。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Tiff.Enums](../../aspose.cad.fileformats.tiff.enums/)
* assembly [Aspose.CAD](../../)

