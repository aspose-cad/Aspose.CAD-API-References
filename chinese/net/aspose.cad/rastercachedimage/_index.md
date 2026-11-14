---
title: "RasterCachedImage 类"
linktitle: "RasterCachedImage"
articleTitle: "RasterCachedImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.RasterCachedImage 类。表示支持光栅图形操作的光栅图像。当需要时，此图像会缓存像素数据。"
type: docs
weight: 730
url: "/net/aspose.cad/rastercachedimage/"
keywords: "RasterCachedImage, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## RasterCachedImage class

表示支持光栅图形操作的光栅图像。需要时此图像会缓存像素数据。

```csharp
public abstract class RasterCachedImage : RasterImage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| abstract [BitsPerPixel](../../aspose.cad/rasterimage/bitsperpixel/) { get; } | 获取图像每像素位数。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [HasAlpha](../../aspose.cad/rasterimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha 通道。 |
| virtual [HasTransparentColor](../../aspose.cad/rasterimage/hastransparentcolor/) { get; set; } | 获取一个值，指示图像是否具有透明颜色。 |
| abstract [Height](../../aspose.cad/image/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.cad/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../rasterimage/) 的水平分辨率（每英寸像素数）。 |
| override [IsCached](../../aspose.cad/rastercachedimage/iscached/) { get; } | 获取一个值，指示图像数据当前是否已缓存。 |
| [IsRawDataAvailable](../../aspose.cad/rasterimage/israwdataavailable/) { get; } | 获取一个值，指示是否可以加载原始数据。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [RawCustomColorConverter](../../aspose.cad/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.cad/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.cad/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.cad/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.cad/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.cad/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [TransparentColor](../../aspose.cad/rasterimage/transparentcolor/) { get; set; } | 获取图像的透明颜色。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [VerticalResolution](../../aspose.cad/rasterimage/verticalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| abstract [Width](../../aspose.cad/image/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [AdjustBrightness](../../aspose.cad/rastercachedimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.cad/rastercachedimage/adjustcontrast/)(float) | 图像对比度 |
| override [AdjustGamma](../../aspose.cad/rastercachedimage/adjustgamma/#adjustgamma)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.cad/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | 图像的伽马校正。 |
| override [BinarizeBradley](../../aspose.cad/rastercachedimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| override [BinarizeFixed](../../aspose.cad/rastercachedimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化 |
| override [BinarizeOtsu](../../aspose.cad/rastercachedimage/binarizeotsu/)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.cad/rastercachedimage/cachedata/)() | 缓存数据，并确保不会从底层 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) 再次加载额外数据。 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| override [Crop](../../aspose.cad/rastercachedimage/crop/)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.cad/rasterimage/crop/)(int, int, int, int) | 裁剪图像并进行位移。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.cad/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.cad/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理。 |
| [GetArgb32Pixel](../../aspose.cad/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.cad/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| [GetDefaultPixels](../../aspose.cad/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.cad/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.cad/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认的原始数据数组。 |
| [GetPixel](../../aspose.cad/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | 获取图像中的所有字符串值。 |
| override [Grayscale](../../aspose.cad/rastercachedimage/grayscale/)() | 将图像转换为灰度表示。 |
| [LoadArgb32Pixels](../../aspose.cad/rasterimage/loadargb32pixels/)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadCmykPixels](../../aspose.cad/rasterimage/loadcmykpixels/)(Rectangle) | 加载 CMYK 格式的像素。 |
| [LoadPartialArgb32Pixels](../../aspose.cad/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 按包部分加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.cad/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 按包部分加载像素。 |
| [LoadPixels](../../aspose.cad/rasterimage/loadpixels/)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.cad/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [ReadScanLine](../../aspose.cad/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLineArgb](../../aspose.cad/rasterimage/readscanlineargb/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| override [Resize](../../aspose.cad/rastercachedimage/resize/#resize)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.cad/rastercachedimage/resize/#resize_1)(int, int, ResizeType) | 调整图像大小。 |
| override [Rotate](../../aspose.cad/rastercachedimage/rotate/)(float, bool, Color) | 围绕中心旋转图像。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveArgb32Pixels](../../aspose.cad/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveCmykPixels](../../aspose.cad/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 保存像素。 |
| [SavePixels](../../aspose.cad/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.cad/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.cad/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| virtual [SetPalette](../../aspose.cad/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.cad/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.cad/rasterimage/setresolution/)(double, double) | 为此 [`RasterImage`](../rasterimage/) 设置分辨率。 |
| [WriteScanLine](../../aspose.cad/rasterimage/writescanline/)(int, Color[]) | 将整行扫描写入指定的扫描行索引。 |
| [WriteScanLine](../../aspose.cad/rasterimage/writescanline/)(int, int[]) | 将整行扫描写入指定的扫描行索引。 |

### 另请参阅

* class [RasterImage](../rasterimage/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

