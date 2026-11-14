---
title: "GltfLoadOptions.SkipValidation"
linktitle: "SkipValidation"
articleTitle: "SkipValidation"
second_title: "Aspose.CAD for .NET API 参考"
description: "GltfLoadOptions 属性。是否跳过对 GLTF/GLB 格式的验证。默认值：False。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skipvalidation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipValidation property

是否跳过对 GLTF/GLB 格式的验证。
默认值：False。

```csharp
public bool SkipValidation { get; set; }
```

## 示例

启用跳过验证的选项。

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipValidation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### 另请参阅

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

