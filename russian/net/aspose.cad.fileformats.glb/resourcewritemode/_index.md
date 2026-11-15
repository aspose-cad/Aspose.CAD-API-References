---
title: "ResourceWriteMode enum"
linktitle: "ResourceWriteMode"
articleTitle: "ResourceWriteMode"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.ResourceWriteMode enum. Определяет, как записываются ресурсы."
type: docs
weight: 460
url: "/net/aspose.cad.fileformats.glb/resourcewritemode/"
product_version: "26.9"
---
## ResourceWriteMode enumeration

Определяет, как записываются ресурсы.

```csharp
public enum ResourceWriteMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | `0` | Используйте наиболее подходящий режим. |
| SatelliteFile | `1` | Ресурсы будут храниться во внешних спутниковых файлах. |
| EmbeddedAsBase64 | `2` | Ресурсы будут встроены в JSON, закодированный в Base64. |
| BufferView | `3` | Ресурсы будут храниться во внутренних бинарных буферах. Действительно только для [`ImageGlb`](../imageglb/). |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

