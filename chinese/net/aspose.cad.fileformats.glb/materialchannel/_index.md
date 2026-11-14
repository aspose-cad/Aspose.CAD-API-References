---
title: "MaterialChannel 结构体"
linktitle: "MaterialChannel"
articleTitle: "MaterialChannel"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.MaterialChannel 结构体。表示材料子通道，通常包含纹理。使用 Channels 和 FindChannel 进行访问..."
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.glb/materialchannel/"
product_version: "26.9"
---
## MaterialChannel struct

表示一个材质子通道，通常包含纹理。

使用 [`Channels`](../material/channels/) 和 [`FindChannel`](../material/findchannel/) 来访问它。

```csharp
public struct MaterialChannel
```

## 属性

| 名称 | 描述 |
| --- | --- |
| Color { get; set; } |  |
| HasDefaultContent { get; } |  |
| 键 { get; } |  |
| 逻辑父级 { get; } |  |
| 参数 { get; } |  |
| Texture { get; } | 获取此材质使用的[`Texture`](./texture/)实例，或 null。 |
| 纹理坐标 { get; } | 获取纹理用于纹理坐标映射的 TEXCOORD_[index] 属性的索引。 |
| 纹理采样器 { get; } |  |
| 纹理变换 { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| 等于(MaterialChannel) |  |
| Equals(object) |  |
| 获取因子(string) |  |
| GetHashCode() |  |
| 设置因子(string, float) |  |
| 设置纹理(int, Texture) |  |
| 设置纹理(int, ImageGlb, ImageGlb, TextureWrapMode, TextureWrapMode, TextureMipMapFilter, TextureInterpolationFilter) |  |
| 设置变换(Vector2, Vector2, float, int?) |  |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

