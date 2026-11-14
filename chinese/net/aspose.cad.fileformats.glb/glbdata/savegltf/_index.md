---
title: "GlbData.SaveGLTF"
linktitle: "SaveGLTF"
articleTitle: "SaveGLTF"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。将此 GlbData 写入 GLTF 格式的文件。"
type: docs
weight: 410
url: "/net/aspose.cad.fileformats.glb/glbdata/savegltf/"
product_version: "26.9"
---
## SaveGLTF(string, WriteSettings) {#savegltf}

将此 [`GlbData`](../) 写入 GLTF 格式的文件。

```csharp
public void SaveGLTF(string filePath, WriteSettings settings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于写入的有效文件路径。 |
| settings | WriteSettings | 可选设置。 |

## 备注

诸如缓冲区和图像等卫星文件也会以 "FILE_{Index}.EXT" 的格式保存文件名。

### 另请参阅

* class [WriteSettings](../../writesettings/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## SaveGLTF(Stream, Stream, Stream, string, WriteSettings) {#savegltf_1}



```csharp
public void SaveGLTF(Stream stream, Stream gltfStream, Stream binStream, string name, 
    WriteSettings settings = null)
```

### 另请参阅

* class [WriteSettings](../../writesettings/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

