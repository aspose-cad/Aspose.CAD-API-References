---
title: "DwfImage.AddElement"
linktitle: "AddElement"
articleTitle: "AddElement"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。将图形元素添加到指定页面。提供向图像中现有图形元素添加新图形元素的机会。要添加它，y..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.dwf/dwfimage/addelement/"
product_version: "26.9"
---
## DwfImage.AddElement method

将图形元素添加到指定页面。
提供向图像中现有图形元素添加新图形元素的机会。
要添加它，您需要创建一个新的图形元素并
指定 [`Pages`](../pages/) 数组中页面的索引，以将元素添加到该页面。

```csharp
public void AddElement(int pageNumber, DwfWhipDrawable element)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 要添加元素的页面在 [`Pages`](../pages/) 数组中的索引。 |
| 元素 | DwfWhipDrawable | 待添加的元素。 |

## 示例

在图像的第一页添加一个新的文本图形元素。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);

using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage) Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    DwfWhipText text = new DwfWhipText();
    text.Text = new DwfString("TEXT");
    text.Color = Color.Red;
    text.Position = new DwfWhipLogicalPoint(4000, 4000);
    text.Font = new DwfWhipFont();
    text.Font.Name = new DwfWhipOptionFontName();
    text.Font.Name.Value = new DwfString("times new roman");
    text.Font.Height = new DwfWhipOptionFontHeight();
    text.Font.Height.Value = 2000;
    text.IsVisible = true;
    image.AddElement(0, text);

    ImageOptionsBase options = new PngOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
                                             {
                                                 DrawType = CadDrawTypeMode.UseObjectColor,
                                             };

    image.Save(stream, options);
}
```

### 另请参阅

* class [DwfWhipDrawable](../../../aspose.cad.fileformats.dwf.whip.objects.drawable/dwfwhipdrawable/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

