---
title: "DwfImage.Metadata"
linktitle: "Метаданные"
articleTitle: "Метаданные"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство DwfImage. Получает или задает информацию о метаданных. Возвращает массив записей метаданных из манифеста и ресурсов дескрипторов пакета Dwf/Dwfx."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.dwf/dwfimage/metadata/"
product_version: "26.9"
---
## DwfImage.Metadata property

Получает или задает информацию о метаданных.
Возвращает массив записей метаданных из манифеста и ресурсов дескрипторов пакета Dwf/Dwfx.

```csharp
public DwfMetadata[] Metadata { get; set; }
```

## Примеры

Извлекает все записи метаданных и изменяет одну из них.

```csharp
string file = "ExampleFile.dwf";
using (DwfImage image = (DwfImage) Aspose.CAD.Image.Load(file))
{
    string outFile = "ExampleFile_Changed.dwf";
    using (FileStream fs = new FileStream(outFile, FileMode.Create))
    {
        DwfMetadata[] metadata = image.Metadata;
        foreach (DwfMetadata dwfMetadata in metadata)
        {
            if (dwfMetadata.Category != "AutoCAD Drawing" || dwfMetadata.Name != "Creator")
            {
                continue;
            }

            dwfMetadata.Value = "Aspose CAD application";
        }

        image.Metadata = metadata;
        ImageOptionsBase options = new DwfOptions { OutputMode = CadOutputMode.Convert };
        image.Save(fs, jpegOptions);
    }
}
```

### См. также

* class [DwfMetadata](../../dwfmetadata/)
* class [DwfImage](../)
* namespace [Aspose.CAD.FileFormats.Dwf](../../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../../)

