---
title: "CadLineTypeShapeFlag Перечисление"
linktitle: "CadLineTypeShapeFlag"
articleTitle: "CadLineTypeShapeFlag"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadLineTypeShapeFlag enum. Флаг формы типа линии."
type: docs
weight: 280
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadlinetypeshapeflag/"
product_version: "26.9"
---
## CadLineTypeShapeFlag enumeration

Флаг формы типа линии.

```csharp
[Flags]
public enum CadLineTypeShapeFlag : short
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Флаги не установлены. Простой элемент типа линии: тире, точка или пробел. |
| RotationIsAbsolute | `1` | Угол поворота встроенного текста или формы является абсолютным относительно начала координат. |
| IsText | `2` | Элемент типа линии содержит встроенную строку текста. |
| IsShape | `4` | Элемент типа линии содержит встроенную форму (ссылается на номер формы из файла SHX). |
| RotationIsUpright | `8` | Встроенный текст или форма отображаются вертикально (ориентация, удобная для чтения). |

### См. также

* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

