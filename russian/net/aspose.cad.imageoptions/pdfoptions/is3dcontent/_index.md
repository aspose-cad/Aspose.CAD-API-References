---
title: "PdfOptions.Is3DContent"
linktitle: "Is3DContent"
articleTitle: "Is3DContent"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство PdfOptions. Получает или задает, должно ли содержимое документа быть представлено в виде 3D модели. Позволяет экспортировать содержимое U3D напрямую в PDF в форме o..."
type: docs
weight: 50
url: "/net/aspose.cad.imageoptions/pdfoptions/is3dcontent/"
product_version: "26.9"
---
## PdfOptions.Is3DContent property

Получает или задает, должно ли содержимое документа быть представлено в виде 3D модели.
Позволяет экспортировать содержимое U3D напрямую в PDF в виде интерактивного 3D объекта аннотации.
Полученный PDF‑файл будет содержать единственный объект 3D модели, занимающий всю страницу с полями.

```csharp
public bool Is3DContent { get; set; }
```

## Примеры

Настраивает экспорт U3dImage в PDF, содержащий 3D модель нужного размера.

```csharp
using (U3dImage u3dImage = (U3dImage)Image.Load(fileName))
{
    PdfOptions pdfOptions = new PdfOptions() {Is3DContent = true};
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PageWidth = 1600; 
    rasterizationOptions.PageHeight = 1600; 
    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    u3dImage.Save(outFile, pdfOptions);
}
```

### См. также

* class [PdfOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

