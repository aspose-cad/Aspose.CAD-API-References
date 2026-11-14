---
title: "Path 类"
linktitle: "路径"
articleTitle: "路径"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Path 类。该路径。定义一个将在页面上呈现的单个图形效果。它使用..."
type: docs
weight: 200
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/"
keywords: "Path, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Path class

该路径。
定义一个将在页面上呈现的单个图形效果。
它使用画笔绘制几何形状并在其周围绘制描边。

```csharp
public class Path
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Path](path/)() | 初始化 `Path` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutomationPropertiesHelpText](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/automationpropertieshelptext/) { get; set; } | 获取或设置自动化属性帮助文本。针对可访问性目的，对 Path 的详细描述，尤其是在使用 ImageBrush 填充时。 |
| [AutomationPropertiesName](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/automationpropertiesname/) { get; set; } | 获取或设置自动化属性名称。针对可访问性目的，对 Path 的简要描述，尤其是在使用 ImageBrush 填充时。 |
| [Clip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/clip/) { get; set; } | 获取或设置剪裁。限制元素的渲染区域。 |
| [Data](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/data/) { get; set; } | 获取或设置数据。描述路径的几何形状。 |
| [Fill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/fill/) { get; set; } | 获取或设置填充。描述用于绘制由路径的 Data 属性指定的几何形状的画笔。 |
| [FixedPageNavigateUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/fixedpagenavigateuri/) { get; set; } | Gets or sets the fixed page navigate uri. Associates a hyperlink URI with the element. May be a relative reference or a URI that addresses a resource that is internal to or external to the package. |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/language/) { get; set; } | Gets or sets the language. Specifies the default language used for the current element and for any child or descendant elements. The language is specified according to RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/name/) { get; set; } | Gets or sets the name. Contains a string value that identifies the current element as a named, addressable point in the document for the purpose of hyperlinking. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/opacity/) { get; set; } | 获取或设置不透明度。定义路径元素的统一透明度。取值范围从 0（完全透明）到 1（完全不透明），包括两端。超出此范围的值无效。 |
| [OpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/opacitymask/) { get; set; } | 获取或设置不透明度蒙版。指定一个 alpha 值的蒙版，以与 Opacity 属性相同的方式应用于路径，但允许元素的不同区域使用不同的 alpha 值。 |
| [PathClip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathclip/) { get; set; } | 获取或设置路径剪裁。限制元素的渲染区域。 |
| [PathData](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathdata/) { get; set; } | 获取或设置路径数据。描述路径的几何形状。 |
| [PathFill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathfill/) { get; set; } | 获取或设置路径填充。描述用于绘制由路径的 Data 属性指定的几何形状的画笔。 |
| [PathOpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathopacitymask/) { get; set; } | 获取或设置路径不透明度蒙版。指定一个 alpha 值的蒙版，以与 Opacity 属性相同的方式应用于路径，但允许元素的不同区域使用不同的 alpha 值。 |
| [PathRenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathrendertransform/) { get; set; } | 获取或设置路径渲染变换。为路径的所有属性以及路径的所有子元素（例如由 Path.Data 属性元素定义的几何形状）建立新的坐标系。 |
| [PathStroke](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathstroke/) { get; set; } | 获取或设置路径描边。指定用于绘制描边的画笔。 |
| [RenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/rendertransform/) { get; set; } | 获取或设置渲染变换。为路径的所有属性以及路径的所有子元素（例如由 Path.Data 属性元素定义的几何形状）建立新的坐标系。 |
| [SnapsToDevicePixels](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/snapstodevicepixels/) { get; set; } | 获取或设置一个值，指示是否捕捉到设备像素。在抗锯齿时，消费者控制是否将控制点捕捉到最近的设备像素。有效值为 ‘false’ 和 ‘true’。消费者可能会忽略此属性。 |
| [SnapsToDevicePixelsSpecified](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/snapstodevicepixelsspecified/) { get; set; } | 获取或设置一个值，指示是否已指定捕捉到设备像素。 |
| [Stroke](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/stroke/) { get; set; } | 获取或设置描边。指定用于绘制描边的画笔。 |
| [StrokeDashArray](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedasharray/) { get; set; } | 获取或设置描边虚线数组。指定轮廓描边的虚线和间隙的长度。这些值以描边粗细的倍数形式指定，使用空格分隔的列表，且必须包含偶数个非负值。当绘制描边时，这些值指定的虚线和间隙会重复，以覆盖描边的整个长度。如果省略此属性，描边将实线绘制，不会出现间隙。 |
| [StrokeDashCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedashcap/) { get; set; } | 获取或设置描边虚线端帽。指定每段虚线的端点绘制方式。有效值为 Flat、Round、Square 和 Triangle。 |
| [StrokeDashOffset](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedashoffset/) { get; set; } | 获取或设置描边虚线偏移。调整重复虚线数组模式的起始点。如果省略此值，虚线数组将与描边的原点对齐。值以描边粗细的倍数形式指定。 |
| [StrokeEndLineCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokeendlinecap/) { get; set; } | 获取或设置笔画结束线帽。定义笔画中最后一个短划线末端的形状。有效值为 Flat、Square、Round 和 Triangle。 |
| [StrokeLineJoin](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokelinejoin/) { get; set; } | 获取或设置笔画线段连接方式。指定笔画在路径拐角处的绘制方式。有效值为 Miter、Bevel 和 Round。如果选择 Miter，则在绘制笔画时使用 StrokeMiterLimit 的值。 |
| [StrokeMiterLimit](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokemiterlimit/) { get; set; } | 获取或设置笔画斜接限制。它是最大斜接长度与笔画厚度一半的比率。仅当 StrokeLineJoin 属性指定为 Miter 时，此值才有意义。 |
| [StrokeStartLineCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokestartlinecap/) { get; set; } | 获取或设置笔画起始线帽。定义笔画中第一个短划线起始端的形状。有效值为 Flat、Square、Round 和 Triangle。 |
| [StrokeThickness](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokethickness/) { get; set; } | 获取或设置笔画粗细。指定笔画的粗细，单位为有效坐标空间（包括路径的渲染变换）。笔画绘制在 Path 元素的 Data 属性指定的几何边界之上。StrokeThickness 的一半会延伸到 Data 属性指定的几何之外。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

