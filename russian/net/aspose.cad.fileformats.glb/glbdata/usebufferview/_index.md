---
title: "GlbData.UseBufferView"
linktitle: "UseBufferView"
articleTitle: "UseBufferView"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Создаёт или переиспользует экземпляр BufferView в LogicalBufferViews."
type: docs
weight: 110
url: "/net/aspose.cad.fileformats.glb/glbdata/usebufferview/"
product_version: "26.9"
---
## UseBufferView(ArraySegment&lt;byte&gt;, int, BufferMode?) {#usebufferview}

Создаёт или переиспользует экземпляр [`BufferView`](../../bufferview/)
в [`LogicalBufferViews`](../logicalbufferviews/).

```csharp
public BufferView UseBufferView(ArraySegment<byte> data, int byteStride = 0, 
    BufferMode? target = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | ArraySegment`1 | Диапазон массива для обёртывания. |
| byteStride | Int32 | Для буферов вершин с шагом, должно быть значение, кратное 4, иначе 0. |
| target | Nullable`1 | Тип аппаратного буфера устройства, или null. |

### Возвращаемое значение

Экземпляр [`BufferView`](../../bufferview/).

### См. также

* class [BufferView](../../bufferview/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## UseBufferView(Buffer, int, int?, int, BufferMode?) {#usebufferview_1}

Создаёт или переиспользует экземпляр [`BufferView`](../../bufferview/)
в [`LogicalBufferViews`](../logicalbufferviews/).

```csharp
public BufferView UseBufferView(Buffer buffer, int byteOffset = 0, int? byteLength = default, 
    int byteStride = 0, BufferMode? target = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Buffer | Буфер для обёртывания. |
| byteOffset | Int32 | Нулевой индекс первого Byte в *buffer* |
| byteLength | Nullable`1 | Количество элементов в *buffer* |
| byteStride | Int32 | Для буферов вершин с шагом, должно быть значение, кратное 4, иначе 0. |
| target | Nullable`1 | Тип аппаратного буфера устройства, или null. |

### Возвращаемое значение

Экземпляр [`BufferView`](../../bufferview/).

### См. также

* class [BufferView](../../bufferview/)
* class [Buffer](../../buffer/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## UseBufferView(byte[], int, int?, int, BufferMode?) {#usebufferview_2}

Создаёт или переиспользует экземпляр [`BufferView`](../../bufferview/)
в [`LogicalBufferViews`](../logicalbufferviews/).

```csharp
public BufferView UseBufferView(byte[] buffer, int byteOffset = 0, int? byteLength = default, 
    int byteStride = 0, BufferMode? target = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Byte[] | Массив для обертывания. |
| byteOffset | Int32 | Нулевой индекс первого Byte в *buffer* |
| byteLength | Nullable`1 | Количество элементов в *buffer* |
| byteStride | Int32 | Для буферов вершин с шагом, должно быть значение, кратное 4, иначе 0. |
| target | Nullable`1 | Тип аппаратного буфера устройства, или null. |

### Возвращаемое значение

Экземпляр [`BufferView`](../../bufferview/).

### См. также

* class [BufferView](../../bufferview/)
* enum [BufferMode](../../buffermode/)
* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

