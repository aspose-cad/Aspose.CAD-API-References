---
title: "PdfOptions.Is3DContent"
linktitle: "Is3DContent"
articleTitle: "Is3DContent"
second_title: "Aspose.CAD for .NET API 参考"
description: "PdfOptions 属性。获取或设置文档内容是否应表示为 3D 模型。允许将 U3D 内容直接导出为 PDF 的一种形式 o..."
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions/pdfoptions/is3dcontent/"
product_version: "26.9"
---
## PdfOptions.Is3DContent property

获取或设置文档内容是否应表示为 3D 模型。
允许将 U3D 内容直接导出为 PDF，以交互式 3D 注释对象的形式。
生成的 PDF 文件将包含占据整个页面（含边距）的单个 3D 模型对象。

```csharp
public bool Is3DContent { get; set; }
```

## 示例

设置将 U3dImage 导出为包含所需尺寸 3D 模型的 PDF。

```csharp
using (U3dImage u3dImage = (U3dImage)Image.Load(fileName))
{
    PdfOptions pdfOptions = new PdfOptions() {Is3DContent = true};
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PageWidth = 1600; 
    rasterizationOptions.PageHeight = 1600; 
    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    u3dImage.Save(outFile, pdfOptions);
}
```

### 另请参阅

* class [PdfOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

