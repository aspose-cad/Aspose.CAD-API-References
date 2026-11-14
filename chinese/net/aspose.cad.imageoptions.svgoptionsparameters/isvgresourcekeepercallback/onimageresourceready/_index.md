---
title: "ISvgResourceKeeperCallback.OnImageResourceReady"
linktitle: "OnImageResourceReady"
articleTitle: "OnImageResourceReady"
second_title: "Aspose.CAD for .NET API 参考"
description: "ISvgResourceKeeperCallback 方法。针对 SVG 中的每个光栅图像调用。使用它来指定如何存储光栅图像。"
type: docs
weight: 10
url: "/net/aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/onimageresourceready/"
product_version: "26.9"
---
## ISvgResourceKeeperCallback.OnImageResourceReady method

针对 SVG 中的每个光栅图像调用。使用它来指定光栅图像的存储方式。

```csharp
public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | Byte[] | 光栅图像内容的字节。 |
| imageType | SvgImageType | 图像的类型。 |
| suggestedFileName | String | 建议文件的名称。 |
| useEmbeddedImage | Boolean& | 如果设置为 `true`，则图像将嵌入到 SVG 中。 |

### 返回值

应返回已保存资源的路径。该路径将在 SVG 图像中用于引用光栅内容。路径应相对于目标 SVG 文档。

### 另请参阅

* enum [SvgImageType](../../svgimagetype/)
* interface [ISvgResourceKeeperCallback](../)
* namespace [Aspose.CAD.ImageOptions.SvgOptionsParameters](../../../aspose.cad.imageoptions.svgoptionsparameters/)
* assembly [Aspose.CAD](../../../)

