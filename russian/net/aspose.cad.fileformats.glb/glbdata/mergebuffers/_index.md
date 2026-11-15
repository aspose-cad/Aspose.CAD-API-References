---
title: "GlbData.MergeBuffers"
linktitle: "MergeBuffers"
articleTitle: "MergeBuffers"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Объединяет все экземпляры LogicalBuffers в один большой."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.glb/glbdata/mergebuffers/"
product_version: "26.9"
---
## MergeBuffers() {#mergebuffers}

Объединяет все экземпляры [`LogicalBuffers`](../logicalbuffers/) в один большой.

```csharp
public void MergeBuffers()
```

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | .Net массивы имеют верхний предел в 2 ГБ, поэтому это максимальный размер, до которого буфер обычно может вырасти; попытка объединить буферы, суммарный размер которых превышает 2 ГБ, вызовет это исключение. |

## Примечания

При объединении буферов также корректируются смещения BufferView, чтобы данные, на которые они указывают, оставались прежними.
 
 

Если требуется включить изображения в бинарный файл, вызовите [`MergeImages`](../mergeimages/)
перед вызовом [`MergeBuffers`](../mergebuffers/).

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

---

## MergeBuffers(int) {#mergebuffers_1}

Объединяет все экземпляры [`LogicalBuffers`](../logicalbuffers/) в буферы размером *maxSize*.

```csharp
public void MergeBuffers(int maxSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| maxSize | Int32 | Максимальный размер каждого буфера. Обратите внимание, что если отдельный BufferView больше, чем *maxSize*, этот буфер также будет больше. |

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

