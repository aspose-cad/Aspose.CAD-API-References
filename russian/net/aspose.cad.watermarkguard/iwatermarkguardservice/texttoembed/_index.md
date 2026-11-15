---
title: "IWatermarkGuardService.TextToEmbed"
linktitle: "TextToEmbed"
articleTitle: "TextToEmbed"
second_title: "Aspose.CAD для .NET справка API"
description: "IWatermarkGuardService property. Встраивает текст."
type: docs
weight: 30
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/texttoembed/"
product_version: "26.9"
---
## IWatermarkGuardService.TextToEmbed property

Встраивает текст.

```csharp
public string TextToEmbed { get; set; }
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

