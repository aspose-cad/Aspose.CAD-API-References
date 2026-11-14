---
title: "DwfImage.CacheData"
linktitle: "CacheData"
articleTitle: "CacheData"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 方法。缓存数据并确保不会从底层 DataStreamContainer 再次加载额外数据。根据加载 o..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.dwf/dwfimage/cachedata/"
product_version: "26.9"
---
## DwfImage.CacheData method

缓存数据并确保不会从底层 [`DataStreamContainer`](../../../aspose.cad/datastreamsupporter/datastreamcontainer/) 进行额外的数据加载。
根据加载选项，仅必要的数据部分可以从图像数据加载到缓存中。
在这种情况下，我们可以使用此方法将所有图像数据加载到缓存中。

```csharp
public override void CacheData()
```

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

