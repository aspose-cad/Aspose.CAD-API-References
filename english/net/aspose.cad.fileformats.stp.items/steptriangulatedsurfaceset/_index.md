---
title: "StepTriangulatedSurfaceSet Class"
linktitle: "StepTriangulatedSurfaceSet"
articleTitle: "StepTriangulatedSurfaceSet"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Stp.Items.StepTriangulatedSurfaceSet class. TriangulatedSurfaceSet class for STP file. Class represents simple tessellated surface set..."
type: docs
weight: 1070
url: "/net/aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/"
keywords: "StepTriangulatedSurfaceSet, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepTriangulatedSurfaceSet class

TriangulatedSurfaceSet class for STP file.
 Class represents simple tessellated surface set.
 A tessellated geometry can be defined either by a TRIANGULATED_FACE or by 
 a COMPLEX_TRIANGULATED_FACE. These entities are similar to the entities 
 TRIANGULATED_SURFACE_SET and COMPLEX_TRIANGULATED_SURFACE_SET.
 The only difference between a tessellated face and a tessellated surface set 
 is that the tesselated face has an additional attribute GeometricLink. 
 This optional attribute can be used for preserving the exact definition of 
 the underlying exact geometry.

```csharp
public class StepTriangulatedSurfaceSet : StepTessellatedItem
```

## Constructors

| Name | Description |
| --- | --- |
| [StepTriangulatedSurfaceSet](steptriangulatedsurfaceset/)(string, StepCoordinatesList, int, List&lt;double[]&gt;, List&lt;int&gt;, List&lt;int[]&gt;) | Initializes a new instance of the StepTriangulatedSurfaceSet class. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Gets the area of the entity. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/coordinates/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Gets the length of the entity. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnmax/) { get; set; } |  |
| [Triangles](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/triangles/) { get; set; } |  |
| [UId](../../aspose.cad.fileformats.stp.items/steprepresentationitem/uid/) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.cad.fileformats.stp.items/steprepresentationitem/equals/)(StepRepresentationItem) |  |
| override [GetHashCode](../../aspose.cad.fileformats.stp.items/steprepresentationitem/gethashcode/)() |  |

### See Also

* class [StepTessellatedItem](../steptessellateditem/)
* namespace [Aspose.CAD.FileFormats.Stp.Items](../../aspose.cad.fileformats.stp.items/)
* assembly [Aspose.CAD](../../)

