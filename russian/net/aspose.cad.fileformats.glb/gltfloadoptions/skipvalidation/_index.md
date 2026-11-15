---
title: "GltfLoadOptions.SkipValidation"
linktitle: "SkipValidation"
articleTitle: "SkipValidation"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство GltfLoadOptions. Определяет, следует ли пропустить проверку для формата GLTF/GLB. Значение по умолчанию: False."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/gltfloadoptions/skipvalidation/"
product_version: "26.9"
---
## GltfLoadOptions.SkipValidation property

Следует ли пропустить проверку для формата GLTF/GLB.
Значение по умолчанию: False.

```csharp
public bool SkipValidation { get; set; }
```

## Примеры

Включение опции пропуска проверки.

```csharp
var fileName = @"C:\path\model.glb";
var gltfLoadOptions = new GltfLoadOptions { SkipValidation = true };
using (var image = Image.Load(fileName, gltfLoadOptions))
{
  // ...
}
```

### См. также

* class [GltfLoadOptions](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

