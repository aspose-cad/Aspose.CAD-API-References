---
title: "DwfPageEPlot.RealWorldMinPoint"
linktitle: "RealWorldMinPoint"
articleTitle: "RealWorldMinPoint"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство DwfPageEPlot. Возвращает минимальное значение координат сущностей, масштабированное в реальные единицы измерения."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/realworldminpoint/"
product_version: "26.9"
---
## DwfPageEPlot.RealWorldMinPoint property

Получает минимальное значение координат сущностей, масштабированных до реальных единиц измерения.

```csharp
public Cad3DPoint RealWorldMinPoint { get; }
```

### Возвращаемое значение

Минимальное значение координат сущностей, масштабированное в реальные единицы измерения, или значение 'null', если ресурс не содержит операнд 'Units'.

## Примеры

Возвращает ширину и высоту изображения, масштабированные в единицы реального мира.

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

### См. также

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

