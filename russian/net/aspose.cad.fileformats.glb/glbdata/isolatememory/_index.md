---
title: "GlbData.IsolateMemory"
linktitle: "IsolateMemory"
articleTitle: "IsolateMemory"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Обновляет все внутренние буферы памяти."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.glb/glbdata/isolatememory/"
product_version: "26.9"
---
## GlbData.IsolateMemory method

Обновляет все внутренние буферы памяти.

```csharp
public void IsolateMemory()
```

## Примечания

[`Buffer`](../../buffer/) instances can be created using external `Byte` arrays, which
может потенциально быть общим с другими экземплярами. Прямое редактирование этих массивов может привести к
повреждению.
Этот метод обновляет все внутренние буферы памяти, копируя данные в недавно выделенные
буферы. Это гарантирует, что в данный момент все буферы памяти не являются общими и находятся в эксклюзивном
использовании этого [`GlbData`](../) экземпляра.

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

