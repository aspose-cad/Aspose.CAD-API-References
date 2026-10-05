---
title: "PathFigure.IsClosed"
linktitle: "IsClosed"
articleTitle: "IsClosed"
second_title: "Aspose.CAD for .NET API Reference"
description: "PathFigure property. Gets or sets a value indicating whether is closed. Specifies whether the path is closed. If set to true, the stroke is drawn \"closed\", t..."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/pathfigure/isclosed/"
product_version: "26.9"
---
## PathFigure.IsClosed property

Gets or sets a value indicating whether is closed.
 Specifies whether the path is closed.
 If set to true, the stroke is drawn "closed", that is,
 the last point in the last segment of the path figure is connected with
 the point specified in the StartPoint attribute,
 otherwise the stroke is drawn "open", and the last point is not connected to the start point.
 Only applicable if the path figure is used in a Path element that specifies a stroke.

```csharp
public bool IsClosed { get; set; }
```

### See Also

* class [PathFigure](../)
* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../../)

