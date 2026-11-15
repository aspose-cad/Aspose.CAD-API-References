---
title: "CadMaterialMap Класс"
linktitle: "CadMaterialMap"
articleTitle: "CadMaterialMap"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadMaterialMap класс. Представляет карту материалного компонента, определяющую источник текстуры и контролирующую, как она проецируется..."
type: docs
weight: 930
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/"
keywords: "CadMaterialMap, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadMaterialMap class

Представляет карту компонента материала, определяющую источник текстуры и контролирующую, как она проецируется, мозаичится и трансформируется на поверхности объекта.

```csharp
public class CadMaterialMap
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadMaterialMap](cadmaterialmap/)() | Инициализирует новый экземпляр класса `CadMaterialMap`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoTransform](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/autotransform/) { get; set; } | Автоматический режим трансформации маппера. Несколько значений могут быть объединены с помощью логического ИЛИ. |
| [BlendFactor](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/blendfactor/) { get; set; } | Коэффициент смешения для карты изображения, от 0.0 до 1.0. |
| [FileName](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/filename/) { get; set; } | Путь к файлу изображения, используемому в качестве источника карты. |
| [Projection](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/projection/) { get; set; } | Проекция отображения, используемая при применении карты к поверхности. |
| [Source](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/source/) { get; set; } | Источник данных материалной карты. |
| [Tiling](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/tiling/) { get; set; } | Метод плитки, применяемый при проецировании карты на поверхность. |
| [TransformMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/transformmatrix/) { get; set; } | Матрица преобразования отображателя, сохранённая как плоский список из 16 значений. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [IdentityMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/identitymatrix/) | Матрица преобразования единичного преобразования: без вращения, без масштабирования, без перемещения. Используется как запасной вариант, когда [`TransformMatrix`](./transformmatrix/) не содержит ровно 16 значений. |

### См. также

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

