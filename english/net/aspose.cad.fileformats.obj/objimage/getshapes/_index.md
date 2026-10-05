---
title: "ObjImage.GetShapes"
linktitle: "GetShapes"
articleTitle: "GetShapes"
second_title: "Aspose.CAD for .NET API Reference"
description: "ObjImage method. Gets data about drawable shapes for OBJ image. Each shape contains information about its name, material and faces. ObjFace includes data abo..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.obj/objimage/getshapes/"
product_version: "26.9"
---
## ObjImage.GetShapes method

Gets data about drawable shapes for OBJ image.
 Each shape contains information about its name, material and faces.
 ObjFace includes data about correspoinding vertex, texture, and normal indices.

```csharp
public IEnumerable<ObjShape> GetShapes()
```

## Examples

Prints the quantity of faces in each shape.

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
    foreach (ObjShape shape in objImage.GetShapes())
    {
        System.Console.WriteLine("Shape has {0} faces", shape.Faces.Count);
    }
}
```

### See Also

* class [ObjShape](../../../aspose.cad.fileformats.obj.elements/objshape/)
* class [ObjImage](../)
* namespace [Aspose.CAD.FileFormats.Obj](../../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../../)

