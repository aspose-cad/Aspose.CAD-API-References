---
title: "MaterialChannel Struct"
linktitle: "MaterialChannel"
articleTitle: "MaterialChannel"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.MaterialChannel struct. Represents a material sub-channel, which usually contains a texture. Use Channels and FindChannel to acces..."
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.glb/materialchannel/"
product_version: "26.9"
---
## MaterialChannel struct

Represents a material sub-channel, which usually contains a texture.

 Use [`Channels`](../material/channels/) and [`FindChannel`](../material/findchannel/) to access it.

```csharp
public struct MaterialChannel
```

## Properties

| Name | Description |
| --- | --- |
| Color { get; set; } |  |
| HasDefaultContent { get; } |  |
| Key { get; } |  |
| LogicalParent { get; } |  |
| Parameters { get; } |  |
| Texture { get; } | Gets the [`Texture`](./texture/) instance used by this Material, or null. |
| TextureCoordinate { get; } | Gets the index of texture's TEXCOORD_[index] attribute used for texture coordinate mapping. |
| TextureSampler { get; } |  |
| TextureTransform { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| Equals(MaterialChannel) |  |
| Equals(object) |  |
| GetFactor(string) |  |
| GetHashCode() |  |
| SetFactor(string, float) |  |
| SetTexture(int, Texture) |  |
| SetTexture(int, ImageGlb, ImageGlb, TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) |  |
| SetTransform(Vector2, Vector2, float, int?) |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

