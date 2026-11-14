---
title: "DracoImage.Height"
linktitle: "高度"
articleTitle: "高度"
second_title: "Aspose.CAD for .NET API 参考"
description: "DracoImage 属性。获取图像的高度。计算方式为所有顶点中 Y 坐标的最大值与最小值之差。..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.draco/dracoimage/height/"
product_version: "26.9"
---
## DracoImage.Height property

获取图像的高度。
计算方式为所有顶点的 Y 坐标的最大值与最小值之差。
允许的最小高度为 1。

```csharp
public override int Height { get; }
```

### Property Value

图像的高度。

## 示例

打印 DRACO 绘图的高度。

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The height of the image is {0}", drcImage.Height);
}
```

### 另请参阅

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

