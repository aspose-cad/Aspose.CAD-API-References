---
title: "GlbData.GetSatellitePaths"
linktitle: "GetSatellitePaths"
articleTitle: "GetSatellitePaths"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。获取给定 glTF 文件的卫星/依赖文件列表。包括二进制块和纹理图像。"
type: docs
weight: 300
url: "/net/aspose.cad.fileformats.glb/glbdata/getsatellitepaths/"
product_version: "26.9"
---
## GlbData.GetSatellitePaths method

获取给定 glTF 文件的卫星/依赖文件列表。
包括二进制块和纹理图像。

```csharp
public static string[] GetSatellitePaths(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 有效的文件路径。 |

### 返回值

文件中找到的相对文件路径列表。

## 备注

此方法旨在尽可能快，并且避免执行大量
对 glTf 文件的验证和解析，它只是盲目地查找 URI 字段。

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

