---
title: "CadMaterialMapTiling Enum"
linktitle: "CadMaterialMapTiling"
articleTitle: "CadMaterialMapTiling"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadConsts.CadMaterialMapTiling enum. Указывает метод укладки для CadMaterialMap."
type: docs
weight: 360
url: "/net/aspose.cad.fileformats.cad.cadconsts/cadmaterialmaptiling/"
product_version: "26.9"
---
## CadMaterialMapTiling enumeration

Указывает метод укладки для [`CadMaterialMap`](../../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/).

```csharp
public enum CadMaterialMapTiling : byte
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Inherit | `0` | Наследовать настройку укладки от родителя. |
| Tile | `1` | Повторяет material map вдоль оси изображения (по умолчанию). |
| Crop | `2` | Обрезает material map ниже 0.0 и выше 1.0 по оси изображения. |
| Clamp | `3` | Ограничивает material map между 0.0 и 1.0 по оси изображения. |
| Mirror | `4` | Операция grip является зеркальной. |

### См. также

* [Tiling](../tiling/)
* namespace [Aspose.CAD.FileFormats.Cad.CadConsts](../../aspose.cad.fileformats.cad.cadconsts/)
* assembly [Aspose.CAD](../../)

