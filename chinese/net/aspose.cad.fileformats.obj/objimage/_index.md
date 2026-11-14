---
title: "ObjImage 类"
linktitle: "ObjImage"
articleTitle: "ObjImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Obj.ObjImage 类。表示 OBJ 格式的图像。包含有关绘图边界、材质、顶点和形状的信息。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.obj/objimage/"
keywords: "ObjImage, Aspose.CAD.FileFormats.Obj, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ObjImage class

表示 OBJ 格式的图像。
包含有关绘图边界、材质、顶点和形状的信息。
每个形状包含关于一组面及其对应的材质、顶点、纹理和法线索引的信息。

```csharp
public class ObjImage : Image
```

## 示例

加载 OBJ 格式的绘图。

```csharp
using (ObjImage objImage = (ObjImage)Image.Load(fileName))
{
...
}
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ObjImage](objimage/)(ObjRoot) | 初始化 `ObjImage` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| override [Depth](../../aspose.cad.fileformats.obj/objimage/depth/) { get; } | 获取图像的深度。计算方式为所有顶点的 Z 坐标的最大值与最小值之差。允许的最小深度为 0。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.obj/objimage/height/) { get; } | 获取图像的高度。计算方式为所有顶点的 Y 坐标的最大值与最小值之差。允许的最小高度为 1。 |
| override [IsCached](../../aspose.cad.fileformats.obj/objimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [ObjRoot](../../aspose.cad.fileformats.obj/objimage/objroot/) { get; set; } | 获取或设置绘图的根信息。ObjRoot 包含关于顶点、材质和形状的数据。可用于公开面信息。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.obj/objimage/width/) { get; } | 获取图像的宽度。计算方式为所有顶点的 X 坐标的最大值与最小值之差。允许的最小宽度为 1。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.obj/objimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/) 加载额外数据。未实现。 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| [GetShapes](../../aspose.cad.fileformats.obj/objimage/getshapes/)() | 获取 OBJ 图像可绘制形状的数据。每个形状包含其名称、材质和面的信息。ObjFace 包含对应顶点、纹理和法线索引的数据。 |
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
* namespace [Aspose.CAD.FileFormats.Obj](../../aspose.cad.fileformats.obj/)
* assembly [Aspose.CAD](../../)

