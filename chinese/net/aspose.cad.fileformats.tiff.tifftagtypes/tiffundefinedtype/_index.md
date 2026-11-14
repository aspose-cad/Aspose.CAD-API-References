---
title: "TiffUndefinedType 类"
linktitle: "TiffUndefinedType"
articleTitle: "TiffUndefinedType"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Tiff.TiffTagTypes.TiffUndefinedType 类。tiff 未定义类型。"
type: docs
weight: 150
url: "/net/aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/"
keywords: "TiffUndefinedType, Aspose.CAD.FileFormats.Tiff.TiffTagTypes, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TiffUndefinedType class

tiff undefined 类型。

```csharp
public class TiffUndefinedType : TiffDataType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffUndefinedType](tiffundefinedtype/#constructor)(TiffTags) | 初始化 `TiffUndefinedType` 类的新实例。 |
| [TiffUndefinedType](tiffundefinedtype/#constructor_1)(ushort) | 初始化 `TiffUndefinedType` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignedDataSize](../../aspose.cad.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | 获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。 |
| override [Count](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/count/) { get; } | 获取元素的计数。 |
| [Data](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/data/) { get; set; } | 获取或设置数据。 |
| override [DataSize](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/datasize/) { get; } | 获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。 |
| [Id](../../aspose.cad.fileformats.tiff/tiffdatatype/id/) { get; } | 获取标签 ID 的整数表示。 |
| [IsValid](../../aspose.cad.fileformats.tiff/tiffdatatype/isvalid/) { get; } | 获取一个值，指示标签数据是否有效。有效的标签包含可保留的数据。无效的标签无法存储。 |
| [TagId](../../aspose.cad.fileformats.tiff/tiffdatatype/tagid/) { get; } | 获取标签 ID。 |
| override [TagType](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/tagtype/) { get; } | 获取标签类型。 |
| override [Value](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/value/) { get; set; } | 获取或设置此数据类型包含的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.cad.fileformats.tiff/tiffdatatype/compareto/)(object) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于该对象之前、之后，还是与其处于相同位置。 |
| virtual [DeepClone](../../aspose.cad.fileformats.tiff/tiffdatatype/deepclone/)() | 对该实例进行深度克隆。 |
| [GetAlignedDataSize](../../aspose.cad.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | 获取在 4 字节（int）或 8 字节（long）边界对齐的数据大小。 |
| override [ToString](../../aspose.cad.fileformats.tiff/tiffdatatype/tostring/)() | 返回表示此实例的字符串。 |
| override [WriteAdditionalData](../../aspose.cad.fileformats.tiff.tifftagtypes/tiffundefinedtype/writeadditionaldata/)(TiffStreamWriter) | 写入附加标签数据。 |
| [WriteTag](../../aspose.cad.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | 写入标签数据。 |

### 另请参阅

* class [TiffDataType](../../aspose.cad.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.CAD.FileFormats.Tiff.TiffTagTypes](../../aspose.cad.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.CAD](../../)

