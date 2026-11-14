---
title: "GlbData.IsolateMemory"
linktitle: "IsolateMemory"
articleTitle: "IsolateMemory"
second_title: "Aspose.CAD for .NET API 参考"
description: "GlbData 方法。刷新所有内部内存缓冲区。"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.glb/glbdata/isolatememory/"
product_version: "26.9"
---
## GlbData.IsolateMemory method

刷新所有内部内存缓冲区。

```csharp
public void IsolateMemory()
```

## 备注

[`Buffer`](../../buffer/) instances can be created using external `Byte` arrays, which
可能会与其他实例共享。直接编辑这些数组可能导致数据
损坏。
此方法通过将数据复制到新分配的
缓冲区。此确保在此时，所有内存缓冲区未共享且专用
使用此 [`GlbData`](../) 实例。

### 另请参阅

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

