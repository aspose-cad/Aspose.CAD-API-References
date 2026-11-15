---
title: "DwgImage.AddEntityToBlock"
linktitle: "AddEntityToBlock"
articleTitle: "AddEntityToBlock"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод DwgImage. Добавляет сущность в указанный блок."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.cad/dwgimage/addentitytoblock/"
product_version: "26.9"
---
## DwgImage.AddEntityToBlock method

Добавляет объект в указанный блок.

```csharp
public void AddEntityToBlock(string blockName, CadEntityBase entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| blockName | String | Имя блока. |
| сущность | CadEntityBase | Сущность для добавления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если *entity* равно null. |
| ArgumentException | Выбрасывается, если блок не существует, является системным блоком или сущность уже связана с другим блоком. |

### См. также

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

