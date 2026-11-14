---
title: "Material.FindChannel"
linktitle: "FindChannel"
articleTitle: "FindChannel"
second_title: "Aspose.CAD for .NET API 参考"
description: "Material 方法。查找 MaterialChannel 的实例。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb/material/findchannel/"
product_version: "26.9"
---
## Material.FindChannel method

查找 [`MaterialChannel`](../../materialchannel/) 的实例。

```csharp
public MaterialChannel? FindChannel(string channelKey)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| channelKey | String | 通道键。目前使用以下值： - "Normal" - "Occlusion" - "Emissive" - 当材质为 `MaterialPBRMetallicRoughness` 时： - "BaseColor" - "MetallicRoughness" - 当材质为 `MaterialPBRSpecularGlossiness` 时： - "Diffuse" - "SpecularGlossiness" |

### 返回值

一个 [`MaterialChannel`](../../materialchannel/) 结构。如果不存在则为 null。

### 另请参阅

* struct [MaterialChannel](../../materialchannel/)
* class [Material](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

