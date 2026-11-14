---
title: "Image.Palette"
linktitle: "调色板"
articleTitle: "调色板"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 属性。获取或设置颜色调色板。"
type: docs
weight: 230
url: "/net/aspose.cad/image/palette/"
product_version: "26.9"
---
## Image.Palette property

获取或设置颜色调色板。

```csharp
public IColorPalette Palette { get; set; }
```

### Property Value

颜色调色板。

## 示例

断言 DGN 绘图包含调色板。

```csharp
var fileName = @"C:\path\drawing.dgn";
using (DgnImage drawing = (DgnImage)Image.Load(fileName))
{
    AssertLegacy.IsNotEmpty(drawing.Palette);
}
```

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

