---
title: "DwfImage.RemoveElement"
linktitle: "RemoveElement"
articleTitle: "RemoveElement"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。从指定页面移除图形元素。提供从图像中移除图形元素的功能。要移除它，需要指定…"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.dwf/dwfimage/removeelement/"
product_version: "26.9"
---
## DwfImage.RemoveElement method

从指定页面移除图形元素。
提供从图像中移除图形元素的功能。
要移除它，您需要在[`Pages`](../pages/)数组中指定元素应被移除的页面索引
以及在[`Entities`](../../dwfpage/entities/)数组中元素的索引。

```csharp
public void RemoveElement(int pageNumber, int elementIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 要从中移除元素的[`Pages`](../pages/)数组中的页面索引。 |
| elementIndex | Int32 | 要移除的元素索引。 |

## 示例

从图像的第一页中移除最后一个图形元素。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);

using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage) Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    image.RemoveElement(0, image.Pages[0].Entities.Length-1);

    ImageOptionsBase options = new PngOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
                                             {
                                                 DrawType = CadDrawTypeMode.UseObjectColor,
                                             };

    image.Save(stream, options);
}
```

### 另请参阅

* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

