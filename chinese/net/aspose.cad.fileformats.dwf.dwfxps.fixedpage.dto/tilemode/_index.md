---
title: "TileMode 枚举"
linktitle: "TileMode"
articleTitle: "TileMode"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.TileMode 枚举。瓦片模式。指定在填充几何体中如何执行平铺。"
type: docs
weight: 330
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/tilemode/"
product_version: "26.9"
---
## TileMode enumeration

瓦片模式。
指定在填充几何体中如何执行平铺。

```csharp
public enum TileMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 无模式。在此模式下，仅绘制单个基础瓦片。其余区域保持透明。 |
| Tile | `1` | 瓦片模式。在此模式下，绘制基础瓦片，并通过重复基础瓦片来填充其余区域，使每个瓦片的右边缘与下一个瓦片的左边缘相接，底部边缘与下一个瓦片的顶部相接。 |
| FlipX | `2` | 翻转 X 模式。在此模式下，瓦片排列类似于 Tile 瓦片模式，但交替的列会水平翻转。基础瓦片按视口指定的位置放置。该瓦片左右两侧的列中的瓦片会水平翻转。 |
| FlipY | `3` | 翻转 Y 模式。在此模式下，瓦片排列类似于 Tile 瓦片模式，但交替的行会垂直翻转。基础瓦片按视口指定的位置放置。上下行的瓦片会垂直翻转。 |
| FlipXY | `4` | 翻转 XY 模式。在此模式下，瓦片排列类似于 Tile 瓦片模式，但交替的列会水平翻转，交替的行会垂直翻转。基础瓦片按视口指定的位置放置。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

