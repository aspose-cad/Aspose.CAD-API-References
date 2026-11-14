---
title: "Image 类"
linktitle: "Image"
articleTitle: "Image"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Image 类。该图像是所有类型绘图的基类。"
type: docs
weight: 510
url: "/net/aspose.cad/image/"
keywords: "Image, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Image class

Image 是所有绘图类型的基类。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 `Image` 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| abstract [Height](../../aspose.cad/image/height/) { get; } | 获取图像高度。 |
| abstract [IsCached](../../aspose.cad/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| abstract [Width](../../aspose.cad/image/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.cad/datastreamsupporter/cachedata/)() | 缓存数据，并确保不会从底层 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) 再次加载额外数据。 |
| static [CanLoad](../../aspose.cad/image/canload/#canload)(Stream) | 确定是否可以从指定的流加载图像。 |
| static [CanLoad](../../aspose.cad/image/canload/#canload_1)(string) | 确定是否可以从指定的文件路径加载图像。 |
| static [CanLoad](../../aspose.cad/image/canload/#canload_2)(Stream, LoadOptions) | 确定是否可以从指定的流加载图像，并可选地使用指定的 *loadOptions*。 |
| static [CanLoad](../../aspose.cad/image/canload/#canload_3)(string, LoadOptions) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| static [GetFileFormat](../../aspose.cad/image/getfileformat/#getfileformat)(Stream) | 获取文件格式。 |
| static [GetFileFormat](../../aspose.cad/image/getfileformat/#getfileformat_1)(string) | 获取文件格式。 |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | 获取图像中的所有字符串值。 |
| static [Load](../../aspose.cad/image/load/#load)(Stream) | 从指定的流加载新图像。 |
| static [Load](../../aspose.cad/image/load/#load_1)(string) | 从指定的文件加载新图像。 |
| static [Load](../../aspose.cad/image/load/#load_2)(Stream, LoadOptions) | 从指定的流加载新图像。 |
| static [Load](../../aspose.cad/image/load/#load_3)(string, LoadOptions) | 从指定的文件加载新图像。 |
| static [Load](../../aspose.cad/image/load/#load_4)(Stream, string, LoadOptions) | 从指定的流加载新图像。 |
| override [Save](../../aspose.cad/image/save/#save)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/#save_1)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/#save_2)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/#saveasync)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/#saveasync_1)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |

### 另请参阅

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

