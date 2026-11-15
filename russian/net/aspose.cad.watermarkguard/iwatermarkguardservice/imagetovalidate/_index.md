---
title: "IWatermarkGuardService.ImageToValidate"
linktitle: "ImageToValidate"
articleTitle: "ImageToValidate"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство IWatermarkGuardService. Проверяет изображение."
type: docs
weight: 60
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToValidate property

Проверяет изображение.

```csharp
public Stream ImageToValidate { get; set; }
```

### Возвращаемое значение

Успех операции.

## Примеры

Встраивание и проверка изображения.

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

### См. также

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

