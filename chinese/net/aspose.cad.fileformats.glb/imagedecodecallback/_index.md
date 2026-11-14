---
title: "ImageDecodeCallback 委托"
linktitle: "ImageDecodeCallback"
articleTitle: "ImageDecodeCallback"
second_title: "Aspose.CAD for .NET API 参考"
description: "用于拦截纹理加载的回调，以便客户端引擎对其进行解码并在必要时上传到 GPU。"
type: docs
weight: 280
url: "/net/aspose.cad.fileformats.glb/imagedecodecallback/"
product_version: "26.9"
---
## ImageDecodeCallback delegate

回调用于拦截纹理的加载，以便它们可以
由客户端引擎解码并在必要时上传到 GPU。

```csharp
public delegate bool ImageDecodeCallback(ImageGlb image);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | ImageGlb | 包含纹理的 Image |

### 返回值

如果我们想保留图像内存数据在 [`ImageGlb`](../../../aspose.cad.fileformats.glb/imageglb/) 中，则为 True。

否则内存将被清除，[`ImageGlb`](../../../aspose.cad.fileformats.glb/imageglb/) 将为空。

### 另请参阅

* class [ImageGlb](../imageglb/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

