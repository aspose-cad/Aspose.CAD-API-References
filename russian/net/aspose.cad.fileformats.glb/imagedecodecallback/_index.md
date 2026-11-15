---
title: "Делегат ImageDecodeCallback"
linktitle: "ImageDecodeCallback"
articleTitle: "ImageDecodeCallback"
second_title: "Aspose.CAD для .NET справка API"
description: "Обратный вызов, используемый для перехвата загрузки текстур, чтобы их мог декодировать клиентский движок и загрузить на GPU при необходимости."
type: docs
weight: 280
url: "/net/aspose.cad.fileformats.glb/imagedecodecallback/"
product_version: "26.9"
---
## ImageDecodeCallback delegate

Обратный вызов, используемый для перехвата загрузки текстур, чтобы они могли быть
декодированы клиентским движком и загружены в GPU, если необходимо.

```csharp
public delegate bool ImageDecodeCallback(ImageGlb image);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | ImageGlb | Изображение, содержащее текстуру |

### Возвращаемое значение

True, если мы хотим сохранить данные изображения в памяти внутри [`ImageGlb`](../../../aspose.cad.fileformats.glb/imageglb/).

В противном случае память будет очищена, и [`ImageGlb`](../../../aspose.cad.fileformats.glb/imageglb/) будет пустым.

### См. также

* class [ImageGlb](../imageglb/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

