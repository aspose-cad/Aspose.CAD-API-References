---
title: "IWatermarkGuardService.ImageToValidate"
linktitle: "ImageToValidate"
articleTitle: "ImageToValidate"
second_title: "Aspose.CAD for .NET API Reference"
description: "IWatermarkGuardService property. Validates the image."
type: docs
weight: 60
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToValidate property

Validates the image.

```csharp
public Stream ImageToValidate { get; set; }
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

