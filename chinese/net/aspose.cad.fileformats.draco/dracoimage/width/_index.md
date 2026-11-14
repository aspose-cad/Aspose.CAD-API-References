---
title: "DracoImage.Width"
linktitle: "宽度"
articleTitle: "宽度"
second_title: "Aspose.CAD for .NET API 参考"
description: "DracoImage 属性。获取图像的宽度。计算方式为所有顶点中 X 坐标的最大值与最小值之差。M..."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.draco/dracoimage/width/"
product_version: "26.9"
---
## DracoImage.Width property

获取图像的宽度。
计算方式为所有顶点的 X 坐标最大值与最小值之差。
最小允许宽度为 1。

```csharp
public override int Width { get; }
```

### Property Value

图像的宽度。

## 示例

打印 DRACO 绘图的宽度。

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The width of the image is {0}", drcImage.Width);
}
```

### 另请参阅

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

