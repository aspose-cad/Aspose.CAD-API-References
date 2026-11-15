---
title: "Accessor Класс"
linktitle: "Accessor"
articleTitle: "Accessor"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Accessor класс."
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

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteLength](../../aspose.cad.fileformats.glb/accessor/bytelength/) { get; } | Получает количество байтов, начиная с [`ByteOffset`](./byteoffset/), используемых этим `Accessor` |
| [ByteOffset](../../aspose.cad.fileformats.glb/accessor/byteoffset/) { get; } | Получает начальное смещение байта внутри [`SourceBufferView`](./sourcebufferview/). |
| [Count](../../aspose.cad.fileformats.glb/accessor/count/) { get; } | Получает количество элементов. |
| [Dimensions](../../aspose.cad.fileformats.glb/accessor/dimensions/) { get; } | Получает [`DimensionType`](../dimensiontype/) элемента. |
| [Encoding](../../aspose.cad.fileformats.glb/accessor/encoding/) { get; } | Получает [`EncodingType`](../encodingtype/) элемента. |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [Format](../../aspose.cad.fileformats.glb/accessor/format/) { get; } |  |
| [IsSparse](../../aspose.cad.fileformats.glb/accessor/issparse/) { get; } | Получает значение, указывающее, имеет ли этот `Accessor` разреженную структуру. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Normalized](../../aspose.cad.fileformats.glb/accessor/normalized/) { get; } | Получает значение, указывающее, нормализованы ли значения элементов. |
| [SourceBufferView](../../aspose.cad.fileformats.glb/accessor/sourcebufferview/) { get; } | Получает буфер [`BufferView`](../bufferview/), содержащий элементы в виде закодированного массива байтов. |

## Методы

| Имя | Описание |
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
| [SetData](../../aspose.cad.fileformats.glb/accessor/setdata/)(BufferView, int, int, DimensionType, EncodingType, bool?) | Связывает этот `Accessor` с [`BufferView`](../bufferview/) |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetIndexData](../../aspose.cad.fileformats.glb/accessor/setindexdata/#setindexdata)(MemoryAccessor) |  |
| [SetIndexData](../../aspose.cad.fileformats.glb/accessor/setindexdata/#setindexdata_1)(BufferView, int, int, IndexEncodingType) | Связывает этот `Accessor` с [`BufferView`](../bufferview/) |
| [SetVertexData](../../aspose.cad.fileformats.glb/accessor/setvertexdata/#setvertexdata)(MemoryAccessor) |  |
| [SetVertexData](../../aspose.cad.fileformats.glb/accessor/setvertexdata/#setvertexdata_1)(BufferView, int, int, DimensionType, EncodingType, bool) | Связывает этот `Accessor` с [`BufferView`](../bufferview/) |
| [TryGetVertexBytes](../../aspose.cad.fileformats.glb/accessor/trygetvertexbytes/)(int) |  |
| [UpdateBounds](../../aspose.cad.fileformats.glb/accessor/updatebounds/)() |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

