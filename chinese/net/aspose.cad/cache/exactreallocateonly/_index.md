---
title: ExactReallocateOnly
second_title: Aspose.CAD for .NET API 参考
description: 获取或设置一个值指示重新分配是否应该准确如果重新分配不准确则性能应该更高
type: docs
weight: 50
url: /zh/net/aspose.cad/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

获取或设置一个值，指示重新分配是否应该准确。如果重新分配不准确，则性能应该更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### 适当的价值

` true` 如果重新分配是准确的；否则，` false` 。

### 评论

精确的重新分配将执行额外内存的重新分配，直到达到指定的上限。 在重新分配期间超过内存上限时，如果可能，缓存数据将被复制到磁盘。 在重新分配期间超过磁盘内存上限时，将引发相应的异常。 如果关闭此选项，性能应该会更高，因为如果可能，将不会执行额外的复制， 但是这也可能导致超出为内存或磁盘指定的上限。

### 也可以看看

* class [Cache](../../cache)
* 命名空间 [Aspose.CAD](../../cache)
* 部件 [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->