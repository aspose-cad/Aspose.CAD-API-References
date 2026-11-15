---
title: "DwfPageEPlot.DrawObjectsInRealWorldCoordinates"
linktitle: "DrawObjectsInRealWorldCoordinates"
articleTitle: "DrawObjectsInRealWorldCoordinates"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство DwfPageEPlot. Возвращает коллекцию сущностей, масштабированных в единицы реального мира, из ресурса с ролью '2d streaming graphics'."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.dwf.eplotinterface/dwfpageeplot/drawobjectsinrealworldcoordinates/"
product_version: "26.9"
---
## DwfPageEPlot.DrawObjectsInRealWorldCoordinates property

Получает коллекцию сущностей, масштабированных до реальных единиц измерения, из ресурса с ролью '2d streaming graphics'.

```csharp
public DwfWhipDrawable[] DrawObjectsInRealWorldCoordinates { get; }
```

### Возвращаемое значение

Коллекция сущностей, масштабированных в единицы реального мира, или значение 'null', если ресурс не содержит операнд 'Units'.

## Примеры

Получает коллекцию сущностей, масштабированных в единицы реального мира.

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

### См. также

* class [DwfWhipDrawable](../../../aspose.cad.fileformats.dwf.whip.objects.drawable/dwfwhipdrawable/)
* class [DwfPageEPlot](../)
* namespace [Aspose.CAD.FileFormats.Dwf.EPlotInterface](../../../aspose.cad.fileformats.dwf.eplotinterface/)
* assembly [Aspose.CAD](../../../)

