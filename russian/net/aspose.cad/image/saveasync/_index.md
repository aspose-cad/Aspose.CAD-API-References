---
title: "Image.SaveAsync"
linktitle: "SaveAsync"
articleTitle: "SaveAsync"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод Image. Сохраняет данные объекта в указанное местоположение файла в указанном формате файла согласно параметрам сохранения."
type: docs
weight: 150
url: "/net/aspose.cad/image/saveasync/"
product_version: "26.9"
---
## SaveAsync(Stream, ImageOptionsBase) {#saveasync}

Сохраняет данные изображения в указанный поток в заданном формате файла в соответствии с параметрами сохранения.

```csharp
public Task SaveAsync(Stream stream, ImageOptionsBase optionsBase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Поток | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Параметры сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Невозможно сохранить в указанный формат, так как он в данный момент не поддерживается.;optionsBase |
| [ImageSaveException](../../../aspose.cad.cadexceptions/imagesaveexception/) | Экспорт изображения не удался. |

## Примеры

Экспортирует чертёж в формат JPEG, поворачивает его на 90 градусов и записывает в поток памяти

```csharp
using (var ms = new MemoryStream())
{
    using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
    {
        await image.Save(ms, new JpegOptions()
        {
            Rotation = RotateFlipType.Rotate90FlipNone
        });
    }
}
```

### См. также

* class [ImageOptionsBase](../../../aspose.cad.imageoptions/imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## SaveAsync(string, ImageOptionsBase) {#saveasync_1}

Сохраняет данные объекта в указанное расположение файла в заданном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual Task SaveAsync(string filePath, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| опции | ImageOptionsBase | Опции. |

## Примеры

Экспортирует чертёж в BMP с указанным размером

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    await image.Save("targetFile.bmp", new BmpOptions()
    {
        VectorRasterizationOptions = new CadRasterizationOptions()
        {
            PageWidth = 640,
            PageHeight = 480
        }
    });
}
```

### См. также

* class [ImageOptionsBase](../../../aspose.cad.imageoptions/imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

