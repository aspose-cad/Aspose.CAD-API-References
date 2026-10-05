---
title: "Glyphs.CaretStops"
linktitle: "CaretStops"
articleTitle: "CaretStops"
second_title: "Aspose.CAD for .NET API Reference"
description: "Glyphs property. Gets or sets the caret stops. Identifies the positions within the sequence of Unicode characters at which a text-selection tool can place a ..."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/caretstops/"
product_version: "26.9"
---
## Glyphs.CaretStops property

Gets or sets the caret stops.
 Identifies the positions within the sequence of Unicode characters at which a text-selection tool can place a text-editing caret.
 Potential caret-stop positions are identified by their indices into the UTF-16 code units represented by the UnicodeString attribute value.
 When this attribute is missing, the text in the UnicodeString attribute value MUST be interpreted
 as having a caret stop between every Unicode UTF-16 code unit and at the beginning and end of the text.
 The value SHOULD indicate that the caret cannot stop in front of most combining marks or in front of the second UTF-16 code unit of UTF-16 surrogate pairs.

```csharp
public string CaretStops { get; set; }
```

### See Also

* class [Glyphs](../)
* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../../)

