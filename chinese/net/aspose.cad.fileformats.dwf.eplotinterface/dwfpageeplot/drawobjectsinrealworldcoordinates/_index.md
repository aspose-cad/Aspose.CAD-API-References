---
title: "DwfPageEPlot.DrawObjectsInRealWorldCoordinates"
linktitle: "DrawObjectsInRealWorldCoordinates"
articleTitle: "DrawObjectsInRealWorldCoordinates"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfPageEPlot 属性。获取来自角色为 '2d streaming graphics' 的资源中，按真实世界单位缩放的实体集合。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/drawobjectsinrealworldcoordinates/"
product_version: "26.9"
---
## DwfPageEPlot.DrawObjectsInRealWorldCoordinates property

获取来自角色为 '2d streaming graphics' 的资源中，以真实世界单位缩放的实体集合。

```csharp
public DwfWhipDrawable[] DrawObjectsInRealWorldCoordinates { get; }
```

### 返回值

按真实世界单位缩放的实体集合，若资源不包含 'Units' 操作数，则为 'null' 值。

## 示例

检索按真实世界单位缩放的实体集合。

```csharp
string file = "ExampleFile.dwf";
DwfWhipDrawable[] result;
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        result = page.DrawObjectsInRealWorldCoordinates;
    }
}

foreach (DwfWhipDrawable s in result)
{
    Do something;
}
```

### 另请参阅

* class [DwfWhipDrawable](../../../aspose.cad.fileformats.dwf.whip.objects.drawable/dwfwhipdrawable/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

