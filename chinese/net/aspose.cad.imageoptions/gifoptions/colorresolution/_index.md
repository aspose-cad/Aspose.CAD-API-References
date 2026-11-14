---
title: "GifOptions.ColorResolution"
linktitle: "ColorResolution"
articleTitle: "ColorResolution"
second_title: "Aspose.CAD for .NET API 参考"
description: "GifOptions 属性。获取或设置 GIF 颜色分辨率。"
type: docs
weight: 60
url: "/net/aspose.cad.imageoptions/gifoptions/colorresolution/"
product_version: "26.9"
---
## GifOptions.ColorResolution property

获取或设置 GIF 颜色分辨率。

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

颜色分辨率。

## 备注

颜色分辨率 - 每种原色可用的位数
相对于原始图像，减 1。此值表示大小
整个调色板，其中图形的颜色来源于
已选择的，而不是图形实际使用的颜色数量。
例如，如果此字段的值为 3，则调色板的
原始图像每种原色可用 4 位来创建
图像。此值应设置为指示丰富度
原始调色板，即使并非整个调色板的每种颜色
在源机器上可用。

### 另请参阅

* class [GifOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

