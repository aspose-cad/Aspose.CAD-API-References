---
title: "GifOptions.PixelAspectRatio"
linktitle: "PixelAspectRatio"
articleTitle: "PixelAspectRatio"
second_title: "Aspose.CAD for .NET API 参考"
description: "GifOptions 属性。获取或设置 GIF 像素宽高比。"
type: docs
weight: 80
url: "/net/aspose.cad.imageoptions/gifoptions/pixelaspectratio/"
product_version: "26.9"
---
## GifOptions.PixelAspectRatio property

获取或设置 GIF 像素宽高比。

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF 像素宽高比。

## 备注

像素纵横比 - 用于计算近似值的因素
原始图像中像素的纵横比。 如果
如果该字段的值不为 0，则此纵横比的近似值
基于以下公式计算：
纵横比 = (像素纵横比 + 15) / 64
像素纵横比被定义为像素的
宽度除以高度。 此字段的取值范围允许
指定最宽像素为 4:1 到最高像素为
1:4，增量为 1/64。
取值：
0 - 未提供纵横比信息。
1..255 - 用于计算的值。

### 另请参阅

* class [GifOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

