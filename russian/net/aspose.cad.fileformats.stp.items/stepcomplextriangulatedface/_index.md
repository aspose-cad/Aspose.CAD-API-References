---
title: "StepComplexTriangulatedFace Класс"
linktitle: "StepComplexTriangulatedFace"
articleTitle: "StepComplexTriangulatedFace"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Stp.Items.StepComplexTriangulatedFace класс. ComplexTriangulatedFace класс для файла STP. Класс представляет сложную фасетную поверхность. A ..."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/"
keywords: "StepComplexTriangulatedFace, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepComplexTriangulatedFace class

ComplexTriangulatedFace класс для файла STP.
Класс представляет сложную фасетную поверхность.
Тесселированную геометрию можно определить либо через TRIANGULATED_FACE, либо через
COMPLEX_TRIANGULATED_FACE. Эти сущности похожи на сущности
TRIANGULATED_SURFACE_SET и COMPLEX_TRIANGULATED_SURFACE_SET.
Единственное различие между тесселированной гранью и тесселированным набором поверхностей
заключается в том, что у тесселированной грани есть дополнительный атрибут GeometricLink.
Этот необязательный атрибут может использоваться для сохранения точного определения
исходной точной геометрии.

```csharp
public class StepComplexTriangulatedFace : StepTessellatedFace
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StepComplexTriangulatedFace](stepcomplextriangulatedface/#constructor)() | Конструктор по умолчанию. |
| [StepComplexTriangulatedFace](stepcomplextriangulatedface/#constructor_1)(string, StepCoordinatesList, int, List&lt;double[]&gt;, StepRepresentationItem, List&lt;int&gt;, List&lt;int[]&gt;, List&lt;int[]&gt;) | Инициализирует новый экземпляр класса StepComplexTriangulatedFace. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Получает площадь сущности. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/coordinates/) { get; set; } |  |
| [GeometricLink](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/geometriclink/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Получает длину сущности. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/pnmax/) { get; set; } |  |
| [TriangleFans](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/trianglefans/) { get; set; } |  |
| [TriangleStrips](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/trianglestrips/) { get; set; } |  |
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

