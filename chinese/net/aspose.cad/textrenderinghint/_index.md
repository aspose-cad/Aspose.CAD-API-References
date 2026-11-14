---
title: "TextRenderingHint 枚举"
linktitle: "TextRenderingHint"
articleTitle: "TextRenderingHint"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.TextRenderingHint 枚举。指定文本渲染的质量。"
type: docs
weight: 910
url: "/net/aspose.cad/textrenderinghint/"
product_version: "26.9"
---
## TextRenderingHint enumeration

指定文本渲染的质量。

```csharp
public enum TextRenderingHint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SystemDefault | `0` | 每个字符使用其字形位图绘制，采用系统默认的渲染提示。文本将使用用户为系统选择的任何字体平滑设置进行绘制。 |
| SingleBitPerPixelGridFit | `1` | 每个字符使用其字形位图绘制。使用 Hinting 来改善字符在笔画和曲线上的外观。 |
| SingleBitPerPixel | `2` | 每个字符使用其字形位图绘制。未使用 Hinting。 |
| AntiAliasGridFit | `3` | 每个字符使用带有 Hinting 的抗锯齿字形位图绘制。由于抗锯齿，质量大幅提升，但性能开销更高。 |
| AntiAlias | `4` | 每个字符使用未使用 Hinting 的抗锯齿字形位图绘制。由于抗锯齿，质量更好。由于关闭 Hinting，笔画宽度差异可能会更明显。 |
| ClearTypeGridFit | `5` | 每个字符使用带有 Hinting 的 ClearType 字形位图绘制。最高质量设置。用于利用 ClearType 字体特性。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

