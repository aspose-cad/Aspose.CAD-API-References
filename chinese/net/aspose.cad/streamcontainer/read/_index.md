---
title: "StreamContainer.Read"
linktitle: "Read"
articleTitle: "Read"
second_title: "Aspose.CAD for .NET API 参考"
description: "StreamContainer 方法。读取字节以填充指定的字节缓冲区。"
type: docs
weight: 70
url: "/net/aspose.cad/streamcontainer/read/"
product_version: "26.9"
---
## Read(byte[]) {#read}

读取字节以填充指定的字节缓冲区。

```csharp
public virtual int Read(byte[] bytes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字节 | Byte[] | 要填充的字节。 |

### 返回值

读取的字节数。如果流中的字节不足，此值可能小于缓冲区中的字节数。

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Read(byte[], int, int) {#read_1}

从当前流读取一系列字节，并将流内的位置前移读取的字节数。

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Byte[] | 字节数组。当此方法返回时，缓冲区包含指定的字节数组，其中 *offset* 到 (*offset* + *count* - 1) 之间的值已被从当前源读取的字节替换。 |
| offset | Int32 | 在 *buffer* 中的基于零的字节偏移量，指示从何处开始存储从当前流读取的数据。 |
| 计数 | Int32 | 从当前流读取的最大字节数。 |

### 返回值

读取到缓冲区的字节总数。如果当前可用的字节不足以满足请求的字节数，则该值可能小于请求的字节数；如果已到达流的末尾，则为零 (0)。

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

