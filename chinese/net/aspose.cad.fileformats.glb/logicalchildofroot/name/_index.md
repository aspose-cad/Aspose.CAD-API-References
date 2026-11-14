---
title: "LogicalChildOfRoot.Name"
linktitle: "名称"
articleTitle: "名称"
second_title: "Aspose.CAD for .NET API 参考"
description: "LogicalChildOfRoot 属性。获取或设置显示文本名称，或为 null。⚠️ 请勿用作对象 ID ⚠️ 请参阅备注。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/logicalchildofroot/name/"
product_version: "26.9"
---
## LogicalChildOfRoot.Name property

获取或设置显示文本名称，或 null。
 

**⚠️ DO NOT USE AS AN OBJECT ID ⚠️** see remarks.

```csharp
public string Name { get; set; }
```

## 备注

glTF 未定义任何对象名称规则。

这意味着名称可以为 null 或不唯一。

因此不要将 [`Name`](../name/) 用于对象名称显示以外的任何用途。

如果需要通过某个 ID 引用对象，请改用查找表。

### 另请参阅

* class [LogicalChildOfRoot](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

