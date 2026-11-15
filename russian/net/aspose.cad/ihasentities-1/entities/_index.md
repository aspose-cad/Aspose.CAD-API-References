---
title: "IHasEntities<T>.Entities"
linktitle: "Entities"
articleTitle: "Entities"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство IHasEntities. Получает все объекты, существующие в чертеже. Может быть полезно для обхода их и проверки их свойств"
type: docs
weight: 20
url: "/net/aspose.cad/ihasentities-1/entities/"
product_version: "26.9"
---
## IHasEntities<T>.Entities property

Получает все объекты, существующие в чертеже.
Может быть полезно для их обхода и проверки их свойств

```csharp
public IEnumerable<T> Entities { get; }
```

### Property Value

Набор экземпляров сущностей

## Примеры

Получает набор сущностей из чертежа.

```csharp
using (IfcImage ifcImage = (IfcImage)Image.Load(fileName))
{
    var entities = ifcImage.Entities
}
```

### См. также

* interface [IHasEntities&lt;T&gt;](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

