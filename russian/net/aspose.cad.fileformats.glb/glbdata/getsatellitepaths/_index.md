---
title: "GlbData.GetSatellitePaths"
linktitle: "GetSatellitePaths"
articleTitle: "GetSatellitePaths"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Получает список спутниковых/зависимых файлов для заданного файла glTF. Включает бинарные блобы и текстурные изображения."
type: docs
weight: 300
url: "/net/aspose.cad.fileformats.glb/glbdata/getsatellitepaths/"
product_version: "26.9"
---
## GlbData.GetSatellitePaths method

Получает список спутниковых/зависимых файлов для заданного файла glTF.
Это включает бинарные блобы и текстурные изображения.

```csharp
public static string[] GetSatellitePaths(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Допустимый путь к файлу. |

### Возвращаемое значение

Список относительных путей к файлам, как найдено в файле.

## Примечания

Этот метод разработан так, чтобы быть максимально быстрым и избегает выполнения большого количества
валидации и разбора файла glTf, он просто слепо ищет поля URI.

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

