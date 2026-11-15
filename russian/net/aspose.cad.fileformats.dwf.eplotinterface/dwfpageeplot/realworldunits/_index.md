---
title: "DwfPageEPlot.RealWorldUnits"
linktitle: "RealWorldUnits"
articleTitle: "RealWorldUnits"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство DwfPageEPlot. Возвращает единицы масштаба реального мира. Строковый ярлык, указывающий единицу измерения, которую представляет масштаб при измерении одной логической..."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldunits/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldUnits property

Возвращает единицы масштаба реального мира.
Строковый ярлык, указывающий единицу измерения, которую представляет масштаб при измерении одной логической координаты.

```csharp
public string RealWorldUnits { get; }
```

### Возвращаемое значение

Единицы масштаба реального мира или пустая строка, если имя единицы не указано или ресурс не содержит операнд 'Units'.

## Примеры

Возвращает единицы масштаба реального мира.

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

### См. также

* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

