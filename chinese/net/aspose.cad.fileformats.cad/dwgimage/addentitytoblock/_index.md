---
title: "DwgImage.AddEntityToBlock"
linktitle: "AddEntityToBlock"
articleTitle: "AddEntityToBlock"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwgImage 方法。向指定块添加实体。"
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.cad/dwgimage/addentitytoblock/"
product_version: "26.9"
---
## DwgImage.AddEntityToBlock method

向指定块添加实体。

```csharp
public void AddEntityToBlock(string blockName, CadEntityBase entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| blockName | String | 块的名称。 |
| 实体 | CadEntityBase | 要添加的实体。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 *entity* 为 null，则抛出异常。 |
| ArgumentException | 如果块不存在，或是系统块，或该实体已关联到另一个块，则抛出异常。 |

### 另请参阅

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

