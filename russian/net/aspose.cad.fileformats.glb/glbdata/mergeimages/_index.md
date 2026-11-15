---
title: "GlbData.MergeImages"
linktitle: "MergeImages"
articleTitle: "MergeImages"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Переносит всё содержимое LogicalImages в экземпляры BufferView"
type: docs
weight: 180
url: "/net/aspose.cad.fileformats.glb/glbdata/mergeimages/"
product_version: "26.9"
---
## GlbData.MergeImages method

Переносит всё содержимое [`LogicalImages`](../logicalimages/) в экземпляры [`BufferView`](../../bufferview/).

```csharp
public void MergeImages()
```

## Примечания

Изображения могут храниться тремя разными способами:
 - As satellite files.
 - Embedded as MIME64 into the JSON document
 - Referenced with [`BufferView`](../../bufferview/) This call ensures all images will be internalized as [`BufferView`](../../bufferview/) instances. This action cannot be reversed.

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

