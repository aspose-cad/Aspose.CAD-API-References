---
title: "Canvas 类"
linktitle: "Canvas"
articleTitle: "Canvas"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Canvas 类。画布。Canvas 元素将元素组合在一起。字形和路径元素可以被分组..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/"
keywords: "Canvas, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Canvas class

画布。
Canvas 元素将元素组合在一起。
 [Glyphs](../glyphs/) and [Path](../path/) elements can be grouped in a canvas in order to be identified as a unit(as a hyperlink destination)
或将组合属性值应用于每个子元素和祖先元素。

```csharp
public class Canvas
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Canvas](canvas/)() | 初始化 `Canvas` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutomationPropertiesHelpText](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/automationpropertieshelptext/) { get; set; } | 获取或设置自动化属性帮助文本。对 Canvas 内容的详细描述，用于辅助功能，特别是当其包含一组图形和文本元素，旨在组成单个矢量图形时。 |
| [AutomationPropertiesName](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/automationpropertiesname/) { get; set; } | 获取或设置自动化属性名称。对 Canvas 内容的简要描述，用于辅助功能，特别是当其包含一组矢量图形和文本元素，旨在组成单个矢量图形时。 |
| [CanvasClip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasclip/) { get; set; } | 获取或设置画布剪裁。限制元素的渲染区域。 |
| [CanvasOpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasopacitymask/) { get; set; } | 获取或设置画布不透明度蒙版。指定一组 alpha 值的蒙版，以与 Opacity 属性相同的方式应用于画布，但允许元素的不同区域使用不同的 alpha 值。 |
| [CanvasRenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasrendertransform/) { get; set; } | 获取或设置画布渲染变换。为画布的子元素和后代元素（例如另一个画布）建立新的坐标系。也会影响剪裁和不透明度蒙版。 |
| [CanvasResources](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasresources/) { get; set; } | 获取或设置画布资源。包含 Canvas 元素的资源字典。 |
| [Clip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/clip/) { get; set; } | 获取或设置剪裁。限制元素的渲染区域。 |
| [FixedPageNavigateUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/fixedpagenavigateuri/) { get; set; } | Gets or sets the fixed page navigate uri. Associates a hyperlink URI with the element. May be a relative reference or a URI that addresses a resource that is internal to or external to the package. |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/items/) { get; set; } | 获取或设置项。将 FixedPage 的后代元素分组在一起。 |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/language/) { get; set; } | Gets or sets the language. Specifies the default language used for the current element and for any child or descendant elements. The language is specified according to RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/name/) { get; set; } | Gets or sets the name. Contains a string value that identifies the current element as a named, addressable point in the document for the purpose of hyperlinking. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/opacity/) { get; set; } | 获取或设置不透明度。定义画布的统一透明度。取值范围为 0（完全透明）到 1（完全不透明），包括端点。超出此范围的值无效。 |
| [OpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/opacitymask/) { get; set; } | 获取或设置不透明度蒙版。指定一组 alpha 值的蒙版，以与 Opacity 属性相同的方式应用于画布，但允许元素的不同区域使用不同的 alpha 值。 |
| [RenderOptionsEdgeMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/renderoptionsedgemode/) { get; set; } | 获取或设置渲染选项边缘模式。控制画布内路径的边缘渲染方式。唯一有效的值是 Aliased。省略此属性将导致边缘以使用者的默认方式渲染。 |
| [RenderOptionsEdgeModeSpecified](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/renderoptionsedgemodespecified/) { get; set; } | 获取或设置一个值，指示是否已指定渲染选项边缘模式。 |
| [RenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/rendertransform/) { get; set; } | 获取或设置渲染变换。为画布的子元素和后代元素（例如另一个画布）建立新的坐标系。也会影响剪裁和不透明度蒙版。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

