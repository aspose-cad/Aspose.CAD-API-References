---
title: "InstanceBuilder.Name"
linktitle: "名称"
articleTitle: "名称"
second_title: "Aspose.CAD for .NET API 参考"
description: "InstanceBuilder 属性。获取此对象的显示文本名称，或 null。⚠️ 请勿将其用作对象 ID ⚠️ 请参阅备注。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb.scenes/instancebuilder/name/"
product_version: "26.9"
---
## InstanceBuilder.Name property

获取此对象的显示文本名称，若无则为 null。
 

**⚠️ DO NOT USE AS AN OBJECT ID ⚠️** see remarks.

```csharp
public string Name { get; }
```

## 备注

glTF 未定义任何对象名称规则。

这意味着名称可以为 null 或不唯一。

因此，名称只能用于对象名称显示，不能用于其他用途。

如果需要通过某个 ID 引用对象，请改用查找表。

### 另请参阅

* class [InstanceBuilder](../)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../../)

