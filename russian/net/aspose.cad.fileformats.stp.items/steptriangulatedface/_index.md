---
title: "StepTriangulatedFace Класс"
linktitle: "StepTriangulatedFace"
articleTitle: "StepTriangulatedFace"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Stp.Items.StepTriangulatedFace класс. TriangulatedFace класс для файла STP. Класс представляет простую тесселированную грань. Тесселированная гео..."
type: docs
weight: 1060
url: "/net/aspose.cad.fileformats.stp.items/steptriangulatedface/"
keywords: "StepTriangulatedFace, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepTriangulatedFace class

TriangulatedFace класс для файла STP.
Класс представляет простую тесселированную грань.
Тесселированную геометрию можно определить либо через TRIANGULATED_FACE, либо через
COMPLEX_TRIANGULATED_FACE. Эти сущности похожи на сущности
TRIANGULATED_SURFACE_SET и COMPLEX_TRIANGULATED_SURFACE_SET.
Единственное различие между тесселированной гранью и тесселированным набором поверхностей
заключается в том, что у тесселированной грани есть дополнительный атрибут GeometricLink.
Этот необязательный атрибут может использоваться для сохранения точного определения
исходной точной геометрии.

```csharp
public class StepTriangulatedFace : StepTessellatedFace
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StepTriangulatedFace](steptriangulatedface/#constructor)() | Конструктор по умолчанию. |
| [StepTriangulatedFace](steptriangulatedface/#constructor_1)(string, StepCoordinatesList, int, List&lt;double[]&gt;, StepRepresentationItem, List&lt;int&gt;, List&lt;int[]&gt;) | Инициализирует новый экземпляр класса StepTriangulatedFace. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Получает площадь сущности. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/steptriangulatedface/coordinates/) { get; set; } |  |
| [GeometricLink](../../aspose.cad.fileformats.stp.items/steptriangulatedface/geometriclink/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/steptriangulatedface/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Получает длину сущности. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/steptriangulatedface/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/steptriangulatedface/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/steptriangulatedface/pnmax/) { get; set; } |  |
| [Triangles](../../aspose.cad.fileformats.stp.items/steptriangulatedface/triangles/) { get; set; } |  |
| [UId](../../aspose.cad.fileformats.stp.items/steprepresentationitem/uid/) { get; set; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../aspose.cad.fileformats.stp.items/steprepresentationitem/equals/)(StepRepresentationItem) |  |
| override [GetHashCode](../../aspose.cad.fileformats.stp.items/steprepresentationitem/gethashcode/)() |  |

### См. также

* class [StepTessellatedFace](../steptessellatedface/)
* namespace [Aspose.CAD.FileFormats.Stp.Items](../../aspose.cad.fileformats.stp.items/)
* assembly [Aspose.CAD](../../)

