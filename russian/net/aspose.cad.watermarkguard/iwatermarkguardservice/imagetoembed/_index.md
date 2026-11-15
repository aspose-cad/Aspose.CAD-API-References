---
title: "IWatermarkGuardService.ImageToEmbed"
linktitle: "ImageToEmbed"
articleTitle: "ImageToEmbed"
second_title: "Aspose.CAD для .NET справка API"
description: "IWatermarkGuardService property. Встраивает изображение."
type: docs
weight: 40
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetoembed/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToEmbed property

Встраивает изображение.

```csharp
public Stream ImageToEmbed { get; set; }
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

