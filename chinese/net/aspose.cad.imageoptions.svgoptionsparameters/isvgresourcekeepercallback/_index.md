---
title: "ISvgResourceKeeperCallback 接口"
linktitle: "ISvgResourceKeeperCallback"
articleTitle: "ISvgResourceKeeperCallback"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.SvgOptionsParameters.ISvgResourceKeeperCallback 接口。SVG 回调接口"
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/"
product_version: "26.9"
---
## ISvgResourceKeeperCallback interface

svg 回调接口

```csharp
public interface ISvgResourceKeeperCallback
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [OnFontResourceReady](../../aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/onfontresourceready/)(FontStoringArgs) | 针对 SVG 中使用的每种字体调用。使用它来指定字体的存储方式。 |
| [OnImageResourceReady](../../aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/onimageresourceready/)(byte[], SvgImageType, string, ref bool) | 针对 SVG 中的每个光栅图像调用。使用它来指定光栅图像的存储方式。 |
| [OnSvgDocumentReady](../../aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/onsvgdocumentready/)(byte[], string) | 当 SVG 文档准备好时调用。 |

### 另请参阅

* namespace [Aspose.CAD.ImageOptions.SvgOptionsParameters](../../aspose.cad.imageoptions.svgoptionsparameters/)
* assembly [Aspose.CAD](../../)

