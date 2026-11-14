---
title: "GlbData.LoadGlbImage"
linktitle: "LoadGlbImage"
articleTitle: "LoadGlbImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。读取一个指向 GLB 或 GLTF 文件的路径中的 GlbData 实例"
type: docs
weight: 260
url: "/net/aspose.cad.fileformats.glb/glbdata/loadglbimage/"
product_version: "26.9"
---
## GlbData.LoadGlbImage method

读取一个指向 GLB 或 GLTF 文件的路径中的 [`GlbData`](../) 实例

```csharp
public static GlbData LoadGlbImage(string filePath, ReadSettings settings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 有效的文件路径。 |
| settings | ReadSettings | 可选设置。 |

### 返回值

一个 [`GlbData`](../) 实例。

## 备注

*settings* can be either a plain [`ReadSettings`](../../readsettings/) instance,
或者一个 `ReadContext`，在这种情况下，将使用该上下文读取
其中的文件。

### 另请参阅

* class [GlbData](../)
* class [ReadSettings](../../readsettings/)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

