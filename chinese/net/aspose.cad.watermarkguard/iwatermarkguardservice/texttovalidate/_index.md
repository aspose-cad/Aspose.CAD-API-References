---
title: "IWatermarkGuardService.TextToValidate"
linktitle: "TextToValidate"
articleTitle: "TextToValidate"
second_title: "Aspose.CAD for .NET API 参考"
description: "IWatermarkGuardService 属性。验证文本。"
type: docs
weight: 50
url: "/net/aspose.cad.watermarkguard/iwatermarkguardservice/texttovalidate/"
product_version: "26.9"
---
## IWatermarkGuardService.TextToValidate property

验证文本。

```csharp
public string TextToValidate { get; set; }
```

### 返回值

操作成功。

## 示例

文本嵌入和验证。

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

### 另请参阅

* interface [IWatermarkGuardService](../)
* namespace [Aspose.CAD.WatermarkGuard](../../../aspose.cad.watermarkguard/)
* assembly [Aspose.CAD](../../../)

