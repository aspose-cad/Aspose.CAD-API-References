---
title: "PolyBezier 类"
linktitle: "PolyBezier"
articleTitle: "PolyBezier"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cgm.Commands.PolyBezier 类. Class=4, ElementId=26"
type: docs
weight: 1680
url: "/net/aspose.cad.fileformats.cgm.commands/polybezier/"
keywords: "PolyBezier, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PolyBezier class

类=4, 元素ID=26

```csharp
public class PolyBezier : Command
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PolyBezier](polybezier/#constructor)(CgmFile) | 初始化 PolyBezier 类的新实例。 |
| [PolyBezier](polybezier/#constructor_1)(CgmFile, int, IEnumerable&lt;BezierCurve&gt;) | 初始化 PolyBezier 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ContinuityIndicator](../../aspose.cad.fileformats.cgm.commands/polybezier/continuityindicator/) { get; set; } | 1：不连续，2：连续，>2：保留给已注册的值 |
| [Curves](../../aspose.cad.fileformats.cgm.commands/polybezier/curves/) { get; set; } |  |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/polybezier/readfrombinary/)(IBinaryReader) |  |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/command/tostring/)() |  |
| override [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/polybezier/writeasbinary/)(IBinaryWriter) |  |
| override [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/polybezier/writeascleartext/)(IClearTextWriter) |  |

### 另请参阅

* class [Command](../command/)
* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

