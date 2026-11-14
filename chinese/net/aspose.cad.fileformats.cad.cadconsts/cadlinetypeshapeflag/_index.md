---
title: "CadLineTypeShapeFlag 枚举"
linktitle: "CadLineTypeShapeFlag"
articleTitle: "CadLineTypeShapeFlag"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadLineTypeShapeFlag 枚举。线型形状标志。"
type: docs
weight: 280
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadlinetypeshapeflag/"
product_version: "26.9"
---
## CadLineTypeShapeFlag enumeration

线型形状标志。

```csharp
[Flags]
public enum CadLineTypeShapeFlag : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 未设置标志。一个简单的线型元素：短划线、点或空格。 |
| RotationIsAbsolute | `1` | 嵌入文本或形状的旋转角度是相对于原点的绝对值。 |
| IsText | `2` | 该线型元素包含嵌入的文本字符串。 |
| IsShape | `4` | 该线型元素包含嵌入的形状（通过 SHX 文件中的形状编号引用）。 |
| RotationIsUpright | `8` | 嵌入的文本或形状以正立方式显示（易于阅读的方向）。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

