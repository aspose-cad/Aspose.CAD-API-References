---
title: "IWatermarkGuardService.TextToValidate"
linktitle: "TextToValidate"
articleTitle: "TextToValidate"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство IWatermarkGuardService. Проверяет текст."
type: docs
weight: 50
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/texttovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.TextToValidate property

Проверяет текст.

```csharp
public string TextToValidate { get; set; }
```

### Возвращаемое значение

Успех операции.

## Примеры

Встраивание и проверка текста.

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

### См. также

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

