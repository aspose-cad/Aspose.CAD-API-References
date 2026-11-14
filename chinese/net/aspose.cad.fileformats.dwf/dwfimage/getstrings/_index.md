---
title: "DwfImage.GetStrings"
linktitle: "GetStrings"
articleTitle: "GetStrings"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。获取图像中的所有字符串值。提供以...形式获取图像中所有文本图形元素值的机会。"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.dwf/dwfimage/getstrings/"
product_version: "26.9"
---
## DwfImage.GetStrings method

获取图像中的所有字符串值。
提供获取所有存在的文本图形元素值的机会
在图像中，以字符串数组的形式。

```csharp
public override string[] GetStrings()
```

### 返回值

包含字符串值的数组。

## 示例

检索所有文本图形元素的值并将其打印到控制台。

```csharp
string file = "ExampleFile.dwf";
string[] result;
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (Image image = Image.Load(inStream))
{
    result = image.GetStrings();
}

foreach (string s in result)
{
    Console.WriteLine(s);
}
```

### 另请参阅

* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

