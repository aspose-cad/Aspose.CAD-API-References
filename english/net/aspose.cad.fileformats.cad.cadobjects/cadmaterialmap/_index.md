---
title: "CadMaterialMap Class"
linktitle: "CadMaterialMap"
articleTitle: "CadMaterialMap"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadMaterialMap class. Represents a material component map that defines the texture source and controls how it is projec..."
type: docs
weight: 930
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/"
keywords: "CadMaterialMap, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadMaterialMap class

Represents a material component map that defines the texture source and controls how it is projected, tiled, and transformed on an object surface.

```csharp
public class CadMaterialMap
```

## Constructors

| Name | Description |
| --- | --- |
| [CadMaterialMap](cadmaterialmap/)() | Initializes a new instance of the `CadMaterialMap` class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoTransform](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/autotransform/) { get; set; } | Automatic transform mode of the mapper. Multiple values can be combined using a logical OR. |
| [BlendFactor](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/blendfactor/) { get; set; } | Blend factor for the image map, between 0.0 and 1.0. |
| [FileName](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/filename/) { get; set; } | Path to the image file used as the map source. |
| [Projection](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/projection/) { get; set; } | Mapping projection used when the map is applied to a surface. |
| [Source](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/source/) { get; set; } | Data source of the material map. |
| [Tiling](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/tiling/) { get; set; } | Tiling method applied when the map is projected onto a surface. |
| [TransformMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/transformmatrix/) { get; set; } | Transform matrix of the mapper, stored as a flat list of 16 values. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [IdentityMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/identitymatrix/) | Identity transform matrix: no rotation, no scaling, no translation. Used as a fallback when [`TransformMatrix`](./transformmatrix/) does not contain exactly 16 values. |

### See Also

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

