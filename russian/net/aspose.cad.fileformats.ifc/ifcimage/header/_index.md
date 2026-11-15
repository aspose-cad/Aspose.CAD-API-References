---
title: "IfcImage.Header"
linktitle: "Заголовок"
articleTitle: "Заголовок"
second_title: "Aspose.CAD для .NET справка API"
description: "IfcImage свойство. Получает заголовок."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.ifc/ifcimage/header/"
product_version: "26.9"
---
## IfcImage.Header property

Получает заголовок.

```csharp
public IfcHeader Header { get; }
```

### Property Value

Заголовок.

## Примеры

Получает заголовок из изображения.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var header = ifcImage.Header        
}
```

### См. также

* class [IfcHeader](../../../aspose.cad.fileformats.ifc.header/ifcheader/)
* class [IfcImage](../)
* namespace [Aspose.CAD.FileFormats.Ifc](../../../aspose.cad.fileformats.ifc/)
* assembly [Aspose.CAD](../../../)

