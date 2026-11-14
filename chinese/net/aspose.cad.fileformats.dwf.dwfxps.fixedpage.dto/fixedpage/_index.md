---
title: "FixedPage 类"
linktitle: "FixedPage"
articleTitle: "FixedPage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.FixedPage 类。该固定页面。FixedPage 元素包含页面的内容，并且是根元素..."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/"
keywords: "FixedPage, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## FixedPage class

固定页面。
FixedPage 元素包含页面的内容，并且是 FixedPage 部分的根元素。
固定页面包含一起构成页面上所有标记渲染基础的元素：Paths、[Glyphs](../glyphs/)，
以及可选的 [Canvas](../canvas/) 分组元素。

```csharp
public class FixedPage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FixedPage](fixedpage/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BleedBox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/bleedbox/) { get; set; } | 获取或设置出血框。指定 ContentBox 与所有旨在在最终打印和裁剪页面上出现的图形内容的边界框的并集。包含四个坐标值的列表 (BleedOriginX, BleedOriginY, BleedWidth, BleedHeight)，以逗号分隔的实数表示。如果省略，默认值为 (0,0, Width, Height)。 |
| [ContentBox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/contentbox/) { get; set; } | 获取或设置内容框。指定页面中包含图像内容的区域，在打印或查看时应适配到图像区域。包含四个坐标值的列表 (ContentOriginX, ContentOriginY, ContentWidth, ContentHeight)，以逗号分隔的实数表示。建议指定该值。如果省略，默认值为 (0,0,Width,Height)。 |
| [FixedPageResources](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/fixedpageresources/) { get; set; } | 获取或设置固定页面资源。固定页面标记支持使用资源。资源是以标记形式表达的可重用属性值，由键标识并存储在资源字典中。一般而言，任何可以使用属性元素语法表达的属性值都可以保存在资源字典中。 |
| [Height](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/height/) { get; set; } | 获取或设置高度。页面的高度，以有效坐标空间的单位表示的实数。 |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/items/) { get; set; } | 获取或设置元素数组。固定页面包含一起构成页面上所有标记渲染基础的元素：Paths、Glyphs，以及可选的 Canvas 分组元素。 |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/language/) { get; set; } | Gets or sets the language. Specifies the default language used for the current element and for any child or descendant elements. The language is specified according to RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/name/) { get; set; } | Gets or sets the name. Contains a string value that identifies the current element as a named, addressable point in the document for the purpose of hyperlinking. |
| [Width](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/fixedpage/width/) { get; set; } | 获取或设置宽度。页面的宽度，以有效坐标空间的单位表示的实数。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

