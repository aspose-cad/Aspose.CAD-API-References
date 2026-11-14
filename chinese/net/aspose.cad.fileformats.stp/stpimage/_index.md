---
title: "StpImage 类"
linktitle: "StpImage"
articleTitle: "StpImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Stp.StpImage 类。STP 图像类。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.stp/stpimage/"
keywords: "StpImage, Aspose.CAD.FileFormats.Stp, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StpImage class

STP 图像类。

```csharp
public class StpImage : Image
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StpImage](stpimage/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Author](../../aspose.cad.fileformats.stp/stpimage/author/) { get; set; } |  |
| [Authorization](../../aspose.cad.fileformats.stp/stpimage/authorization/) { get; set; } |  |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Collections](../../aspose.cad.fileformats.stp/stpimage/collections/) { get; } | 用于简化遍历 STP 数据的有用集合。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| override [Depth](../../aspose.cad.fileformats.stp/stpimage/depth/) { get; } | 获取图像深度。 |
| [Description](../../aspose.cad.fileformats.stp/stpimage/description/) { get; set; } |  |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.stp/stpimage/height/) { get; } | 获取图像高度。 |
| [ImplementationLevel](../../aspose.cad.fileformats.stp/stpimage/implementationlevel/) { get; set; } |  |
| override [IsCached](../../aspose.cad.fileformats.stp/stpimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Items](../../aspose.cad.fileformats.stp/stpimage/items/) { get; } |  |
| [Name](../../aspose.cad.fileformats.stp/stpimage/name/) { get; set; } |  |
| [Organization](../../aspose.cad.fileformats.stp/stpimage/organization/) { get; set; } |  |
| [OriginatingSystem](../../aspose.cad.fileformats.stp/stpimage/originatingsystem/) { get; set; } |  |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [PreprocessorVersion](../../aspose.cad.fileformats.stp/stpimage/preprocessorversion/) { get; set; } |  |
| [Schemas](../../aspose.cad.fileformats.stp/stpimage/schemas/) { get; } |  |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| [Timestamp](../../aspose.cad.fileformats.stp/stpimage/timestamp/) { get; set; } |  |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| [UnsupportedSchemas](../../aspose.cad.fileformats.stp/stpimage/unsupportedschemas/) { get; } |  |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.stp/stpimage/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Append](../../aspose.cad.fileformats.stp/stpimage/append/)(StpImage) | 追加另一个 STP 图像的内容。此功能允许您合并不同 STP 图像的内容。在下面的示例中，模型从文件加载，然后合并为单个图像。生成的 STP 图像将包含每个已加载 STP 文件中的所有基元。 |
| override [CacheData](../../aspose.cad.fileformats.stp/stpimage/cachedata/)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/)加载额外数据。 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [CopyHeaderValues](../../aspose.cad.fileformats.stp/stpimage/copyheadervalues/)(StpImage) |  |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| [GetLogicalModelsTree](../../aspose.cad.fileformats.stp/stpimage/getlogicalmodelstree/)() | 将 LogicalModels 树结构输出为字符串。 |
| virtual [GetStrings](../../aspose.cad/image/getstrings/)() | 获取图像中的所有字符串值。 |
| [GetTopLevelItems](../../aspose.cad.fileformats.stp/stpimage/gettoplevelitems/)() | 获取文件中所有顶层项（即未被其他项引用的项）。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [UpdateSize](../../aspose.cad.fileformats.stp/stpimage/updatesize/)() |  |

### 另请参阅

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.Stp](../../aspose.cad.fileformats.stp/)
* assembly [Aspose.CAD](../../)

