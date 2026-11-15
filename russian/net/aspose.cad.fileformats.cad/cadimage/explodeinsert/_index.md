---
title: "CadImage.ExplodeInsert"
linktitle: "ExplodeInsert"
articleTitle: "ExplodeInsert"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод CadImage. Разрушает вставку и помещает содержащиеся в ней сущности вместо этой вставки, также возвращая эти сущности."
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.cad/cadimage/explodeinsert/"
product_version: "26.9"
---
## CadImage.ExplodeInsert method

Разворачивает вставку и размещает содержащиеся в ней объекты вместо этой вставки, также возвращая эти объекты

```csharp
public CadEntityBase[] ExplodeInsert(string objectID, bool recurse)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| objectID | String | Идентификатор вставки или, в более старых форматах, номер, [`Id`](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) |
| рекурсивно | Boolean | Нужно ли рекурсивно разрушать дочерние вставки |

### Возвращаемое значение

Все сущности из разрушенной вставки, null если не найдено или не подлежит разрушению

### См. также

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [CadImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

