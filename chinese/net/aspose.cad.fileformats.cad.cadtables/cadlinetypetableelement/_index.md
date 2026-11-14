---
title: "CadLineTypeTableElement 类"
linktitle: "CadLineTypeTableElement"
articleTitle: "CadLineTypeTableElement"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadTables.CadLineTypeTableElement 类。表示在 CadLineTypeTableObject 中定义的线型模式的单个元素。"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/"
keywords: "CadLineTypeTableElement, Aspose.CAD.FileFormats.Cad.CadTables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadLineTypeTableElement class

表示在 [`CadLineTypeTableObject`](../cadlinetypetableobject/) 中定义的线型模式的单个元素。

```csharp
public class CadLineTypeTableElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadLineTypeTableElement](cadlinetypetableelement/)() | 初始化 `CadLineTypeTableElement` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DashDotLength](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/dashdotlength/) { get; set; } | 元素的长度：正值 = 短划线，负值 = 空格，零 = 点。 |
| [Offset](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/offset/) { get; set; } | 嵌入文本或形状相对于线的 X、Y 偏移。 |
| [RotationAngle](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/rotationangle/) { get; set; } | 嵌入文本或形状的旋转角度。 |
| [Scale](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/scale/) { get; set; } | 嵌入文本或形状的比例因子。 |
| [ShapeFlag](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/shapeflag/) { get; set; } | 指示元素类型和旋转模式的标志。 |
| [ShapeNumber](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/shapenumber/) { get; set; } | 来自 SHX 文件的形状编号，或文本元素在字符串区域的文本偏移。 |
| [StyleHandle](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/stylehandle/) { get; set; } | 引用的文本样式或 SHX 字体的句柄。当 [`ShapeFlag`](./shapeflag/) 为 IsText 或 IsShape 时使用。 |
| [Text](../../aspose.cad.fileformats.cad.cadtables/cadlinetypetableelement/text/) { get; set; } | 嵌入的文本字符串。当 [`ShapeFlag`](./shapeflag/) 为 IsText 时使用。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadTables](../../aspose.cad.fileformats.cad.cadtables/)
* assembly [Aspose.CAD](../../)

