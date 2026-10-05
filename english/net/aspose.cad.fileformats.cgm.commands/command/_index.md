---
title: "Command Class"
linktitle: "Command"
articleTitle: "Command"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cgm.Commands.Command class. Base class for all commands"
type: docs
weight: 600
url: "/net/aspose.cad.fileformats.cgm.commands/command/"
keywords: "Command, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Command class

Base class for all commands

```csharp
public abstract class Command
```

## Properties

| Name | Description |
| --- | --- |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| static [Assert](../../aspose.cad.fileformats.cgm.commands/command/assert/)(bool, string) |  |
| abstract [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/command/readfrombinary/)(IBinaryReader) | Reads the binary data from the reader |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/command/tostring/)() |  |
| abstract [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/command/writeasbinary/)(IBinaryWriter) | Writes/exports the command as binary mode |
| abstract [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/command/writeascleartext/)(IClearTextWriter) | Writes/exports the command as clear text mode |

### See Also

* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

