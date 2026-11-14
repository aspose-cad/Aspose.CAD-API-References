---
title: "StpImage.Append"
linktitle: "追加"
articleTitle: "追加"
second_title: "Aspose.CAD for .NET API 参考"
description: "StpImage 方法。追加另一个 STP 图像的内容。此功能允许您合并不同 STP 图像的内容。在下面的示例中，mode..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.stp/stpimage/append/"
product_version: "26.9"
---
## StpImage.Append method

追加另一个 STP 图像的内容。
此功能允许您合并不同 STP 图像的内容。在示例中
下面，模型从文件加载，然后合并为单个图像。结果
STP 图像将包含每个已加载 STP 文件中的所有基元。

```csharp
public void Append(StpImage imageToAppend)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageToAppend | StpImage | 要追加的图像。 |

## 示例

加载 STP 图像，将它们合并为统一的结果图像，并保存最终
输出到文件。

```csharp
string[] files = new string[] { "inFile1.stp", "inFile2.stp", "inFile3.stp" };
string outFile = "outFile.stp";
StpImage mergedImage = new StpImage();
foreach (var file in files)
    using (StpImage image = (StpImage) Image.Load(file))
        mergedImage.Append(image);
mergedImage.Save(outFile, new StpOptions());
```

### 另请参阅

* class [StpImage](../)
* namespace [Aspose.CAD.FileFormats.Stp](../../../aspose.cad.fileformats.stp/)
* assembly [Aspose.CAD](../../../)

