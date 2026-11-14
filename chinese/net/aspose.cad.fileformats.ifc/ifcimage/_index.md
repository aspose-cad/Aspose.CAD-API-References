---
title: "IfcImage 类"
linktitle: "IfcImage"
articleTitle: "IfcImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Ifc.IfcImage 类。表示 IFC 格式的图像。包含所有实体和头部信息。"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.ifc/ifcimage/"
keywords: "IfcImage, Aspose.CAD.FileFormats.Ifc, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## IfcImage class

表示 IFC 格式的图像。
包含所有实体和头部信息。

```csharp
public class IfcImage : Image, IDrawingLayout<IIfcEntity>, IHasEntities<IIfcEntity>, 
    IHasLayouts<IDrawingLayout<IIfcEntity>, IIfcEntity>
```

## 示例

加载 IFC 格式的图纸。

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
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
| override [Depth](../../aspose.cad.fileformats.ifc/ifcimage/depth/) { get; } | 获取深度。它是根据所有实体计算的 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Entities](../../aspose.cad.fileformats.ifc/ifcimage/entities/) { get; } | 获取图纸上存在的所有实体。可用于遍历它们并检查其属性 |
| [Header](../../aspose.cad.fileformats.ifc/ifcimage/header/) { get; } | 获取头部信息。 |
| override [Height](../../aspose.cad.fileformats.ifc/ifcimage/height/) { get; } | 获取图像高度。它是根据所有实体计算的 |
| override [IsCached](../../aspose.cad.fileformats.ifc/ifcimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。目前始终返回 true |
| [Layers](../../aspose.cad.fileformats.ifc/ifcimage/layers/) { get; } | 获取图像中存在的所有图层列表 |
| [LayoutName](../../aspose.cad.fileformats.ifc/ifcimage/layoutname/) { get; } |  |
| [Layouts](../../aspose.cad.fileformats.ifc/ifcimage/layouts/) { get; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.ifc/ifcimage/width/) { get; } | 获取图像宽度。它是根据所有实体计算的 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.cad.fileformats.ifc/ifcimage/add/)(IIfcEntity) |  |
| override [CacheData](../../aspose.cad.fileformats.ifc/ifcimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/) 加载额外数据。目前尚未在 IFC 文件格式中实现 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetStrings](../../aspose.cad.fileformats.ifc/ifcimage/getstrings/)() | 获取图像中的所有字符串值。可用于获取图像中的文本 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [TryRemoveEntity](../../aspose.cad.fileformats.ifc/ifcimage/tryremoveentity/)(IIfcEntity) |  |

### 另请参阅

* class [Image](../../aspose.cad/image/)
* interface [IDrawingLayout&lt;T&gt;](../../aspose.cad/idrawinglayout-1/)
* interface [IIfcEntity](../iifcentity/)
* interface [IHasEntities&lt;T&gt;](../../aspose.cad/ihasentities-1/)
* interface [IHasLayouts&lt;TLayout, TEntity&gt;](../../aspose.cad/ihaslayouts-2/)
* namespace [Aspose.CAD.FileFormats.Ifc](../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../)

