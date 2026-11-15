---
title: "DracoImage.Height"
linktitle: "Высота"
articleTitle: "Высота"
second_title: "Aspose.CAD для .NET справка API"
description: "DracoImage свойство. Возвращает высоту изображения. Вычисляется как разница между максимальными и минимальными значениями координаты Y среди всех вершин. ..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.draco/dracoimage/height/"
product_version: "26.9"
---
## DracoImage.Height property

Получает высоту изображения.
Вычисляется как разница между максимальными и минимальными значениями координаты Y среди всех вершин.
Минимально допустимая высота — 1.

```csharp
public override int Height { get; }
```

### Property Value

Высота изображения.

## Примеры

Выводит высоту рисунка DRACO.

```csharp
using (DracoImage drcImage = (DracoImage)Image.Load(fileName))
{
    System.Console.WriteLine("The height of the image is {0}", drcImage.Height);
}
```

### См. также

* class [DracoImage](../)
* namespace [Aspose.CAD.FileFormats.Draco](../../../aspose.cad.fileformats.draco/)
* assembly [Aspose.CAD](../../../)

