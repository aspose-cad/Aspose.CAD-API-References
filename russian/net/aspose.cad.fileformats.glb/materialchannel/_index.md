---
title: "Структура MaterialChannel"
linktitle: "MaterialChannel"
articleTitle: "MaterialChannel"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.MaterialChannel struct. Представляет субканал материала, который обычно содержит текстуру. Используйте Channels и FindChannel для доступа..."
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.glb/materialchannel/"
product_version: "26.9"
---
## MaterialChannel struct

Представляет субканал материала, который обычно содержит текстуру.

Используйте [`Channels`](../material/channels/) и [`FindChannel`](../material/findchannel/) для доступа к нему.

```csharp
public struct MaterialChannel
```

## Свойства

| Имя | Описание |
| --- | --- |
| Color { get; set; } |  |
| HasDefaultContent { get; } |  |
| Key { get; } |  |
| LogicalParent { get; } |  |
| Parameters { get; } |  |
| Texture { get; } | Получает [`Texture`](./texture/) экземпляр, используемый этим материалом, или null. |
| TextureCoordinate { get; } | Получает индекс атрибута TEXCOORD_[index] текстуры, используемого для отображения координат текстуры. |
| TextureSampler { get; } |  |
| TextureTransform { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| Equals(MaterialChannel) |  |
| Equals(object) |  |
| GetFactor(string) |  |
| GetHashCode() |  |
| SetFactor(string, float) |  |
| SetTexture(int, Texture) |  |
| SetTexture(int, ImageGlb, ImageGlb, TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) |  |
| SetTransform(Vector2, Vector2, float, int?) |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

