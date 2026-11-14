---
title: "DwgImage.InsertBlock"
linktitle: "InsertBlock"
articleTitle: "InsertBlock"
second_title: "Aspose.CAD for .NET API 参考"
description: "DwgImage 方法。在指定点将块插入绘图中。"
type: docs
weight: 60
url: "/net/aspose.cad.fileformats.cad/dwgimage/insertblock/"
product_version: "26.9"
---
## DwgImage.InsertBlock method

在指定点处向图形插入块。

```csharp
public void InsertBlock(string blockName, params Cad3DPoint[] insertPoints)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| blockName | String | 要插入的块的名称。 |
| insertPoints | Cad3DPoint[] | 块的插入点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果块不存在，或是系统块，则抛出异常 |

### 另请参阅

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

