---
title: "StepComplexTriangulatedSurfaceSet класс"
linktitle: "StepComplexTriangulatedSurfaceSet"
articleTitle: "StepComplexTriangulatedSurfaceSet"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Stp.Items.StepComplexTriangulatedSurfaceSet класс. ComplexTriangulatedSurfaceSet класс для файла STP. Класс представляет сложный tessella..."
type: docs
weight: 230
url: "/net/aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/"
keywords: "StepComplexTriangulatedSurfaceSet, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepComplexTriangulatedSurfaceSet class

ComplexTriangulatedSurfaceSet класс для файла STP.
Класс представляет сложный теселлированный набор поверхностей.
Тесселированную геометрию можно определить либо через TRIANGULATED_FACE, либо через
COMPLEX_TRIANGULATED_FACE. Эти сущности похожи на сущности
TRIANGULATED_SURFACE_SET и COMPLEX_TRIANGULATED_SURFACE_SET.
Единственное различие между тесселированной гранью и тесселированным набором поверхностей
заключается в том, что у тесселированной грани есть дополнительный атрибут GeometricLink.
Этот необязательный атрибут может использоваться для сохранения точного определения
исходной точной геометрии.

```csharp
public class StepComplexTriangulatedSurfaceSet : StepTessellatedItem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StepComplexTriangulatedSurfaceSet](stepcomplextriangulatedsurfaceset/)(string, StepCoordinatesList, int, List&lt;double[]&gt;, List&lt;int&gt;, List&lt;int[]&gt;, List&lt;int[]&gt;) | Инициализирует новый экземпляр класса StepComplexTriangulatedSurfaceSet. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Получает площадь сущности. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/coordinates/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Получает длину сущности. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/pnmax/) { get; set; } |  |
| [TriangleFans](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/trianglefans/) { get; set; } |  |
| [TriangleStrips](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/trianglestrips/) { get; set; } |  |
| [UId](../../aspose.cad.fileformats.stp.items/steprepresentationitem/uid/) { get; set; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../aspose.cad.fileformats.stp.items/steprepresentationitem/equals/)(StepRepresentationItem) |  |
| override [GetHashCode](../../aspose.cad.fileformats.stp.items/steprepresentationitem/gethashcode/)() |  |

### См. также

* class [StepTessellatedItem](../steptessellateditem/)
* namespace [Aspose.CAD.FileFormats.Stp.Items](../../aspose.cad.fileformats.stp.items/)
* assembly [Aspose.CAD](../../)

