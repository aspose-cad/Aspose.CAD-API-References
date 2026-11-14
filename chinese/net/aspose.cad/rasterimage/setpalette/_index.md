---
title: "RasterImage.SetPalette"
linktitle: "SetPalette"
articleTitle: "SetPalette"
second_title: "Aspose.CAD for .NET API 参考"
description: "RasterImage 方法。设置图像调色板。"
type: docs
weight: 380
url: "/net/aspose.cad/rasterimage/setpalette/"
product_version: "26.9"
---
## RasterImage.SetPalette method

设置图像调色板。

```csharp
public virtual void SetPalette(IColorPalette palette, bool updateColors)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | IColorPalette | 要设置的调色板。 |
| updateColors | Boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。注意，未更改的索引如果在加载时没有对应的调色板条目，可能导致图像崩溃。 |

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

