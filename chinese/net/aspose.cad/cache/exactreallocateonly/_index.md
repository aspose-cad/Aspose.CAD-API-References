---
title: "Cache.ExactReallocateOnly"
linktitle: "ExactReallocateOnly"
articleTitle: "ExactReallocateOnly"
second_title: "Aspose.CAD for .NET API 参考"
description: "Cache 属性。获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。"
type: docs
weight: 20
url: "/net/aspose.cad/cache/exactreallocateonly/"
product_version: "26.9"
---
## Cache.ExactReallocateOnly property

获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` 如果重新分配是精确的；否则为 `false`。

## 备注

精确的重新分配将仅在指定的上限范围内进行额外内存的重新分配。
在重新分配期间传递内存上限时，如果可能，缓存数据将被复制到磁盘。
在重新分配期间传递磁盘内存的上限时，会抛出相应的异常。
如果关闭此选项，性能应该会更高，因为在可能的情况下不会执行额外的复制，
然而，这可能也会导致超出为内存或磁盘指定的上限。

### 另请参阅

* class [Cache](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

