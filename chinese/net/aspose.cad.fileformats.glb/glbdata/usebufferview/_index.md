---
title: "GlbData.UseBufferView"
linktitle: "UseBufferView"
articleTitle: "UseBufferView"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。在 LogicalBufferViews 处创建或复用 BufferView 实例。"
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.glb/glbdata/usebufferview/"
product_version: "26.9"
---
## UseBufferView(ArraySegment&lt;byte&gt;, int, BufferMode?) {#usebufferview}

创建或复用一个 [`BufferView`](../../bufferview/) 实例
位于 [`LogicalBufferViews`](../logicalbufferviews/)。

```csharp
public BufferView UseBufferView(ArraySegment<byte> data, int byteStride = 0, 
    BufferMode? target = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | ArraySegment`1 | 要包装的数组范围。 |
| byteStride | Int32 | 对于跨距顶点缓冲区，它必须是 4 的倍数，否则为 0 |
| target | Nullable`1 | 硬件设备缓冲区的类型，或 null |

### 返回值

一个 [`BufferView`](../../bufferview/) 实例。

### 另请参阅

* class [BufferView](../../bufferview/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## UseBufferView(Buffer, int, int?, int, BufferMode?) {#usebufferview_1}

创建或复用一个 [`BufferView`](../../bufferview/) 实例
位于 [`LogicalBufferViews`](../logicalbufferviews/)。

```csharp
public BufferView UseBufferView(Buffer buffer, int byteOffset = 0, int? byteLength = default, 
    int byteStride = 0, BufferMode? target = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Buffer | 要包装的缓冲区。 |
| byteOffset | Int32 | 在 *buffer* 中第一个字节的零基索引 |
| byteLength | Nullable`1 | 在 *buffer* 中的元素数量 |
| byteStride | Int32 | 对于跨距顶点缓冲区，它必须是 4 的倍数，否则为 0 |
| target | Nullable`1 | 硬件设备缓冲区的类型，或 null |

### 返回值

一个 [`BufferView`](../../bufferview/) 实例。

### 另请参阅

* class [BufferView](../../bufferview/)
* class [Buffer](../../buffer/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## UseBufferView(byte[], int, int?, int, BufferMode?) {#usebufferview_2}

创建或复用一个 [`BufferView`](../../bufferview/) 实例
位于 [`LogicalBufferViews`](../logicalbufferviews/)。

```csharp
public BufferView UseBufferView(byte[] buffer, int byteOffset = 0, int? byteLength = default, 
    int byteStride = 0, BufferMode? target = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Byte[] | 要包装的数组。 |
| byteOffset | Int32 | 在 *buffer* 中第一个字节的零基索引 |
| byteLength | Nullable`1 | 在 *buffer* 中的元素数量 |
| byteStride | Int32 | 对于跨距顶点缓冲区，它必须是 4 的倍数，否则为 0 |
| target | Nullable`1 | 硬件设备缓冲区的类型，或 null |

### 返回值

一个 [`BufferView`](../../bufferview/) 实例。

### 另请参阅

* class [BufferView](../../bufferview/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

