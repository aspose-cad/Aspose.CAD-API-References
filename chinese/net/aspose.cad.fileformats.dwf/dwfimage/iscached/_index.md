---
title: "DwfImage.IsCached"
linktitle: "IsCached"
articleTitle: "IsCached"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 属性。获取一个值，指示对象的数据当前是否已缓存且不需要读取数据。根据加载选项，仅…"
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.dwf/dwfimage/iscached/"
product_version: "26.9"
---
## DwfImage.IsCached property

获取一个值，指示对象的数据当前是否已缓存且无需读取数据。
根据加载选项，仅必要的数据部分可以从图像数据加载到缓存中。
在这种情况下，我们可以使用此属性来确定仅有图像数据的一部分被加载到缓存中。

```csharp
public override bool IsCached { get; }
```

### Property Value

`true` 如果对象的数据已缓存；否则，`false`。

## 示例

检查对象的数据当前是否已缓存，如果未缓存，则进行缓存。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);

using (FileStream inStream = new FileStream(file, FileMode.Open))
using (var image = (DwfImage) Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{

    if(!image.IsCached)
    {
        image.CacheData();
    }

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

