---
title: "DwfPageEPlot.RealWorldUnits"
linktitle: "RealWorldUnits"
articleTitle: "RealWorldUnits"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwfPageEPlot 属性。获取真实世界的比例单位。字符串标签，指示在测量单个逻辑...时比例所代表的计量单位。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldunits/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldUnits property

获取真实世界的比例单位。
字符串标签，指示在测量单个逻辑坐标时比例所代表的计量单位。

```csharp
public string RealWorldUnits { get; }
```

### 返回值

真实世界的比例单位，若未指定单位名称或资源不包含 'Units' 操作数，则为空字符串。

## 示例

获取真实世界的比例单位。

```csharp
string file = "ExampleFile.dwf";
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage)Image.Load(inStream))
{
    DwfPageEPlot page = image.Pages[0] as DwfPageEPlot;
    if (page != null)
    {
        string unitsName =page.RealWorldUnits;
    }
}
```

### 另请参阅

* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

