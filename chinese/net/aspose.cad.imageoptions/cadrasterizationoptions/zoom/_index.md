---
title: "CadRasterizationOptions.Zoom"
linktitle: "Zoom"
articleTitle: "Zoom"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadRasterizationOptions 属性。获取或设置缩放因子。允许相对于画布大小缩放绘图。值为 1 对应完全适配，值低于..."
type: docs
weight: 20
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/zoom/"
product_version: "26.9"
---
## CadRasterizationOptions.Zoom property

获取或设置缩放因子。允许相对于画布大小缩放绘图。值为 1 表示完全适配，值小于 1 可保留边距，值大于 1 可放大绘图。

```csharp
public float Zoom { get; set; }
```

## 示例

设置缩放以保持整个绘图边界可见

```csharp
using (CadImage cadImage = (CadImage)Image.Load(GetPath(fileName)))
{
    JpegOptions options = new JpegOptions();
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.Zoom = 0.9f;
    options.VectorRasterizationOptions = rasterizationOptions;
    cadImage.Save(outFile, options);
}
```

### 另请参阅

* class [CadRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

