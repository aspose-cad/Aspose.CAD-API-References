---
title: "DwfImage.GetElementCount"
linktitle: "GetElementCount"
articleTitle: "GetElementCount"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。获取指定页面的图形元素计数。提供确定特定图像页上图形元素数量的能力..."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf/dwfimage/getelementcount/"
product_version: "26.9"
---
## DwfImage.GetElementCount method

获取指定页面的图形元素计数。
提供确定特定图像页面上图形元素数量的能力。
要获取此值，您需要在数组[`Pages`](../pages/)中指定页面索引，以及您想获取的元素数量。

```csharp
public int GetElementCount(int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 获取图形元素计数的页面索引。 |

### 返回值

指定页面中图形元素的计数。

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
    image.RemoveElement(0, image.GetElementCount(0)-1);

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

