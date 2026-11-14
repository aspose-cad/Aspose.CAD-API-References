---
title: "StepTriangulatedSurfaceSet 类"
linktitle: "StepTriangulatedSurfaceSet"
articleTitle: "StepTriangulatedSurfaceSet"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Stp.Items.StepTriangulatedSurfaceSet 类。TriangulatedSurfaceSet 类用于 STP 文件。类表示简单的镶嵌表面集合..."
type: docs
weight: 1070
url: "/net/aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/"
keywords: "StepTriangulatedSurfaceSet, Aspose.CAD.FileFormats.Stp.Items, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StepTriangulatedSurfaceSet class

TriangulatedSurfaceSet 类用于 STP 文件。
类表示简单的镶嵌表面集合。
镶嵌几何可以通过 TRIANGULATED_FACE 或者
a COMPLEX_TRIANGULATED_FACE。这些实体与这些实体相似
TRIANGULATED_SURFACE_SET 和 COMPLEX_TRIANGULATED_SURFACE_SET。
镶嵌面和镶嵌表面集合之间唯一的区别是
即镶嵌面具有额外的属性 GeometricLink。
此可选属性可用于保留精确定义的
底层精确几何。

```csharp
public class StepTriangulatedSurfaceSet : StepTessellatedItem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StepTriangulatedSurfaceSet](steptriangulatedsurfaceset/)(string, StepCoordinatesList, int, List&lt;double[]&gt;, List&lt;int&gt;, List&lt;int[]&gt;) | 初始化 StepTriangulatedSurfaceSet 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Area](../../aspose.cad.fileformats.stp.items/steprepresentationitem/area/) { get; } | 获取实体的面积。 |
| [Childs](../../aspose.cad.fileformats.stp.items/steprepresentationitem/childs/) { get; } |  |
| [Coordinates](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/coordinates/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.stp.items/steprepresentationitem/id/) { get; } |  |
| override [ItemType](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/itemtype/) { get; } |  |
| [Length](../../aspose.cad.fileformats.stp.items/steprepresentationitem/length/) { get; } | 获取实体的长度。 |
| [Name](../../aspose.cad.fileformats.stp.items/steprepresentationitem/name/) { get; set; } |  |
| [Normals](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/normals/) { get; set; } |  |
| [PNIndex](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnindex/) { get; set; } |  |
| [PNMax](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/pnmax/) { get; set; } |  |
| [Triangles](../../aspose.cad.fileformats.stp.items/steptriangulatedsurfaceset/triangles/) { get; set; } |  |
| [UId](../../aspose.cad.fileformats.stp.items/steprepresentationitem/uid/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Equals](../../aspose.cad.fileformats.stp.items/steprepresentationitem/equals/)(StepRepresentationItem) |  |
| override [GetHashCode](../../aspose.cad.fileformats.stp.items/steprepresentationitem/gethashcode/)() |  |

### 另请参阅

* class [StepTessellatedItem](../steptessellateditem/)
* namespace [Aspose.CAD.FileFormats.Stp.Items](../../aspose.cad.fileformats.stp.items/)
* assembly [Aspose.CAD](../../)

