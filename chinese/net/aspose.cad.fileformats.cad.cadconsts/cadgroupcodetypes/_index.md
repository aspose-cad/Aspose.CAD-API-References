---
title: "CadGroupCodeTypes 枚举"
linktitle: "CadGroupCodeTypes"
articleTitle: "CadGroupCodeTypes"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadGroupCodeTypes 枚举。 Cad 组代码值类型"
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadgroupcodetypes/"
product_version: "26.9"
---
## CadGroupCodeTypes enumeration

Cad 组代码值类型

```csharp
public enum CadGroupCodeTypes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Unknown | `0` | 未知组 |
| StringEx | `1` | 字符串（随着 AutoCAD 2000 中扩展符号名称的引入，255 字符的限制已增加到 2049 个单字节字符，不包括行尾的换行符） |
| String255 | `2` | 字符串（最大 255 个字符；Unicode 字符串更少） |
| StringHexHandle | `3` | 表示十六进制（hex）句柄值的字符串 |
| ArbitraryText | `4` | 任意文本字符串 |
| StringHexBinaryChunk | `5` | 表示二进制块十六进制值的字符串 |
| String | `6` | 字符串值 |
| Comment | `7` | 注释（字符串） |
| StringHexIds | `8` | 表示十六进制对象 ID 的字符串 |
| DoublePrecision3DPoint | `9` | 双精度 3D 点值 |
| DoublePrecisionFloat | `10` | 双精度浮点值 |
| DoublePrecisionScalarFloat | `11` | 双精度标量浮点值 |
| Int16 | `12` | 16 位整数值 |
| Int32 | `13` | 32 位整数值 |
| Int64 | `14` | 64 位整数值 |
| Long | `15` | 长整数值（32 位） |
| BooleanFlag | `16` | 布尔标志值 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

