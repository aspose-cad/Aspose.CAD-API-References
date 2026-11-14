---
title: "GltfLoadOptions.SkipTangentsCalculation"
linktitle: "SkipTangentsCalculation"
articleTitle: "SkipTangentsCalculation"
second_title: "Aspose.CAD for .NET API 参考"
description: "GltfLoadOptions 属性。是否跳过对 GLTF/GLB 格式的切线图计算。默认值：False。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skiptangentscalculation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipTangentsCalculation property

是否跳过对 GLTF/GLB 格式的切线图计算。
默认值：False。

```csharp
public bool SkipTangentsCalculation { get; set; }
```

## 示例

启用跳过切线图计算的选项。

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipTangentsCalculation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### 另请参阅

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

