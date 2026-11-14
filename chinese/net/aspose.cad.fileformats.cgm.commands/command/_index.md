---
title: "Command 类"
linktitle: "Command"
articleTitle: "Command"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cgm.Commands.Command 类。所有命令的基类"
type: docs
weight: 600
url: "/net/aspose.cad.fileformats.cgm.commands/command/"
keywords: "Command, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Command class

所有命令的基类

```csharp
public abstract class Command
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Assert](../../aspose.cad.fileformats.cgm.commands/command/assert/)(bool, string) |  |
| abstract [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/command/readfrombinary/)(IBinaryReader) | 从读取器读取二进制数据 |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/command/tostring/)() |  |
| abstract [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/command/writeasbinary/)(IBinaryWriter) | 以二进制模式写入/导出命令 |
| abstract [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/command/writeascleartext/)(IClearTextWriter) | 以明文模式写入/导出命令 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

