---
title: "IWatermarkGuardService.ImageToEmbed"
linktitle: "ImageToEmbed"
articleTitle: "ImageToEmbed"
second_title: "Aspose.CAD for .NET API 参考"
description: "IWatermarkGuardService 属性。嵌入图像。"
type: docs
weight: 40
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetoembed/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToEmbed property

嵌入图像。

```csharp
public Stream ImageToEmbed { get; set; }
```

### 返回值

操作成功。

## 示例

图像嵌入和验证。

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

### 另请参阅

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

