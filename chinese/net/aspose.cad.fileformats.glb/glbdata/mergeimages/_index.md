---
title: "GlbData.MergeImages"
linktitle: "MergeImages"
articleTitle: "MergeImages"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。将所有 LogicalImages 内容转移到 BufferView 实例中"
type: docs
weight: 180
url: "/net/aspose.cad.fileformats.glb/glbdata/mergeimages/"
product_version: "26.9"
---
## GlbData.MergeImages method

将所有 [`LogicalImages`](../logicalimages/) 内容转移到 [`BufferView`](../../bufferview/) 实例中

```csharp
public void MergeImages()
```

## 备注

图像可以以三种不同的方式存储：
 - As satellite files.
 - Embedded as MIME64 into the JSON document
 - Referenced with [`BufferView`](../../bufferview/) This call ensures all images will be internalized as [`BufferView`](../../bufferview/) instances. This action cannot be reversed.

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

