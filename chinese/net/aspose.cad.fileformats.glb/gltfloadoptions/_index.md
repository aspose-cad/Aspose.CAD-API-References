---
title: "GltfLoadOptions 类"
linktitle: "GltfLoadOptions"
articleTitle: "GltfLoadOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.GltfLoadOptions 类。表示 GLTF/GLB 图像的加载选项。"
type: docs
weight: 240
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/"
keywords: "GltfLoadOptions, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## GltfLoadOptions class

表示 GLTF/GLB 图像的加载选项。

```csharp
public class GltfLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GltfLoadOptions](gltfloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.cad/loadoptions/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [CustomFontFolderOptions](../../aspose.cad/loadoptions/customfontfolderoptions/) { get; set; } | 控制自定义字体文件夹行为的选项。 |
| [CustomFontFolders](../../aspose.cad/loadoptions/customfontfolders/) { get; set; } | 设置自定义字体文件夹。传入 null 可重置为默认文件夹。 |
| [DataBackgroundColor](../../aspose.cad/loadoptions/databackgroundcolor/) { get; set; } | 获取或设置 [`Image`](../../aspose.cad/image/) 背景 [`Color`](../../aspose.cad/color/)。 |
| [Errors](../../aspose.cad/loadoptions/errors/) { get; } | 获取加载错误的列表。 |
| [IgnoreErrors](../../aspose.cad/loadoptions/ignoreerrors/) { get; set; } | 是否忽略加载错误。 |
| [RecoverMalformedCifMif](../../aspose.cad/loadoptions/recovermalformedcifmif/) { get; set; } | 是否恢复未转义的 CIF (U+XXXX) 和 MIF (M+nXXXX) 字符表示法 |
| [SkipTangentsCalculation](../../aspose.cad.fileformats.glb/gltfloadoptions/skiptangentscalculation/) { get; set; } | 是否跳过 GLTF/GLB 格式的切线图计算。默认值：False。 |
| [SkipValidation](../../aspose.cad.fileformats.glb/gltfloadoptions/skipvalidation/) { get; set; } | 是否跳过 GLTF/GLB 格式的验证。默认值：False。 |
| [SpecifiedEncoding](../../aspose.cad/loadoptions/specifiedencoding/) { get; set; } | 获取或设置指定的编码。 |
| [SpecifiedMifEncoding](../../aspose.cad/loadoptions/specifiedmifencoding/) { get; set; } | 获取或设置 MIF 字符的编码 |
| [UnloadOnDispose](../../aspose.cad/loadoptions/unloadondispose/) { get; set; } | 在调用 Dispose 时是否卸载所有数据并释放内存 |
| [VectorizationOptions](../../aspose.cad/loadoptions/vectorizationoptions/) { get; set; } | 获取或设置矢量化选项。 |

### 另请参阅

* class [LoadOptions](../../aspose.cad/loadoptions/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

