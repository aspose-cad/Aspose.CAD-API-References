---
title: "DracoImage.Depth"
linktitle: "深度"
articleTitle: "深度"
second_title: "Aspose.CAD for .NET API 参考"
description: "DracoImage 属性。获取图像的深度。计算方式为所有顶点中 Z 坐标的最大值与最小值之差。M..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.draco/dracoimage/depth/"
product_version: "26.9"
---
## DracoImage.Depth property

获取图像的深度。
计算方式为所有顶点的 Z 坐标的最大值与最小值之差。
允许的最小深度为 0。

```csharp
public override int Depth { get; }
```

### Property Value

图像的深度。

## 示例

打印 DRACO 绘图的深度。

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The depth of the image is {0}", drcImage.Depth);
}
```

### 另请参阅

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

