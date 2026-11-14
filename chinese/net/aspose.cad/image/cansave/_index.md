---
title: "Image.CanSave"
linktitle: "CanSave"
articleTitle: "CanSave"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。确定图像是否可以保存为由传入的保存选项表示的指定文件格式。"
type: docs
weight: 130
url: "/net/aspose.cad/image/cansave/"
product_version: "26.9"
---
## Image.CanSave method

确定图像是否可以保存为由传入的保存选项表示的指定文件格式。

```csharp
public bool CanSave(ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | ImageOptionsBase | 要使用的保存选项。 |

### 返回值

`true` 表示图像可以保存为由传入的保存选项表示的指定文件格式；否则为 `false`。

## 示例

检查是否可以使用默认选项导出为 BMP。

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    if (image.CanSave(new BmpOptions()))
    {
        // 使用此选项可以导出为 BMP 格式。
    }
}
```

### 另请参阅

* class [ImageOptionsBase](../../../aspose.cad.imageoptions/imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

