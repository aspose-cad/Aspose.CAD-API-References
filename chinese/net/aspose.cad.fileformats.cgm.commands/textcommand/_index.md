---
title: "TextCommand 类"
linktitle: "TextCommand"
articleTitle: "TextCommand"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cgm.Commands.TextCommand 类。"
type: docs
weight: 2030
url: "/net/aspose.cad.fileformats.cgm.commands/textcommand/"
keywords: "TextCommand, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TextCommand class



```csharp
public abstract class TextCommand : Command
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |
| [Position](../../aspose.cad.fileformats.cgm.commands/textcommand/position/) { get; } | 应显示字符串的位置 |
| [Text](../../aspose.cad.fileformats.cgm.commands/textcommand/text/) { get; } | 要显示的字符串 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/command/readfrombinary/)(IBinaryReader) | 从读取器读取二进制数据 |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/textcommand/tostring/)() |  |
| abstract [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/command/writeasbinary/)(IBinaryWriter) | 以二进制模式写入/导出命令 |
| abstract [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/command/writeascleartext/)(IClearTextWriter) | 以明文模式写入/导出命令 |

### 另请参阅

* class [Command](../command/)
* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

