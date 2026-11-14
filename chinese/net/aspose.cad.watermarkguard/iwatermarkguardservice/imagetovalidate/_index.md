---
title: "IWatermarkGuardService.ImageToValidate"
linktitle: "ImageToValidate"
articleTitle: "ImageToValidate"
second_title: "Aspose.CAD for .NET API 参考"
description: "IWatermarkGuardService 属性。验证图像。"
type: docs
weight: 60
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/imagetovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.ImageToValidate property

验证图像。

```csharp
public Stream ImageToValidate { get; set; }
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

