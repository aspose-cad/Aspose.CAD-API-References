---
title: "GifOptions.DoPaletteCorrection"
linktitle: "DoPaletteCorrection"
articleTitle: "DoPaletteCorrection"
second_title: "Aspose.CAD for .NET API 参考"
description: "GifOptions 属性。获取或设置一个值，指示是否应用调色板校正。"
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions/gifoptions/dopalettecorrection/"
product_version: "26.9"
---
## GifOptions.DoPaletteCorrection property

获取或设置一个值，指示是否应用调色板校正。

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` 表示已应用调色板校正；否则为 `false`。

## 备注

调色板校正意味着每当图像导出为 GIF 时，源图像的颜色将被分析
以构建最匹配的调色板（如果图像调色板不存在或在选项中未指定）。
分析过程需要一些时间，但输出图像将拥有最佳匹配的颜色调色板，效果在视觉上更佳。

### 另请参阅

* class [GifOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

