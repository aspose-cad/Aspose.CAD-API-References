---
title: "StpImage.Append"
linktitle: "Добавить"
articleTitle: "Добавить"
second_title: "Aspose.CAD для .NET справка API"
description: "StpImage метод. Добавляет содержимое другого STP-изображения. Эта функция позволяет объединять содержимое разных STP-изображений. В примере ниже, mode..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.stp/stpimage/append/"
product_version: "26.9"
---
## StpImage.Append method

Добавляет содержимое другого STP-изображения.
Эта функция позволяет объединять содержимое разных STP-изображений. В примере
ниже, модели загружаются из файлов и затем объединяются в одно изображение. Полученный
STP-изображение будет содержать все примитивы из каждого загруженного STP-файла.

```csharp
public void Append(StpImage imageToAppend)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageToAppend | StpImage | Изображение для добавления. |

## Примеры

Загрузка STP-изображений, их объединение в единое результирующее изображение и сохранение конечного
вывода в файл.

```csharp
string[] files = new string[] { "inFile1.stp", "inFile2.stp", "inFile3.stp" };
string outFile = "outFile.stp";
StpImage mergedImage = new StpImage();
foreach (var file in files)
    using (StpImage image = (StpImage) Image.Load(file))
        mergedImage.Append(image);
mergedImage.Save(outFile, new StpOptions());
```

### См. также

* class [StpImage](../)
* namespace [Aspose.CAD.FileFormats.Stp](../../../aspose.cad.fileformats.stp/)
* assembly [Aspose.CAD](../../../)

