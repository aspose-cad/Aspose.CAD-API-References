---
title: "CadRasterizationOptions.PenOptions"
linktitle: "PenOptions"
articleTitle: "PenOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadRasterizationOptions 属性。获取或设置笔选项。"
type: docs
weight: 30
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/penoptions/"
product_version: "26.9"
---
## CadRasterizationOptions.PenOptions property

获取或设置笔选项。

```csharp
public PenOptions PenOptions { get; set; }
```

### Property Value

笔选项。

## 示例

设置 "方形" 笔

```csharp
using (CadImage cadImage = (CadImage)Image.Load(GetPath(fileName)))
{
    JpegOptions options = new JpegOptions();
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PenOptions = new PenOptions() { StartCap = LineCap.Square, EndCap = LineCap.Square };
    options.VectorRasterizationOptions = rasterizationOptions;
    cadImage.Save(outFile, options);
}
```

### 另请参阅

* class [PenOptions](../../penoptions/)
* class [CadRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

