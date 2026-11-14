---
title: "MemoryImage 结构体"
linktitle: "MemoryImage"
articleTitle: "MemoryImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Memory.MemoryImage 结构体。表示以内存字节数组存储的图像文件"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.glb.memory/memoryimage/"
product_version: "26.9"
---
## MemoryImage struct

表示以内存字节数组形式存储的图像文件

```csharp
public struct MemoryImage : IEquatable<MemoryImage>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MemoryImage](memoryimage/)(ArraySegment&lt;byte&gt;) | 初始化 MemoryImage 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| Content { get; } | 获取图像的文件字节。 |
| Empty { get; } |  |
| FileExtension { get; } | 获取此图像最合适的扩展名字符串。 |
| IsDds { get; } | 获取一个值，指示此对象是否表示有效的 DDS 图像。 |
| IsEmpty { get; } |  |
| IsExtendedFormat { get; } | 获取一个值，指示此对象是否表示由 glTF 扩展支持的图像。 |
| IsJpg { get; } | 获取一个值，指示此对象是否表示有效的 JPG 图像。 |
| IsKtx2 { get; } | 获取一个值，指示此对象是否表示有效的 KTX2 图像。 |
| IsPng { get; } | 获取一个值，指示此对象是否表示有效的 PNG 图像。 |
| IsValid { get; } | 获取一个值，指示此对象是否表示有效的图像。 |
| IsWebp { get; } | 获取一个值，指示此对象是否表示有效的 WEBP 图像。 |
| MimeType { get; } | 获取此图像最合适的 Mime 类型字符串。 |
| SourcePath { get; } | 获取此图像的源路径，或 **null**。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| AreEqual(MemoryImage, MemoryImage) |  |
| Equals(MemoryImage) |  |
| Equals(object) |  |
| GetHashCode() |  |
| IsImageOfType(string) | 标识特定类型的图像。 |
| Open() | 打开图像文件以读取其内容 |
| SaveToFile(string) | 将此 `MemoryImage` 中存储的图像保存到文件。 |
| ToDebuggerDisplay() |  |
| TryParseMime64(string, out MemoryImage) | 尝试将 Mime64 字符串解析为 `MemoryImage` |

## Operators

| 名称 | 描述 |
| --- | --- |
| 运算符 MemoryImage |  |
| 运算符 MemoryImage |  |
| 运算符 MemoryImage |  |
| 运算符 == |  |
| 运算符 != |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

