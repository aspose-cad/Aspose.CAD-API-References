---
title: Size
second_title: Справочник по Aspose.CAD для .NET API
description: Получает размер изображения.
type: docs
weight: 60
url: /ru/net/aspose.cad/image/size/
---
## Image.Size property

Получает размер изображения.

```csharp
public Size Size { get; }
```

### Стоимость имущества

Размер изображения.

### Примеры

Обрабатывает рисунок, если он не пустой

```csharp
var fileName = @"C:\path\drawing.dwg";
using (Aspose.CAD.Image drawing = Aspose.CAD.Image.Load(fileName))
{
    if (!drawing.Size.IsEmpty)
    {
         // ..._ x000d_
    }
}
```

### Смотрите также

* struct [Size](../../size)
* class [Image](../../image)
* пространство имен [Aspose.CAD](../../image)
* сборка [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
