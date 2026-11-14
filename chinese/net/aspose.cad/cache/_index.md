---
title: "Cache 类"
linktitle: "Cache"
articleTitle: "Cache"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Cache 类。包含缓存设置。"
type: docs
weight: 40
url: "/net/aspose.cad/cache/"
keywords: "Cache, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Cache class

包含缓存设置。

```csharp
public static class Cache
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.cad/cache/allocateddiskbytescount/) { get; } | 获取已分配的磁盘字节计数。 |
| static [AllocatedMemoryBytesCount](../../aspose.cad/cache/allocatedmemorybytescount/) { get; } | 获取已分配的内存字节计数。 |
| static [CacheFolder](../../aspose.cad/cache/cachefolder/) { get; set; } | 获取或设置缓存文件夹。 |
| static [CacheType](../../aspose.cad/cache/cachetype/) { get; set; } | 获取或设置使用的缓存方案。 |
| static [ExactReallocateOnly](../../aspose.cad/cache/exactreallocateonly/) { get; set; } | 获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。 |
| static [MaxDiskSpaceForCache](../../aspose.cad/cache/maxdiskspaceforcache/) { get; set; } | 获取或设置缓存的最大可用磁盘空间。指定的值为兆字节数。 |
| static [MaxMemoryForCache](../../aspose.cad/cache/maxmemoryforcache/) { get; set; } | 获取或设置缓存在内存中的最大可用内存。指定的值为兆字节数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [SetDefaults](../../aspose.cad/cache/setdefaults/)() | 将 `Cache` 设置恢复为默认值。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [Reallocated](../../aspose.cad/cache/reallocated/) | 在执行重新分配时触发 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

