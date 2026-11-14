---
title: "StreamContainer.Save"
linktitle: "保存"
articleTitle: "保存"
second_title: "Aspose.CAD for .NET API 参考"
description: "StreamContainer 方法。将流的数据保存（复制）到指定的流。使用默认缓冲区大小 ReadWriteBytesCount 和流的 Length 值。"
type: docs
weight: 150
url: "/net/aspose.cad/streamcontainer/save/"
product_version: "26.9"
---
## Save(Stream) {#save}

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../readwritebytescount/) 和流 [`Length`](../length/) 值。

```csharp
public virtual void Save(Stream destinationStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(string) {#save_1}

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../readwritebytescount/) 和流 [`Length`](../length/) 值。

```csharp
public virtual void Save(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(Stream, int) {#save_2}

将所有流的数据保存（复制）到指定的流。使用流 [`Length`](../length/) 值。

```csharp
public virtual void Save(Stream destinationStream, int bufferSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |
| bufferSize | Int32 | 缓冲区。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(string, int) {#save_3}

将流的数据保存（复制）到指定的流。使用流 [`Length`](../length/) 值。

```csharp
public virtual void Save(string filePath, int bufferSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 值。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(Stream, int, long) {#save_4}

将流的数据保存（复制）到指定的流。

```csharp
public virtual void Save(Stream destinationStream, int bufferSize, long length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 值。 |
| length | Int64 | 要复制的流数据长度。默认长度设置为 [`Length`](../length/) 值。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(string, int, long) {#save_5}

将流的数据保存（复制）到指定的流。

```csharp
public virtual void Save(string filePath, int bufferSize, long length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 值。 |
| length | Int64 | 要复制的流数据长度。默认长度设置为 [`Length`](../length/) 值。 |

### 另请参阅

* class [StreamContainer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

