---
title: "ImageBrush 类"
linktitle: "ImageBrush"
articleTitle: "ImageBrush"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.ImageBrush 类。图像画刷。ImageBrush 元素用于用图像填充区域。图像 i..."
type: docs
weight: 140
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/"
keywords: "ImageBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ImageBrush class

图像画刷。
ImageBrush 元素用于用图像填充区域。
图像在由其分辨率指定的坐标空间中定义。
图像必须引用文档包内的 JPEG、PNG、TIFF 或 JPEG XR 图像部件。

```csharp
public class ImageBrush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageBrush](imagebrush/)() | 初始化 `ImageBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ImageBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/imagebrushtransform/) { get; set; } | 获取或设置图像画刷的变换。描述应用于画刷坐标空间的矩阵变换。Transform 属性与当前有效的渲染变换连接，以产生相对于画刷的有效渲染变换。画刷的视口使用该局部有效渲染变换进行转换。 |
| [ImageSource](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/imagesource/) { get; set; } | 获取或设置图像源。指定图像资源的 URI，或图像资源与颜色配置文件资源的组合 URI。该 URI 必须引用包中的部件。 |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/opacity/) { get; set; } | 获取或设置不透明度。定义画刷填充的统一透明度。值的范围为 0（完全透明）到 1（完全不透明），包括端点。超出此范围的值无效。 |
| [TileMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/tilemode/) { get; set; } | 获取或设置平铺模式。指定内容在填充区域中的平铺方式。有效值为 None、Tile、FlipX、FlipY 和 FlipXY。 |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/transform/) { get; set; } | 获取或设置变换。描述应用于画刷坐标空间的矩阵变换。Transform 属性与当前有效的渲染变换连接，以产生相对于画刷的有效渲染变换。画刷的视口使用该局部有效渲染变换进行转换。 |
| [Viewbox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewbox/) { get; set; } | 获取或设置视图框。指定画刷源内容的位置和尺寸。指定四个以逗号分隔的实数 (x, y, width, height)，其中宽度和高度为非负数。所指定的尺寸相对于以 1/96" 为单位的图像物理尺寸。视图框的四角映射到视口的四角，从而为画刷的源内容提供默认的裁剪和变换。 |
| [ViewboxUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewboxunits/) { get; set; } | 获取或设置视图框单位。指定视图框坐标与其所在坐标空间的关系。 |
| [Viewport](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewport/) { get; set; } | 获取或设置视口。指定在主画刷瓦片所在的坐标空间中用于（可能重复）填充画刷所应用区域的区域。指定四个以逗号分隔的实数 (x, y, width, height)，其中宽度和高度为非负数。通过调整 x 和 y 值来控制画刷图案的对齐方式。 |
| [ViewportUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewportunits/) { get; set; } | 获取或设置视口单位。指定视口坐标与其所在坐标空间的关系。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

