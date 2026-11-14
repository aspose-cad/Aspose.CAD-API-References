---
title: "DwgImage.AddOle2Frame"
linktitle: "AddOle2Frame"
articleTitle: "AddOle2Frame"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwgImage 方法。使用 BMP 图像数据向图形添加 OLE2FRAME 实体。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.cad/dwgimage/addole2frame/"
product_version: "26.9"
---
## DwgImage.AddOle2Frame method

使用 BMP 图像数据向图形添加 OLE2FRAME 实体。

```csharp
public void AddOle2Frame(byte[] imageData, Cad3DPoint insertPoint = null, double? width = default, 
    double? height = default, bool lockAspectRatio = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | Byte[] | 包含 24 位 BMP 图像数据的字节数组。 |
| insertPoint | Cad3DPoint | OLE2FRAME 实体的插入点。 |
| 宽度 | Nullable`1 | OLE2FRAME 的宽度。 |
| 高度 | Nullable`1 | OLE2FRAME 的高度。 |
| lockAspectRatio | Boolean | 如果为 true，则通过根据宽度或高度调整另一维度来保持图像的宽高比。 |

### 另请参阅

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

