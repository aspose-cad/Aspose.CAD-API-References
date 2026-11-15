---
title: "Accessor.SetVertexData"
linktitle: "SetVertexData"
articleTitle: "SetVertexData"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Accessor."
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.glb/accessor/setvertexdata/"
product_version: "26.9"
---
## SetVertexData(MemoryAccessor) {#setvertexdata}



```csharp
public void SetVertexData(MemoryAccessor src)
```

### См. также

* class [MemoryAccessor](../../../aspose.cad.fileformats.glb.memory/memoryaccessor/)
* class [Accessor](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## SetVertexData(BufferView, int, int, DimensionType, EncodingType, bool) {#setvertexdata_1}

Связывает этот [`Accessor`](../) с [`BufferView`](../../bufferview/)

```csharp
public void SetVertexData(BufferView buffer, int bufferByteOffset, int itemCount, 
    DimensionType dimensions = DimensionType.VEC3, EncodingType encoding = EncodingType.FLOAT, 
    bool normalized = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | BufferView | Исходный источник [`BufferView`](../../bufferview/). |
| bufferByteOffset | Int32 | Начальное смещение байта внутри *buffer*. |
| itemCount | Int32 | Количество элементов в accessor. |
| dimensions | DimensionType | Тип элемента [`DimensionType`](../../dimensiontype/). |
| encoding | EncodingType | Кодировка элемента [`EncodingType`](../../encodingtype/). |
| normalized | Boolean | Режим нормализации элемента. |

### См. также

* class [BufferView](../../bufferview/)
* enum [DimensionType](../../dimensiontype/)
* enum [EncodingType](../../encodingtype/)
* class [Accessor](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

