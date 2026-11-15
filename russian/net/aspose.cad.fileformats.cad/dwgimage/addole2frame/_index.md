---
title: "DwgImage.AddOle2Frame"
linktitle: "AddOle2Frame"
articleTitle: "AddOle2Frame"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод DwgImage. Добавляет сущность OLE2FRAME в чертеж, используя данные BMP‑изображения."
type: docs
weight: 70
url: "/net/aspose.cad.fileformats.cad/dwgimage/addole2frame/"
product_version: "26.9"
---
## DwgImage.AddOle2Frame method

Добавляет объект OLE2FRAME в чертеж, используя данные BMP‑изображения.

```csharp
public void AddOle2Frame(byte[] imageData, Cad3DPoint insertPoint = null, double? width = default, 
    double? height = default, bool lockAspectRatio = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageData | Byte[] | Массив байтов, содержащий 24‑битные данные BMP‑изображения. |
| insertPoint | Cad3DPoint | Точка вставки сущности OLE2FRAME. |
| ширина | Nullable`1 | Ширина OLE2FRAME. |
| высота | Nullable`1 | Высота OLE2FRAME. |
| lockAspectRatio | Boolean | Если true, сохраняет соотношение сторон изображения, корректируя высоту на основе ширины или наоборот. |

### См. также

* class [Cad3DPoint](../../../aspose.cad.fileformats.cad.cadobjects/cad3dpoint/)
* class [DwgImage](../)
* namespace [Aspose.CAD.FileFormats.Cad](../../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../../)

