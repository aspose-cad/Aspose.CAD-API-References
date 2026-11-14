---
title: "DracoImage 类"
linktitle: "DracoImage"
articleTitle: "DracoImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Draco.DracoImage 类。表示 DRACO 格式的图像。包含有关绘图边界、顶点、面和属性的信息。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.draco/dracoimage/"
keywords: "DracoImage, Aspose.CAD.FileFormats.Draco, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DracoImage class

表示 DRACO 格式的图像。
包含有关绘图边界、顶点、面和属性的信息。

```csharp
public class DracoImage : Image
```

## 示例

加载 DRACO 格式的绘图。

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
...
}
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| override [Depth](../../aspose.cad.fileformats.draco/dracoimage/depth/) { get; } | 获取图像的深度。计算方式为所有顶点的 Z 坐标的最大值与最小值之差。允许的最小深度为 0。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.draco/dracoimage/height/) { get; } | 获取图像的高度。计算方式为所有顶点的 Y 坐标的最大值与最小值之差。允许的最小高度为 1。 |
| [Indices](../../aspose.cad.fileformats.draco/dracoimage/indices/) { get; set; } | 网格面索引数组。 |
| override [IsCached](../../aspose.cad.fileformats.draco/dracoimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.draco/dracoimage/width/) { get; } | 获取图像的宽度。计算方式为所有顶点的 X 坐标的最大值与最小值之差。允许的最小宽度为 1。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.draco/dracoimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/) 加载额外数据。未实现。 |
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
* namespace [Aspose.CAD.FileFormats.Draco](../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../)

