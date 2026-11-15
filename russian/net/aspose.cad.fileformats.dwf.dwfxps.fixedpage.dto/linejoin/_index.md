---
title: "LineJoin Перечисление"
linktitle: "LineJoin"
articleTitle: "LineJoin"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.LineJoin перечисление. Соединение линий. Определяет внешний вид соединений линий."
type: docs
weight: 160
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/linejoin/"
product_version: "26.9"
---
## LineJoin enumeration

Соединение линий.
Определяет внешний вид соединений линий.

```csharp
public enum LineJoin
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Miter | `0` | Miter. Указывает, что область для заполнения включает пересечение штрихов, проецируемых до бесконечности, а затем обрезается на определённом расстоянии. Пересечение штрихов обрезается линией, перпендикулярной биссектору угла между штрихами, на расстоянии, равном значению предела среза штриха, умноженному на половину толщины штриха. |
| Bevel | `1` | Bevel. Указывает, что внешний угол соединённых линий должен быть заполнен, охватывая треугольную область угла прямой линией между внешними углами каждого штриха. |
| Round | `2` | Round. Указывает, что внешний угол соединённых линий должен быть заполнен, охватывая округлую область с центром в точке пересечения двух линий и радиусом, равным половине толщины штриха. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

