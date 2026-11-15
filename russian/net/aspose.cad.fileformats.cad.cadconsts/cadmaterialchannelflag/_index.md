---
title: "CadMaterialChannelFlag Enum"
linktitle: "CadMaterialChannelFlag"
articleTitle: "CadMaterialChannelFlag"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialChannelFlag enum. Флаги, указывающие, какие каналы текстур активны для CadMaterial. Можно комбинировать несколько флагов..."
type: docs
weight: 300
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialchannelflag/"
product_version: "26.9"
---
## CadMaterialChannelFlag enumeration

Флаги, указывающие, какие каналы текстур активны для [`CadMaterial`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterial/). Несколько флагов можно комбинировать.

```csharp
[Flags]
public enum CadMaterialChannelFlag : byte
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Нет активных каналов текстур. |
| UseDiffuse | `1` | Канал диффузной текстуры активен. |
| UseSpecular | `2` | Канал спекулярной текстуры активен. |
| UseReflection | `4` | Канал отражения текстуры активен. |
| UseOpacity | `8` | Канал непрозрачности текстуры активен. |
| UseBump | `10` | Канал выпуклостей текстуры активен. |
| UseRefraction | `20` | Канал текстуры преломления активен. |
| UseAll | `3F` | Все каналы текстур активны. |

### См. также

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

