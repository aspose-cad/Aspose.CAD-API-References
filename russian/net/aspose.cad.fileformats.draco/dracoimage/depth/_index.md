---
title: "DracoImage.Depth"
linktitle: "Глубина"
articleTitle: "Глубина"
second_title: "Aspose.CAD для .NET справка API"
description: "DracoImage свойство. Возвращает глубину изображения. Вычисляется как разница между максимальными и минимальными значениями координаты Z среди всех вершин. M..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.draco/dracoimage/depth/"
product_version: "26.9"
---
## DracoImage.Depth property

Возвращает глубину изображения.
Вычисляется как разница между максимальными и минимальными значениями координаты Z среди всех вершин.
Минимально допустимая глубина равна 0.

```csharp
public override int Depth { get; }
```

### Property Value

Глубина изображения.

## Примеры

Выводит глубину рисунка DRACO.

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The depth of the image is {0}", drcImage.Depth);
}
```

### См. также

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

