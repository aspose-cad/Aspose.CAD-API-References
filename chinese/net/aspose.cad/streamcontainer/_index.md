---
title: "StreamContainer 类"
linktitle: "StreamContainer"
articleTitle: "StreamContainer"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.StreamContainer 类。表示包含流并提供流处理例程的流容器。"
type: docs
weight: 860
url: "/net/aspose.cad/streamcontainer/"
keywords: "StreamContainer, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## StreamContainer class

表示包含流并提供流处理例程的流容器。

```csharp
public class StreamContainer : DisposableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | 初始化 `StreamContainer` 类的新实例。 |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | 初始化 `StreamContainer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.cad/streamcontainer/canread/) { get; } | 获取指示流是否支持读取的值。 |
| virtual [CanSeek](../../aspose.cad/streamcontainer/canseek/) { get; } | 获取指示流是否支持定位的值。 |
| virtual [CanWrite](../../aspose.cad/streamcontainer/canwrite/) { get; } | 获取指示流是否支持写入的值。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [IsStreamDisposedOnClose](../../aspose.cad/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否已释放。 |
| virtual [Length](../../aspose.cad/streamcontainer/length/) { get; set; } | 获取或设置流的字节长度。此值比通过 StreamContainer 构造函数传入的起始流位置的 Length 小。 |
| virtual [Position](../../aspose.cad/streamcontainer/position/) { get; set; } | 获取或设置流内的当前位置。此值表示相对于通过 StreamContainer 构造函数传入的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.cad/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.cad/streamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Flush](../../aspose.cad/streamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| virtual [Read](../../aspose.cad/streamcontainer/read/#read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.cad/streamcontainer/read/#read_1)(byte[], int, int) | 从当前流读取一系列字节，并将流内的位置前移读取的字节数。 |
| virtual [ReadByte](../../aspose.cad/streamcontainer/readbyte/)() | 从流中读取一个字节，并将流内的位置前移一个字节；如果已到达流的末尾，则返回 -1。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](./readwritebytescount/) 和流的 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_1)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](./readwritebytescount/) 和流的 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_2)(Stream, int) | 将整个流的数据保存（复制）到指定的流。使用流的 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_3)(string, int) | 将流的数据保存（复制）到指定的流。使用流的 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_4)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_5)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Seek](../../aspose.cad/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流内的位置。 |
| virtual [SeekBegin](../../aspose.cad/streamcontainer/seekbegin/)() | 将流位置设置为流的起始位置。此值表示相对于通过 StreamContainer 构造函数传入的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.cad/streamcontainer/tobytes/#tobytes)() | 将流数据转换为 Byte 数组。 |
| virtual [ToBytes](../../aspose.cad/streamcontainer/tobytes/#tobytes_1)(long, long) | 将流数据转换为 Byte 数组。 |
| virtual [Write](../../aspose.cad/streamcontainer/write/#write)(byte[]) | 将所有指定的字节写入流。 |
| virtual [Write](../../aspose.cad/streamcontainer/write/#write_1)(byte[], int, int) | 将一系列字节写入当前流，并将此流内的当前位置前移写入的字节数。 |
| virtual [WriteByte](../../aspose.cad/streamcontainer/writebyte/)(byte) | 将一个字节写入流的当前位址，并将流内的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.cad/streamcontainer/writeto/#writeto)(StreamContainer) | 将包含的数据复制到另一个 `StreamContainer`。 |
| virtual [WriteTo](../../aspose.cad/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | 将包含的数据复制到另一个 `StreamContainer`。 |
| [explicit operator](../../aspose.cad/streamcontainer/op_explicit/) | 执行从 `StreamContainer` 到 Stream 的显式转换。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.cad/streamcontainer/readwritebytescount/) | 在顺序读取时指定读取和写入的字节计数。 |

### 另请参阅

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

