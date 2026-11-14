---
title: "Accessor.SetData"
linktitle: "SetData"
articleTitle: "SetData"
second_title: "Aspose.CAD for .NET API 参考"
description: "Accessor 方法。将此 Accessor 与 BufferView 关联。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/accessor/setdata/"
product_version: "26.9"
---
## Accessor.SetData method

将此 [`Accessor`](../) 与 [`BufferView`](../../bufferview/) 关联。

```csharp
public void SetData(BufferView buffer, int bufferByteOffset, int itemCount, 
    DimensionType dimensions, EncodingType encoding, bool? normalized)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | BufferView | 此 [`BufferView`](../../bufferview/) 源。 |
| bufferByteOffset | Int32 | 在 *buffer* 中的起始字节偏移。 |
| itemCount | Int32 | 访问器中项目的数量。 |
| dimensions | DimensionType | [`DimensionType`](../../dimensiontype/) 项目的类型。 |
| encoding | EncodingType | [`EncodingType`](../../encodingtype/) 项目的编码。 |
| normalized | Nullable`1 | 项目的归一化模式。 |

### 另请参阅

* class [BufferView](../../bufferview/)
* enum [DimensionType](../../dimensiontype/)
* enum [EncodingType](../../encodingtype/)
* class [Accessor](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

