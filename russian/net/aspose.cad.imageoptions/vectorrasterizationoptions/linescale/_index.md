---
title: "VectorRasterizationOptions.LineScale"
linktitle: "LineScale"
articleTitle: "LineScale"
second_title: "Aspose.CAD для .NET справка API"
description: "Свойство VectorRasterizationOptions. Получает или задает значение коэффициента масштабирования толщины линии относительно исходной толщины. Если вы хотите, чтобы линия была толще..."
type: docs
weight: 130
url: "/net/aspose.cad.imageoptions/vectorrasterizationoptions/linescale/"
product_version: "26.9"
---
## VectorRasterizationOptions.LineScale property

Получает или задает значение коэффициента масштабирования толщины линии относительно исходной толщины.
Если вы хотите увеличить толщину линии в 2 раза при экспорте, то вам нужно установить значение 2.
Если вы хотите уменьшить толщину линии в 4 раза при экспорте, то вам нужно установить значение 0.25.

```csharp
public float LineScale { get; set; }
```

## Примеры

Читает файл изображения в формате PLT и сохраняет изображение в формате SVG с .

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.plt", fileName);
string outFile = string.Format("{0}.svg", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (Image image = Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    ImageOptionsBase options = new SvgOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
                                             {
                                                 LineScale = 0.25f
                                             };

    image.Save(stream, options);
}
```

### См. также

* class [VectorRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

