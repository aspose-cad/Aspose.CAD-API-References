---
title: "DxfOptions.OriginPosition"
linktitle: "OriginPosition"
articleTitle: "OriginPosition"
second_title: "Aspose.CAD for .NET API 参考"
description: "DxfOptions 属性。获取或设置原点位置。"
type: docs
weight: 90
url: "/net/aspose.cad.imageoptions/dxfoptions/originposition/"
product_version: "26.9"
---
## DxfOptions.OriginPosition property

获取或设置原点位置。

```csharp
public Point3D OriginPosition { get; set; }
```

### Property Value

文件中项目的原点（起始）位置
默认情况下设置为 (0,0,0)
例如
DxfOptions options = new DxfOptions();
options.OriginPosition = new Point3D(1000, 2000, 3000); //这里是位移坐标
image.Save(filename + ".dxf", options);
结果图像的项目将从 OriginPosition 指定的坐标开始。

### 另请参阅

* class [Point3D](../../../aspose.cad.primitives/point3d/)
* class [DxfOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

