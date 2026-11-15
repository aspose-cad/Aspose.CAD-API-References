---
title: "Класс Command"
linktitle: "Command"
articleTitle: "Command"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cgm.Commands.Command класс. Базовый класс для всех команд"
type: docs
weight: 600
url: "/net/aspose.cad.fileformats.cgm.commands/command/"
keywords: "Command, Aspose.CAD.FileFormats.Cgm.Commands, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Command class

Базовый класс для всех команд

```csharp
public abstract class Command
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ElementClass](../../aspose.cad.fileformats.cgm.commands/command/elementclass/) { get; } |  |
| [ElementId](../../aspose.cad.fileformats.cgm.commands/command/elementid/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| static [Assert](../../aspose.cad.fileformats.cgm.commands/command/assert/)(bool, string) |  |
| abstract [ReadFromBinary](../../aspose.cad.fileformats.cgm.commands/command/readfrombinary/)(IBinaryReader) | Читает двоичные данные из читателя |
| override [ToString](../../aspose.cad.fileformats.cgm.commands/command/tostring/)() |  |
| abstract [WriteAsBinary](../../aspose.cad.fileformats.cgm.commands/command/writeasbinary/)(IBinaryWriter) | Записывает/экспортирует команду в бинарном режиме |
| abstract [WriteAsClearText](../../aspose.cad.fileformats.cgm.commands/command/writeascleartext/)(IClearTextWriter) | Записывает/экспортирует команду в режиме чистого текста |

### См. также

* namespace [Aspose.CAD.FileFormats.Cgm.Commands](../../aspose.cad.fileformats.cgm.commands/)
* assembly [Aspose.CAD](../../)

