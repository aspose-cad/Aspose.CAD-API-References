---
title: "StpImage.Append"
linktitle: "Append"
articleTitle: "Append"
second_title: "Aspose.CAD for .NET API Reference"
description: "StpImage method. Appends the content of another STP image. This feature allows you to merge the content of a different STP images. In the example below, mode..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.stp/stpimage/append/"
product_version: "26.9"
---
## StpImage.Append method

Appends the content of another STP image.
 This feature allows you to merge the content of a different STP images. In the example
 below, models are loaded from files and then merged into a single image.The resulting 
 STP image will contain all the primitives from each of the loaded STP files.

```csharp
public void Append(StpImage imageToAppend)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageToAppend | StpImage | The image to append. |

## Examples

Loading STP images, merging them into a unified resulting image, and saving the final 
 output to a file.

```csharp
string[] files = new string[] { "inFile1.stp", "inFile2.stp", "inFile3.stp" };
string outFile = "outFile.stp";
StpImage mergedImage = new StpImage();
foreach (var file in files)
    using (StpImage image = (StpImage) Image.Load(file))
        mergedImage.Append(image);
mergedImage.Save(outFile, new StpOptions());
```

### See Also

* class [StpImage](../)
* namespace [Aspose.CAD.FileFormats.Stp](../../../aspose.cad.fileformats.stp/)
* assembly [Aspose.CAD](../../../)

