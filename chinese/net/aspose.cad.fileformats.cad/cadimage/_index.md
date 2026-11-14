---
title: "CadImage 类"
linktitle: "CadImage"
articleTitle: "CadImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadImage 类。CAD 图像类"
type: docs
weight: 170
url: "/net/aspose.cad.fileformats.cad/cadimage/"
keywords: "CadImage, Aspose.CAD.FileFormats.Cad, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadImage class

Cad 图像类

```csharp
public class CadImage : Image, IHasEntities<CadEntityBase>, IHasLayouts<CadLayout, CadEntityBase>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadImage](cadimage/)() | 初始化 `CadImage` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActivePage](../../aspose.cad.fileformats.cad/cadimage/activepage/) { get; } | 获取活动页面。 |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [AppIdTables](../../aspose.cad.fileformats.cad/cadimage/appidtables/) { get; set; } | 获取或设置应用程序标识符表。 |
| [ApplicationVersion](../../aspose.cad.fileformats.cad/cadimage/applicationversion/) { get; set; } | 获取或设置应用程序版本。 |
| [BlockEntities](../../aspose.cad.fileformats.cad/cadimage/blockentities/) { get; set; } | 获取或设置块实体。 |
| [BlocksTables](../../aspose.cad.fileformats.cad/cadimage/blockstables/) { get; set; } | 获取或设置块表。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [CadAcds](../../aspose.cad.fileformats.cad/cadimage/cadacds/) { get; set; } | 获取或设置 CadAcds 列表 |
| [ClassEntities](../../aspose.cad.fileformats.cad/cadimage/classentities/) { get; set; } | 获取或设置类实体。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| override [CustomProperties](../../aspose.cad.fileformats.cad/cadimage/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DefaultFont](../../aspose.cad.fileformats.cad/cadimage/defaultfont/) { get; set; } | 获取或设置默认字体。 |
| [DefaultLineWeight](../../aspose.cad.fileformats.cad/cadimage/defaultlineweight/) { get; set; } | 获取或设置默认线宽。 |
| override [Depth](../../aspose.cad.fileformats.cad/cadimage/depth/) { get; } | 获取图像深度。 |
| [DimensionStyles](../../aspose.cad.fileformats.cad/cadimage/dimensionstyles/) { get; set; } | 获取或设置标注样式。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Entities](../../aspose.cad.fileformats.cad/cadimage/entities/) { get; set; } | 获取或设置实体。 |
| [FileEncoding](../../aspose.cad.fileformats.cad/cadimage/fileencoding/) { get; set; } | 获取文件的编码 |
| [Header](../../aspose.cad.fileformats.cad/cadimage/header/) { get; set; } | 获取或设置标题。 |
| override [Height](../../aspose.cad.fileformats.cad/cadimage/height/) { get; } | 获取图像高度。 |
| override [IsCached](../../aspose.cad.fileformats.cad/cadimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [Layers](../../aspose.cad.fileformats.cad/cadimage/layers/) { get; set; } | 获取或设置图层。 |
| [Layouts](../../aspose.cad.fileformats.cad/cadimage/layouts/) { get; } | 获取针对 AutoCAD 格式的特定信息的布局。 |
| [LineTypes](../../aspose.cad.fileformats.cad/cadimage/linetypes/) { get; set; } | 获取或设置标注样式。 |
| [MaintenanceVersion](../../aspose.cad.fileformats.cad/cadimage/maintenanceversion/) { get; set; } | 获取或设置维护版本。 |
| [MaxPoint](../../aspose.cad.fileformats.cad/cadimage/maxpoint/) { get; } | 获取最大点。 |
| [MinPoint](../../aspose.cad.fileformats.cad/cadimage/minpoint/) { get; } | 获取最小点。 |
| [Objects](../../aspose.cad.fileformats.cad/cadimage/objects/) { get; set; } | 获取或设置对象。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [SectionsData](../../aspose.cad.fileformats.cad/cadimage/sectionsdata/) { get; } |  |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| [SpecifiedEncoding](../../aspose.cad.fileformats.cad/cadimage/specifiedencoding/) { get; set; } | 获取或设置指定的编码。 |
| [SpecifiedMifEncoding](../../aspose.cad.fileformats.cad/cadimage/specifiedmifencoding/) { get; set; } | 获取或设置指定的 MIF 字符编码 |
| [Styles](../../aspose.cad.fileformats.cad/cadimage/styles/) { get; set; } | 获取或设置样式。 |
| [ThumbnailImage](../../aspose.cad.fileformats.cad/cadimage/thumbnailimage/) { get; set; } | 获取或设置缩略图。 |
| [UCSs](../../aspose.cad.fileformats.cad/cadimage/ucss/) { get; set; } | 获取或设置 uc ss。 |
| virtual [UnitType](../../aspose.cad/image/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| [ViewPorts](../../aspose.cad.fileformats.cad/cadimage/viewports/) { get; set; } | 获取或设置视口。 |
| [Views](../../aspose.cad.fileformats.cad/cadimage/views/) { get; set; } | 获取或设置视图。 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.cad/cadimage/width/) { get; } | 获取图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddCustomProperty](../../aspose.cad.fileformats.cad/cadimage/addcustomproperty/)(string, string) | 向图形添加自定义属性 |
| override [CacheData](../../aspose.cad.fileformats.cad/cadimage/cachedata/)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/)加载额外数据。 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [ChangeCustomProperty](../../aspose.cad.fileformats.cad/cadimage/changecustomproperty/)(string, string) | 使用新值更新自定义属性及相关 CAD 字段对象。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| [ExplodeInsert](../../aspose.cad.fileformats.cad/cadimage/explodeinsert/)(string, bool) | 展开插入对象并将其包含的实体放置在该插入位置，同时返回这些实体 |
| [GetBounds](../../aspose.cad.fileformats.cad/cadimage/getbounds/#getbounds)() | 为所有实体填充 Bounds 属性（包含实体的最小和最大点）。 |
| [GetBounds](../../aspose.cad.fileformats.cad/cadimage/getbounds/#getbounds_1)(CadEntityBase) | 为实体填充 Bounds 属性（包含最小和最大点）。 |
| override [GetStrings](../../aspose.cad.fileformats.cad/cadimage/getstrings/)() | 获取图像中的所有字符串值。 |
| [RemoveCustomProperty](../../aspose.cad.fileformats.cad/cadimage/removecustomproperty/)(string) | 从图形中移除自定义属性。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| virtual [TryRemoveEntity](../../aspose.cad.fileformats.cad/cadimage/tryremoveentity/)(CadEntityBase) | 从块中移除 DWG 格式的实体。 |
| [UpdateSize](../../aspose.cad.fileformats.cad/cadimage/updatesize/)(bool) | 在更改后更新图像的大小，这可能影响初始尺寸，例如移除实体。图像的 MinPoint、MaxPoint、Width 和 Height 属性已更新。 |

### 另请参阅

* class [Image](../../aspose.cad/image/)
* interface [IHasEntities&lt;T&gt;](../../aspose.cad/ihasentities-1/)
* class [CadEntityBase](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* interface [IHasLayouts&lt;TLayout, TEntity&gt;](../../aspose.cad/ihaslayouts-2/)
* class [CadLayout](../../aspose.cad.fileformats.cad.cadobjects/cadlayout/)
* namespace [Aspose.CAD.FileFormats.Cad](../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../)

