---
title: "ObjImage.ObjRoot"
linktitle: "ObjRoot"
articleTitle: "ObjRoot"
second_title: "Aspose.CAD for .NET API Reference"
description: "ObjImage property. Gets or sets root information about the drawing. ObjRoot contains data about vertices, materials, and shapes. Could be useful for the expo..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.obj/objimage/objroot/"
product_version: "26.9"
---
## ObjImage.ObjRoot property

Gets or sets root information about the drawing.
 ObjRoot contains data about vertices, materials, and shapes.
 Could be useful for the exposing information about faces.

```csharp
public ObjRoot ObjRoot { get; set; }
```

## Examples

Prints the overall quantity of vertices in the OBJ drawing.

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    ObjRoot rootInformation = objImage.ObjRoot;
    System.Console.WriteLine("The drawing has {0} vertices", rootInformation.Vertices.Count);
}
```

### See Also

* class [ObjRoot](../../../aspose.cad.fileformats.obj.elements/objroot/)
* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

