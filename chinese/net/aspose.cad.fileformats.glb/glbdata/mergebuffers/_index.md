---
title: "GlbData.MergeBuffers"
linktitle: "MergeBuffers"
articleTitle: "MergeBuffers"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。将所有 LogicalBuffers 实例合并为一个大的实例。"
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.glb/glbdata/mergebuffers/"
product_version: "26.9"
---
## MergeBuffers() {#mergebuffers}

将所有 [`LogicalBuffers`](../logicalbuffers/) 实例合并为一个大的实例。

```csharp
public void MergeBuffers()
```

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | .Net 数组的上限为 2Gb，因此这是缓冲区通常能够增长的最大尺寸，尝试合并总和超过 2Gb 的缓冲区将抛出此异常。 |

## 备注

在合并缓冲区时，它还会调整 BufferView 的偏移量，以确保它们指向的数据保持不变。
 
 

如果需要在二进制中包含图像，请调用 [`MergeImages`](../mergeimages/)
在调用 [`MergeBuffers`](../mergebuffers/) 之前。

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## MergeBuffers(int) {#mergebuffers_1}

将所有 [`LogicalBuffers`](../logicalbuffers/) 实例合并为大小为 *maxSize* 的缓冲区。

```csharp
public void MergeBuffers(int maxSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxSize | Int32 | 每个缓冲区的最大大小。请注意，如果单个 BufferView 大于 *maxSize*，则该缓冲区也会更大。 |

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

