---
title: "FbxImage 类"
linktitle: "FbxImage"
articleTitle: "FbxImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Fbx.FbxImage 类。Fbx 图像类"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.fbx/fbximage/"
keywords: "FbxImage, Aspose.CAD.FileFormats.Fbx, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## FbxImage class

Fbx 图像类

```csharp
public class FbxImage : Image, IHasEntities<DrawingEntity3D>, 
    IHasLayouts<IDrawingLayout<DrawingEntity3D>, DrawingEntity3D>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| override [Depth](../../aspose.cad.fileformats.fbx/fbximage/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Entities](../../aspose.cad.fileformats.fbx/fbximage/entities/) { get; } |  |
| override [Height](../../aspose.cad.fileformats.fbx/fbximage/height/) { get; } | 获取图像高度。 |
| override [IsCached](../../aspose.cad.fileformats.fbx/fbximage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且不需要读取数据。 |
| [Layouts](../../aspose.cad.fileformats.fbx/fbximage/layouts/) { get; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Scene](../../aspose.cad.fileformats.fbx/fbximage/scene/) { get; } |  |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| [Version](../../aspose.cad.fileformats.fbx/fbximage/version/) { get; } | 获取图像高度。 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.fbx/fbximage/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.cad.fileformats.fbx/fbximage/cachedata/)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/)加载额外数据。 |
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
| [TryRemoveEntity](../../aspose.cad.fileformats.fbx/fbximage/tryremoveentity/)(DrawingEntity3D) |  |

### 另请参阅

* [Image](../image/)
* class [Image](../../aspose.cad/image/)
* interface [IHasEntities&lt;T&gt;](../../aspose.cad/ihasentities-1/)
* class [DrawingEntity3D](../../aspose.cad/drawingentity3d/)
* interface [IHasLayouts&lt;TLayout, TEntity&gt;](../../aspose.cad/ihaslayouts-2/)
* interface [IDrawingLayout&lt;T&gt;](../../aspose.cad/idrawinglayout-1/)
* namespace [Aspose.CAD.FileFormats.Fbx](../../aspose.cad.fileformats.fbx/)
* assembly [Aspose.CAD](../../)

