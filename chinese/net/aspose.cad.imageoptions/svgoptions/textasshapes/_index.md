---
title: "SvgOptions.TextAsShapes"
linktitle: "TextAsShapes"
articleTitle: "TextAsShapes"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。获取或设置一个值，指示文本是否必须转换为形状。默认情况下，文本将被转换为形状，因此它不会被..."
type: docs
weight: 20
url: "/net/aspose.cad.imageoptions/svgoptions/textasshapes/"
product_version: "26.9"
---
## SvgOptions.TextAsShapes property

获取或设置一个值，指示文本是否必须转换为形状。
默认情况下，文本将被转换为形状，因此它将不可选择。

```csharp
public bool TextAsShapes { get; set; }
```

### Property Value

`true` 表示所有文本应在转换中转换为 SVG 形状；否则为 `false`。

## 示例

```csharp
using (var img = Image.Load(file))
{
     CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
     SvgOptions opt = new SvgOptions();
     opt.TextAsShapes = true;
     opt.VectorRasterizationOptions = cadRasterizationOptions;
     img.Save(outFile, opt);
}
```

### 另请参阅

* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

