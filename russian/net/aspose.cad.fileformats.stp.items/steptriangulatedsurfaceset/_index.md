---
title: "StepTriangulatedSurfaceSet Класс"
linktitle: "StepTriangulatedSurfaceSet"
articleTitle: "StepTriangulatedSurfaceSet"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Stp.Items.StepTriangulatedSurfaceSet класс. Класс TriangulatedSurfaceSet для файла STP. Класс представляет простой тесселированный набор поверхностей..."
type: docs
weight: 1070
url: "/net/aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/"
keywords: "StepTriangulatedSurfaceSet, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepTriangulatedSurfaceSet class

Класс TriangulatedSurfaceSet для файла STP.
Класс представляет простой тесселированный набор поверхностей.
Тесселированную геометрию можно определить либо через TRIANGULATED_FACE, либо через
COMPLEX_TRIANGULATED_FACE. Эти сущности похожи на сущности
TRIANGULATED_SURFACE_SET и COMPLEX_TRIANGULATED_SURFACE_SET.
Единственное различие между тесселированной гранью и тесселированным набором поверхностей
заключается в том, что у тесселированной грани есть дополнительный атрибут GeometricLink.
Этот необязательный атрибут может использоваться для сохранения точного определения
исходной точной геометрии.

```csharp
public class StepTriangulatedSurfaceSet : StepTessellatedItem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StepTriangulatedSurfaceSet](steptriangulatedsurfaceset/)(string, StepCoordinatesList, int, List&lt;double[]&gt;, List&lt;int&gt;, List&lt;int[]&gt;) | Инициализирует новый экземпляр класса StepTriangulatedSurfaceSet. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Получает площадь сущности. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/coordinates/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Получает длину сущности. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnmax/) { get; set; } |  |
| [Triangles](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/triangles/) { get; set; } |  |
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

