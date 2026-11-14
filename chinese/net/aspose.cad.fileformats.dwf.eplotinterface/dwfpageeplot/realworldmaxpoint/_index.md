---
title: "DwfPageEPlot.RealWorldMaxPoint"
linktitle: "RealWorldMaxPoint"
articleTitle: "RealWorldMaxPoint"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfPageEPlot 属性。获取按真实世界单位缩放的实体坐标的最大值。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldmaxpoint/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldMaxPoint property

获取以真实世界单位缩放的实体坐标的最大值。

```csharp
public Cad3DPoint RealWorldMaxPoint { get; }
```

### 返回值

实体坐标按真实世界单位缩放的最大值，若资源不包含 'Units' 操作数，则为 'null' 值。

## 示例

获取按真实世界单位缩放的图像宽度和高度。

```csharp
string file = "ExampleFile.dwf";
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        Cad3DPoint maxPoint = page.RealWorldMaxPoint;
        Cad3DPoint minPoint = page.RealWorldMinPoint;
        double width = maxPoint.X - minPoint.X;
        double height = maxPoint.Y - minPoint.Y;
    }
}
```

### 另请参阅

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

