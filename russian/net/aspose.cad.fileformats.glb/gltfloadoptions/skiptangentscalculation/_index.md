---
title: "GltfLoadOptions.SkipTangentsCalculation"
linktitle: "SkipTangentsCalculation"
articleTitle: "SkipTangentsCalculation"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство GltfLoadOptions. Определяет, следует ли пропустить вычисление карт тангенсов для формата GLTF/GLB. Значение по умолчанию: False."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skiptangentscalculation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipTangentsCalculation property

Следует ли пропустить вычисление карт тангенсов для формата GLTF/GLB.
Значение по умолчанию: False.

```csharp
public bool SkipTangentsCalculation { get; set; }
```

## Примеры

Включение опции пропуска вычисления карт тангенсов.

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipTangentsCalculation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### См. также

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

