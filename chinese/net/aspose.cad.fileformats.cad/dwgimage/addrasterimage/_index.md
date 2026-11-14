---
title: "DwgImage.AddRasterImage"
linktitle: "AddRasterImage"
articleTitle: "AddRasterImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwgImage 方法。向图形添加光栅 IMAGE 实体。"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.cad/dwgimage/addrasterimage/"
product_version: "26.9"
---
## DwgImage.AddRasterImage method

向图形添加栅格 IMAGE 实体。

```csharp
public void AddRasterImage(string imagePath, Cad3DPoint insertPoint = null, double scale = 1m, 
    short rotation = 0, short brigtness = 50, short contrast = 50, short fade = 0)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imagePath | String | 光栅图像文件的路径。 |
| insertPoint | Cad3DPoint | 图像的插入点。 |
| 缩放 | Double | 统一的图像缩放因子。 |
| 旋转 | Int16 | 图像逆时针旋转角度（以度为单位）。 |
| brigtness | Int16 | 图像亮度值，范围为 [0..100]。 |
| contrast | Int16 | 图像对比度值在范围 [0..100] 内。 |
| 淡化 | Int16 | 图像淡化值在范围 [0..100] 内。 |

### 另请参阅

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

