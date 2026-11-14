---
title: "CgmImage 类"
linktitle: "CgmImage"
articleTitle: "CgmImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cgm.CgmImage 类。表示二进制模式下的 CGM 文件"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cgm/cgmimage/"
keywords: "CgmImage, Aspose.CAD.FileFormats.Cgm, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CgmImage class

表示二进制模式下的 CGM 文件

```csharp
public class CgmImage : Image
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CgmImage](cgmimage/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [Data](../../aspose.cad.fileformats.cgm/cgmimage/data/) { get; } | 提供 CGM 数据结构 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.cgm/cgmimage/height/) { get; } |  |
| override [IsCached](../../aspose.cad.fileformats.cgm/cgmimage/iscached/) { get; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.cgm/cgmimage/width/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.cgm/cgmimage/cachedata/)() |  |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | 获取图像中的所有字符串值。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |

### 另请参阅

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.Cgm](../../aspose.cad.fileformats.cgm/)
* assembly [Aspose.CAD](../../)

