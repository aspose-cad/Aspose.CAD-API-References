---
title: "DwfImage.Metadata"
linktitle: "元数据"
articleTitle: "元数据"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfImage 属性。获取或设置元数据信息。返回 Dwf/Dwfx 包的清单和描述符资源中的元数据记录数组。"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.dwf/dwfimage/metadata/"
product_version: "26.9"
---
## DwfImage.Metadata property

获取或设置元数据信息。
返回 Dwf/Dwfx 包的清单和描述符资源中的元数据记录数组。

```csharp
public DwfMetadata[] Metadata { get; set; }
```

## 示例

检索所有元数据记录并修改其中一个。

```csharp
string file = "ExampleFile.dwf";
using (DwfImage image = (DwfImage) Aspose.CAD.Image.Load(file))
{
    string outFile = "ExampleFile_Changed.dwf";
    using (FileStream fs = new FileStream(outFile, FileMode.Create))
    {
        DwfMetadata[] metadata = image.Metadata;
        foreach (DwfMetadata dwfMetadata in metadata)
        {
            if (dwfMetadata.Category != "AutoCAD Drawing" || dwfMetadata.Name != "Creator")
            {
                continue;
            }

            dwfMetadata.Value = "Aspose CAD application";
        }

        image.Metadata = metadata;
        ImageOptionsBase options = new DwfOptions { OutputMode = CadOutputMode.Convert };
        image.Save(fs, jpegOptions);
    }
}
```

### 另请参阅

* class [DwfMetadata](../../dwfmetadata/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

