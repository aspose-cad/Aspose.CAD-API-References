---
title: "DxfOptions.OriginPosition"
linktitle: "OriginPosition"
articleTitle: "OriginPosition"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство DxfOptions. Получает или задает позицию начала."
type: docs
weight: 90
url: "/net/aspose.cad.imageoptions/dxfoptions/originposition/"
product_version: "26.9"
---
## DxfOptions.OriginPosition property

Получает или задает исходную позицию.

```csharp
public Point3D OriginPosition { get; set; }
```

### Property Value

Позиция начала (начальная) элементов в файле
По умолчанию она установлена в (0,0,0)
Например
DxfOptions options = new DxfOptions();
options.OriginPosition = new Point3D(1000, 2000, 3000); //здесь координаты смещения
image.Save(filename + ".dxf", options);
Получившееся изображение будет иметь элементы, начинающиеся с координат, указанных в OriginPosition

### См. также

* class [Point3D](../../../aspose.cad.primitives/point3d/)
* class [DxfOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

