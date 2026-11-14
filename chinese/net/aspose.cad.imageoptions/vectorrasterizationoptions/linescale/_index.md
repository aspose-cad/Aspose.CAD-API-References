---
title: "VectorRasterizationOptions.LineScale"
linktitle: "LineScale"
articleTitle: "LineScale"
second_title: "Aspose.CAD for .NET API 参考"
description: "VectorRasterizationOptions 属性。获取或设置相对于原始粗细的线宽缩放因子的值。如果您想要线条粗..."
type: docs
weight: 130
url: "/net/aspose.cad.imageoptions/vectorrasterizationoptions/linescale/"
product_version: "26.9"
---
## VectorRasterizationOptions.LineScale property

获取或设置相对于原始粗细的线宽缩放因子的值。
如果您希望在导出时将线宽增加 2 倍，则需要将该值设置为 2。
如果您希望在导出时将线条粗细降低 4 倍，则需要将值设置为 0.25。

```csharp
public float LineScale { get; set; }
```

## 示例

读取 PLT 格式的图像文件并以 SVG 格式保存图像。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.plt", fileName);
string outFile = string.Format("{0}.svg", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (Image image = Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    ImageOptionsBase options = new SvgOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
                                             {
                                                 LineScale = 0.25f
                                             };

    image.Save(stream, options);
}
```

### 另请参阅

* class [VectorRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

