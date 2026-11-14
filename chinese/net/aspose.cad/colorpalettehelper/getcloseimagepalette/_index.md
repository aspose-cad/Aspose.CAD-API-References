---
title: "ColorPaletteHelper.GetCloseImagePalette"
linktitle: "GetCloseImagePalette"
articleTitle: "GetCloseImagePalette"
second_title: "Aspose.CAD for .NET API 参考"
description: "ColorPaletteHelper 方法。获取光栅图像的颜色调色板（对图像进行调色），如果图像没有调色板。若调色板已存在，则会使用它..."
type: docs
weight: 60
url: "/net/aspose.cad/colorpalettehelper/getcloseimagepalette/"
product_version: "26.9"
---
## ColorPaletteHelper.GetCloseImagePalette method

从光栅图像获取颜色调色板（对图像进行调色），如果图像没有调色板。若调色板已存在，则使用现有调色板而不是执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | RasterImage | 光栅图像。 |
| entriesCount | Int32 | 所需的条目计数。 |

### 返回值

颜色调色板从 *image* 中最常见的颜色开始，并包含 *entriesCount* 个条目。

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

