---
title: "StreamContainer.Seek"
linktitle: "Seek"
articleTitle: "Seek"
second_title: "Aspose.CAD for .NET API 参考"
description: "StreamContainer 方法。设置当前流中的位置。"
type: docs
weight: 120
url: "/net/aspose.cad/streamcontainer/seek/"
product_version: "26.9"
---
## StreamContainer.Seek method

设置当前流内的位置。

```csharp
public virtual long Seek(long offset, SeekOrigin origin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | Int64 | 相对于 *origin* 参数的字节偏移量。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| origin | SeekOrigin | 类型为 [`SeekOrigin`](../../seekorigin/) 的值，指示用于获取新位置的参考点。 |

### 返回值

当前流中的新位置。

### 另请参阅

* enum [SeekOrigin](../../seekorigin/)
* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

