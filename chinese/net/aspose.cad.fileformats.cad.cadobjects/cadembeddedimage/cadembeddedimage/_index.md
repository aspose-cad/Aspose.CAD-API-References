---
title: "CadEmbeddedImage.CadEmbeddedImage"
linktitle: "CadEmbeddedImage"
articleTitle: "CadEmbeddedImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadEmbeddedImage 构造函数。初始化 CadRasterImage 类的一个新实例。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadembeddedimage/cadembeddedimage/"
product_version: "26.9"
---
## CadEmbeddedImage constructor

初始化 [`CadRasterImage`](../../cadrasterimage/) 类的一个新实例。

```csharp
public CadEmbeddedImage(CadRasterImageDef imageDef, Cad3DPoint insertionPoint, Cad3DPoint uVector, 
    Cad3DPoint vVector)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageDef | CadRasterImageDef | 图像定义。 |
| insertionPoint | Cad3DPoint | 插入点。 |
| uVector | Cad3DPoint | U 向量。 |
| vVector | Cad3DPoint | V 向量。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当某个参数为 null 时抛出。 |
| ArgumentException | 当 CadRasterImageDef.ObjectHandle 为 null 或为空时抛出 |

### 另请参阅

* class [CadRasterImageDef](../../cadrasterimagedef/)
* class [Cad3DPoint](../../cad3dpoint/)
* class [CadEmbeddedImage](../)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../../)

