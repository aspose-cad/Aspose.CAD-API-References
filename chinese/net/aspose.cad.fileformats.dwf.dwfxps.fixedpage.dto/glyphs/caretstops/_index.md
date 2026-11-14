---
title: "Glyphs.CaretStops"
linktitle: "CaretStops"
articleTitle: "CaretStops"
second_title: "Aspose.CAD for .NET API 参考"
description: "Glyphs 属性。获取或设置插入点停靠位置。标识 Unicode 字符序列中文本选择工具可以放置 ... 的位置。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/caretstops/"
product_version: "26.9"
---
## Glyphs.CaretStops property

获取或设置插入点停靠位置。
标识 Unicode 字符序列中文本选择工具可以放置文本编辑插入点的位置。
潜在的插入点停靠位置通过其在 UnicodeString 属性值所表示的 UTF-16 代码单元中的索引来标识。
当此属性缺失时，UnicodeString 属性值中的文本必须解释为
在每个 Unicode UTF-16 代码单元之间以及文本的开头和结尾都有插入点停靠位置。
该值应指示插入点不能停在大多数组合标记前或 UTF-16 代理对的第二个代码单元前。

```csharp
public string CaretStops { get; set; }
```

### 另请参阅

* class [Glyphs](../)
* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../../)

