---
title: "IWatermarkGuardService.TextToValidate"
linktitle: "TextToValidate"
articleTitle: "TextToValidate"
second_title: "Aspose.CAD for .NET API Reference"
description: "IWatermarkGuardService property. Validates the text."
type: docs
weight: 50
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/texttovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.TextToValidate property

Validates the text.

```csharp
public string TextToValidate { get; set; }
```

### Return Value

The success of operation.

## Examples

Text embedding and validation.

```csharp
string inputFileName = "Tyrannosaurus.dxf";
string embeddedFileName = "Tyrannosaurus_embedded.dxf";

string watermarkText = "草长莺飞";

var inputImage = Image.Load(inputFileName);
bool embedSuccess = inputImage.WatermarkGuardService.EmbedText(watermarkText);
inputImage.Save(embeddedFileName, new DxfOptions());

var embeddedImage = Image.Load(embeddedFileName);
bool validateSuccess = embeddedImage.WatermarkGuardService.ValidateText(watermarkText);
```

### See Also

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

