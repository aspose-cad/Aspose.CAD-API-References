---
title: "DracoImage.Width"
linktitle: "Ширина"
articleTitle: "Ширина"
second_title: "Aspose.CAD для .NET справка API"
description: "DracoImage свойство. Возвращает ширину изображения. Вычисляется как разница между максимальными и минимальными значениями координаты X среди всех вершин. M..."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.draco/dracoimage/width/"
product_version: "26.9"
---
## DracoImage.Width property

Возвращает ширину изображения.
Вычисляется как разница между максимальными и минимальными значениями координаты X среди всех вершин.
Минимально допустимая ширина — 1.

```csharp
public override int Width { get; }
```

### Property Value

Ширина изображения.

## Примеры

Выводит ширину рисунка DRACO.

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The width of the image is {0}", drcImage.Width);
}
```

### См. также

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

