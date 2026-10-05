---
title: "IWatermarkGuardService.ImageToEmbed"
linktitle: "ImageToEmbed"
articleTitle: "ImageToEmbed"
second_title: "Aspose.CAD for .NET API Reference"
description: "IWatermarkGuardService property. Embeds the image."
type: docs
weight: 40
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetoembed/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToEmbed property

Embeds the image.

```csharp
public Stream ImageToEmbed { get; set; }
```

### Return Value

The success of operation.

## Examples

Image embedding and validation.

```csharp
string inputFileName = "Tyrannosaurus.dxf";
string watermarkFileName = "Clock-Icon.png";
string embeddedFileName = "Tyrannosaurus_embedded.dxf";

var watermarkStream = new MemoryStream(File.ReadAllBytes(watermarkFileName));

var inputImage = Image.Load(inputFileName);
bool embedSuccess = inputImage.WatermarkGuardService.EmbedImage(watermarkStream);
inputImage.Save(embeddedFileName, new DxfOptions());

var embeddedImage = Image.Load(embeddedFileName);
bool validateSuccess = embeddedImage.WatermarkGuardService.ValidateImage(watermarkStream);
```

### See Also

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

