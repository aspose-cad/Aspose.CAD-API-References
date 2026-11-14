---
title: "StyleSimulations 枚举"
linktitle: "StyleSimulations"
articleTitle: "StyleSimulations"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.StyleSimulations 枚举。该样式模拟。可以将合成样式模拟应用于字形的形状..."
type: docs
weight: 310
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/stylesimulations/"
product_version: "26.9"
---
## StyleSimulations enumeration

该样式模拟。
可以将合成样式模拟应用于字形的形状
通过使用 StyleSimulations 属性。
样式模拟可以在字体的设计样式之外额外应用。
StyleSimulations 属性的默认值为 None，
在这种情况下，字形的形状保持原始设计，不会被修改。

```csharp
public enum StyleSimulations
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 无。字形的形状保持原始设计，不会被修改。 |
| ItalicSimulation | `1` | 斜体模拟。对 IsSideways 为 false 的字形通过将字符对齐框的顶部边缘向右倾斜 20°（相对于字符基线）来实现合成斜体。 |
| BoldSimulation | `2` | 粗体模拟。通过在字形笔画的两个边界各扩宽 1% 的 EM 大小来实现合成加粗，使笔画中心相对于字符坐标系保持在同一位置。 |
| BoldItalicSimulation | `3` | 粗斜体模拟。同时应用 BoldSimulation 和 ItalicSimulation。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

