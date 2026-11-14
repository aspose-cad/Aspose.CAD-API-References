---
title: "DataStreamSupporter 类"
linktitle: "DataStreamSupporter"
articleTitle: "DataStreamSupporter"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.DataStreamSupporter 类。数据流容器。"
type: docs
weight: 200
url: "/net/aspose.cad/datastreamsupporter/"
keywords: "DataStreamSupporter, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DataStreamSupporter class

数据流容器。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| abstract [IsCached](../../aspose.cad/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.cad/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](./datastreamcontainer/) 加载额外的数据。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/#save)() | 将对象的数据保存到当前的 `DataStreamSupporter`。 |
| [Save](../../aspose.cad/datastreamsupporter/save/#save_1)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/#save_2)(string) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/#save_3)(string, bool) | 将对象的数据保存到指定的文件位置。 |

### 另请参阅

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

