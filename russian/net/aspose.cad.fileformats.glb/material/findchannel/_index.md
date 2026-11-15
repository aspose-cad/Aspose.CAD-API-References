---
title: "Material.FindChannel"
linktitle: "FindChannel"
articleTitle: "FindChannel"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Material. Находит экземпляр MaterialChannel"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb/material/findchannel/"
product_version: "26.9"
---
## Material.FindChannel method

Находит экземпляр [`MaterialChannel`](../../materialchannel/)

```csharp
public MaterialChannel? FindChannel(string channelKey)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| channelKey | String | Ключ канала. В настоящее время используются следующие значения: - "Normal" - "Occlusion" - "Emissive" - Когда материал является `MaterialPBRMetallicRoughness`: - "BaseColor" - "MetallicRoughness" - Когда материал является `MaterialPBRSpecularGlossiness`: - "Diffuse" - "SpecularGlossiness" |

### Возвращаемое значение

Структура [`MaterialChannel`](../../materialchannel/). Или null, если она не существует.

### См. также

* struct [MaterialChannel](../../materialchannel/)
* class [Material](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

