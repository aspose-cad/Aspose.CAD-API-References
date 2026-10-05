---
title: "Technique Class"
linktitle: "Technique"
articleTitle: "Technique"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Technique class. The technique. The technique element declares the information used to process some portio..."
type: docs
weight: 1200
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/technique/"
keywords: "Technique, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Technique class

The technique.
 The technique element declares the information used to process some portion of the content.
 Each technique conforms to an associated profile.Techniques generally act as a "switch".
 If more than one is present for a particular portion of content, on import, one or the other is picked, but usually not both.
 Selection should be based on which profile the importing application can support.
 Techniques contain application data and programs, making them assets that can be managed as a unit.

```csharp
public class Technique : ColladaElement
```

## Constructors

| Name | Description |
| --- | --- |
| [Technique](technique/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Profile](../../aspose.cad.fileformats.collada.fileparser.elements/technique/profile/) { get; set; } | Gets or sets the profile. The profile attribute indicates the type of profile. This is a vendor defined character string that indicates the platform or capability target for the technique. Required attribute. |

### See Also

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

