---
title: "StepComplexTriangulatedSurfaceSet Class"
linktitle: "StepComplexTriangulatedSurfaceSet"
articleTitle: "StepComplexTriangulatedSurfaceSet"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Stp.Items.StepComplexTriangulatedSurfaceSet class. ComplexTriangulatedSurfaceSet class for STP file. Class represents complex tessella..."
type: docs
weight: 230
url: "/net/aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/"
keywords: "StepComplexTriangulatedSurfaceSet, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepComplexTriangulatedSurfaceSet class

ComplexTriangulatedSurfaceSet class for STP file.
 Class represents complex tessellated surface set.
 A tessellated geometry can be defined either by a TRIANGULATED_FACE or by 
 a COMPLEX_TRIANGULATED_FACE. These entities are similar to the entities 
 TRIANGULATED_SURFACE_SET and COMPLEX_TRIANGULATED_SURFACE_SET.
 The only difference between a tessellated face and a tessellated surface set 
 is that the tesselated face has an additional attribute GeometricLink. 
 This optional attribute can be used for preserving the exact definition of 
 the underlying exact geometry.

```csharp
public class StepComplexTriangulatedSurfaceSet : StepTessellatedItem
```

## Constructors

| Name | Description |
| --- | --- |
| [StepComplexTriangulatedSurfaceSet](stepcomplextriangulatedsurfaceset/)(string, StepCoordinatesList, int, List&lt;double[]&gt;, List&lt;int&gt;, List&lt;int[]&gt;, List&lt;int[]&gt;) | Initializes a new instance of the StepComplexTriangulatedSurfaceSet class. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Gets the area of the entity. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/coordinates/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Gets the length of the entity. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/pnmax/) { get; set; } |  |
| [TriangleFans](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/trianglefans/) { get; set; } |  |
| [TriangleStrips](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedsurfaceset/trianglestrips/) { get; set; } |  |
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

