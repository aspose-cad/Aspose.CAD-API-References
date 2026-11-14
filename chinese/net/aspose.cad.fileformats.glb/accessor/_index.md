---
title: "Accessor 类"
linktitle: "Accessor"
articleTitle: "Accessor"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Accessor 类。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb/accessor/"
keywords: "Accessor, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Accessor class



```csharp
public sealed class Accessor : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ByteLength](../../aspose.cad.fileformats.glb/accessor/bytelength/) { get; } | 获取字节数，从 [`ByteOffset`](./byteoffset/) 开始，由此 `Accessor` 使用。 |
| [ByteOffset](../../aspose.cad.fileformats.glb/accessor/byteoffset/) { get; } | 获取 [`SourceBufferView`](./sourcebufferview/) 中的起始字节偏移。 |
| [Count](../../aspose.cad.fileformats.glb/accessor/count/) { get; } | 获取项的数量。 |
| [Dimensions](../../aspose.cad.fileformats.glb/accessor/dimensions/) { get; } | 获取项的 [`DimensionType`](../dimensiontype/)。 |
| [Encoding](../../aspose.cad.fileformats.glb/accessor/encoding/) { get; } | 获取项的 [`EncodingType`](../encodingtype/)。 |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [Format](../../aspose.cad.fileformats.glb/accessor/format/) { get; } |  |
| [IsSparse](../../aspose.cad.fileformats.glb/accessor/issparse/) { get; } | 获取一个值，指示此 `Accessor` 是否具有稀疏结构。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Normalized](../../aspose.cad.fileformats.glb/accessor/normalized/) { get; } | 获取一个值，指示项的值是否已归一化。 |
| [SourceBufferView](../../aspose.cad.fileformats.glb/accessor/sourcebufferview/) { get; } | 获取包含项的已编码字节数组的 [`BufferView`](../bufferview/) 缓冲区。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AsColorArray](../../aspose.cad.fileformats.glb/accessor/ascolorarray/)(float) |  |
| [AsIndicesArray](../../aspose.cad.fileformats.glb/accessor/asindicesarray/)() |  |
| [AsMatrix2x2Array](../../aspose.cad.fileformats.glb/accessor/asmatrix2x2array/)() |  |
| [AsMatrix3x3Array](../../aspose.cad.fileformats.glb/accessor/asmatrix3x3array/)() |  |
| [AsMatrix4x3Array](../../aspose.cad.fileformats.glb/accessor/asmatrix4x3array/)() |  |
| [AsMatrix4x4Array](../../aspose.cad.fileformats.glb/accessor/asmatrix4x4array/)() |  |
| [AsMultiArray](../../aspose.cad.fileformats.glb/accessor/asmultiarray/)(int) |  |
| [AsQuaternionArray](../../aspose.cad.fileformats.glb/accessor/asquaternionarray/)() |  |
| [AsScalarArray](../../aspose.cad.fileformats.glb/accessor/asscalararray/)() |  |
| [AsVector2Array](../../aspose.cad.fileformats.glb/accessor/asvector2array/)() |  |
| [AsVector3Array](../../aspose.cad.fileformats.glb/accessor/asvector3array/)() |  |
| [AsVector4Array](../../aspose.cad.fileformats.glb/accessor/asvector4array/)() |  |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetData](../../aspose.cad.fileformats.glb/accessor/setdata/)(BufferView, int, int, DimensionType, EncodingType, bool?) | 将此 `Accessor` 与 [`BufferView`](../bufferview/) 关联。 |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetIndexData](../../aspose.cad.fileformats.glb/accessor/setindexdata/#setindexdata)(MemoryAccessor) |  |
| [SetIndexData](../../aspose.cad.fileformats.glb/accessor/setindexdata/#setindexdata_1)(BufferView, int, int, IndexEncodingType) | 将此 `Accessor` 与 [`BufferView`](../bufferview/) 关联。 |
| [SetVertexData](../../aspose.cad.fileformats.glb/accessor/setvertexdata/#setvertexdata)(MemoryAccessor) |  |
| [SetVertexData](../../aspose.cad.fileformats.glb/accessor/setvertexdata/#setvertexdata_1)(BufferView, int, int, DimensionType, EncodingType, bool) | 将此 `Accessor` 与 [`BufferView`](../bufferview/) 关联。 |
| [TryGetVertexBytes](../../aspose.cad.fileformats.glb/accessor/trygetvertexbytes/)(int) |  |
| [UpdateBounds](../../aspose.cad.fileformats.glb/accessor/updatebounds/)() |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

