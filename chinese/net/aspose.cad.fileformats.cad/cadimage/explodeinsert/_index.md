---
title: "CadImage.ExplodeInsert"
linktitle: "ExplodeInsert"
articleTitle: "ExplodeInsert"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadImage 方法。将插入拆解并将其包含的实体放置在该插入的位置，同时返回这些实体。"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.cad/cadimage/explodeinsert/"
product_version: "26.9"
---
## CadImage.ExplodeInsert method

展开插入对象并将其包含的实体放置在该插入位置，同时返回这些实体

```csharp
public CadEntityBase[] ExplodeInsert(string objectID, bool recurse)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectID | String | 插入句柄或在旧格式中的编号，[`Id`](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) |
| 递归 | Boolean | 是否递归地拆分子插入 |

### 返回值

从已拆分的插入中获取的所有实体，如果未找到或无法拆分则为 null

### 另请参阅

* class [CadEntityBase](../../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/)
* class [CadImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

