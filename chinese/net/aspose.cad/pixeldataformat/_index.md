---
title: "PixelDataFormat 类"
linktitle: "PixelDataFormat"
articleTitle: "PixelDataFormat"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.PixelDataFormat 类。像素数据格式。"
type: docs
weight: 690
url: "/net/aspose.cad/pixeldataformat/"
keywords: "PixelDataFormat, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PixelDataFormat class

像素数据格式。

```csharp
public class PixelDataFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsPerPixel](../../aspose.cad/pixeldataformat/bitsperpixel/) { get; } | 获取每像素位数。 |
| [ChannelBits](../../aspose.cad/pixeldataformat/channelbits/) { get; } | 获取每个通道的位计数。 |
| [ChannelsCount](../../aspose.cad/pixeldataformat/channelscount/) { get; } | 获取通道数量。 |
| static [Cmyk](../../aspose.cad/pixeldataformat/cmyk/) { get; } | 获取为每像素 32 位且每种青色、品红、黄色和黑色各 8 位定义的 `PixelDataFormat`。 |
| static [Grayscale](../../aspose.cad/pixeldataformat/grayscale/) { get; } | 获取为每像素 8 位且 8 位表示 0-255 区间灰度强度的 `PixelDataFormat`。 |
| static [GrayscaleAlpha](../../aspose.cad/pixeldataformat/grayscalealpha/) { get; } | 获取为每像素 16 位且 8 位表示 0-255 区间灰度强度并附加 8 位 alpha 分量的 `PixelDataFormat`。 |
| [PixelFormat](../../aspose.cad/pixeldataformat/pixelformat/) { get; } | 获取像素格式。 |
| static [Rgb16Bpp555](../../aspose.cad/pixeldataformat/rgb16bpp555/) { get; } | 获取为每像素 16 位且红、绿、蓝各 5 位、未定义 alpha 的 `PixelDataFormat`。 |
| static [Rgb24Bpp](../../aspose.cad/pixeldataformat/rgb24bpp/) { get; } | 获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 `PixelDataFormat`。 |
| static [Rgb24BppPng](../../aspose.cad/pixeldataformat/rgb24bpppng/) { get; } | 获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 `PixelDataFormat`。 |
| static [Rgb32Bpp](../../aspose.cad/pixeldataformat/rgb32bpp/) { get; } | 获取为每像素 32 位且 alpha、红、绿、蓝各 8 位的 `PixelDataFormat`。 |
| static [RgbIndexed1Bpp](../../aspose.cad/pixeldataformat/rgbindexed1bpp/) { get; } | 获取为每种颜色 1 位索引的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed2Bpp](../../aspose.cad/pixeldataformat/rgbindexed2bpp/) { get; } | 获取为每种颜色 2 位索引的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed4Bpp](../../aspose.cad/pixeldataformat/rgbindexed4bpp/) { get; } | 获取为每种颜色 4 位索引的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed8Bpp](../../aspose.cad/pixeldataformat/rgbindexed8bpp/) { get; } | 获取为每种颜色 8 位索引的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板或将 RGBA 转换为索引颜色模型。 |
| static [Rgba32Bpp](../../aspose.cad/pixeldataformat/rgba32bpp/) { get; } | 获取为每像素 32 位且 alpha、红、绿、蓝各 8 位的 `PixelDataFormat`。 |
| static [YCbCr](../../aspose.cad/pixeldataformat/ycbcr/) { get; } | 获取为每像素 24 位且亮度、蓝差、红差色度分量各 8 位的 `PixelDataFormat`。 |
| static [Ycck](../../aspose.cad/pixeldataformat/ycck/) { get; } | 获取为每像素 32 位且亮度、蓝差、红差和黑色色度分量各 8 位的 `PixelDataFormat`。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.cad/pixeldataformat/equals/)(object) | 确定指定的对象是否等于此实例。 |
| override [GetHashCode](../../aspose.cad/pixeldataformat/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.cad/pixeldataformat/tostring/)() | 返回表示此实例的字符串。 |
| [operator !=](../../aspose.cad/pixeldataformat/op_inequality/) | 返回两个 `PixelDataFormat` 类的不等结果。 |
| [operator ==](../../aspose.cad/pixeldataformat/op_equality/) | 返回两个 `PixelDataFormat` 类的相等结果。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

