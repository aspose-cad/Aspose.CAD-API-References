---
title: "Перечисление StyleSimulations"
linktitle: "StyleSimulations"
articleTitle: "StyleSimulations"
second_title: "Aspose.CAD для .NET справка API"
description: "Перечисление Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.StyleSimulations. Симуляции стиля. Синтетические симуляции стиля могут применяться к форме ..."
type: docs
weight: 310
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/stylesimulations/"
product_version: "26.9"
---
## StyleSimulations enumeration

Симуляции стиля.
Синтетические симуляции стиля могут применяться к форме глифов
с помощью атрибута StyleSimulations.
Симуляции стиля могут применяться в дополнение к разработанному стилю шрифта.
Значение по умолчанию для атрибута StyleSimulations — None,
в этом случае формы глифов не изменяются от их оригинального дизайна.

```csharp
public enum StyleSimulations
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Отсутствие. Формы глифов не изменяются от их оригинального дизайна. |
| ItalicSimulation | `1` | Симуляция наклона. Синтетическое наклонение применяется к глифам со значением IsSideways, равным false, путём наклона верхнего края выравнивающего бокса символа на 20° вправо относительно базовой линии символа. |
| BoldSimulation | `2` | Симуляция полужирного начертания. Синтетическое утолщение применяется путём геометрического расширения штрихов глифов на 1 % от размера EM для каждой из двух границ штриха, так чтобы центры штрихов оставались в том же положении относительно координатной системы символа. |
| BoldItalicSimulation | `3` | Симуляция полужирного наклона. Применяются как BoldSimulation, так и ItalicSimulation. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

