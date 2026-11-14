---
title: "CF2Image 类"
linktitle: "CF2Image"
articleTitle: "CF2Image"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.CF2.CF2Image 类。CF2 图像类"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.cf2/cf2image/"
keywords: "CF2Image, Aspose.CAD.FileFormats.CF2, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CF2Image class

CF2 图像类

```csharp
public sealed class CF2Image : Image
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [AuxSecton](../../aspose.cad.fileformats.cf2/cf2image/auxsecton/) { get; } | 获取辅助部分。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| virtual [Depth](../../aspose.cad/image/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.cf2/cf2image/height/) { get; } | 获取图像高度。 |
| override [IsCached](../../aspose.cad.fileformats.cf2/cf2image/iscached/) { get; } | 获取图像是否已缓存 |
| [LineTypeColors](../../aspose.cad.fileformats.cf2/cf2image/linetypecolors/) { get; } | 线型的颜色。 |
| [LinesOutputDescribing](../../aspose.cad.fileformats.cf2/cf2image/linesoutputdescribing/) { get; set; } | 线型输出的描述 |
| [MainSecton](../../aspose.cad.fileformats.cf2/cf2image/mainsecton/) { get; } | 获取主部分。 |
| [MaxPoint](../../aspose.cad.fileformats.cf2/cf2image/maxpoint/) { get; } | 获取最大点。 |
| [MinPoint](../../aspose.cad.fileformats.cf2/cf2image/minpoint/) { get; } | 获取最小点。 |
| [OrderOutputDescribing](../../aspose.cad.fileformats.cf2/cf2image/orderoutputdescribing/) { get; set; } | 订单部分输出的描述 |
| [OrderSecton](../../aspose.cad.fileformats.cf2/cf2image/ordersecton/) { get; } | 获取顺序部分。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| [SubSectons](../../aspose.cad.fileformats.cf2/cf2image/subsectons/) { get; } | 获取子部分。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.cf2/cf2image/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.cf2/cf2image/cachedata/)() | 缓存数据 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetStrings](../../aspose.cad.fileformats.cf2/cf2image/getstrings/)() | 获取图像中的所有字符串值。 |
| [LoadMessageFile](../../aspose.cad.fileformats.cf2/cf2image/loadmessagefile/#loadmessagefile)(Stream) | 从指定的流加载消息文件。 |
| [LoadMessageFile](../../aspose.cad.fileformats.cf2/cf2image/loadmessagefile/#loadmessagefile_1)(string) | 从指定的路径加载消息文件。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [UpdateSize](../../aspose.cad.fileformats.cf2/cf2image/updatesize/)() | 更新大小 |

### 另请参阅

* [Image](../image/)
* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.CF2](../../aspose.cad.fileformats.cf2/)
* assembly [Aspose.CAD](../../)

