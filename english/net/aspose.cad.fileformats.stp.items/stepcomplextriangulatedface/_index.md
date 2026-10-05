---
title: "StepComplexTriangulatedFace Class"
linktitle: "StepComplexTriangulatedFace"
articleTitle: "StepComplexTriangulatedFace"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Stp.Items.StepComplexTriangulatedFace class. ComplexTriangulatedFace class for STP file. Class represents complex tessellated face. A ..."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/"
keywords: "StepComplexTriangulatedFace, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepComplexTriangulatedFace class

ComplexTriangulatedFace class for STP file.
 Class represents complex tessellated face.
 A tessellated geometry can be defined either by a TRIANGULATED_FACE or by 
 a COMPLEX_TRIANGULATED_FACE. These entities are similar to the entities 
 TRIANGULATED_SURFACE_SET and COMPLEX_TRIANGULATED_SURFACE_SET.
 The only difference between a tessellated face and a tessellated surface set 
 is that the tesselated face has an additional attribute GeometricLink. 
 This optional attribute can be used for preserving the exact definition of 
 the underlying exact geometry.

```csharp
public class StepComplexTriangulatedFace : StepTessellatedFace
```

## Constructors

| Name | Description |
| --- | --- |
| [StepComplexTriangulatedFace](stepcomplextriangulatedface/#constructor)() | The default constructor. |
| [StepComplexTriangulatedFace](stepcomplextriangulatedface/#constructor_1)(string, StepCoordinatesList, int, List&lt;double[]&gt;, StepRepresentationItem, List&lt;int&gt;, List&lt;int[]&gt;, List&lt;int[]&gt;) | Initializes a new instance of the StepComplexTriangulatedFace class. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | Gets the area of the entity. |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/coordinates/) { get; set; } |  |
| [GeometricLink](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/geometriclink/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | Gets the length of the entity. |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/pnmax/) { get; set; } |  |
| [TriangleFans](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/trianglefans/) { get; set; } |  |
| [TriangleStrips](../../aspose.cad.fileformats.stp.items/stepcomplextriangulatedface/trianglestrips/) { get; set; } |  |
| [UId](../../aspose.cad.fileformats.stp.items/steprepresentationitem/uid/) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.cad.fileformats.stp.items/steprepresentationitem/equals/)(StepRepresentationItem) |  |
| override [GetHashCode](../../aspose.cad.fileformats.stp.items/steprepresentationitem/gethashcode/)() |  |

### See Also

* class [StepTessellatedFace](../steptessellatedface/)
* namespace [Aspose.CAD.FileFormats.Stp.Items](../../aspose.cad.fileformats.stp.items/)
* assembly [Aspose.CAD](../../)

