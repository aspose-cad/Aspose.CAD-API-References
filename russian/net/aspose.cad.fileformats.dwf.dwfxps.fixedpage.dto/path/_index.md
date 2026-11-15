---
title: "Класс Path"
linktitle: "Path"
articleTitle: "Path"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Path class. Путь. Определяет один графический эффект, который будет отрисован на странице. Он рисует геометрию с..."
type: docs
weight: 200
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/"
keywords: "Path, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Path class

Путь.
Определяет один графический эффект, который будет отрисован на странице.
Он рисует геометрию кистью и обводит её контуром.

```csharp
public class Path
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Path](path/)() | Создаёт новый экземпляр класса `Path`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutomationPropertiesHelpText](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/automationpropertieshelptext/) { get; set; } | Получает или задает текст подсказки свойств автоматизации. Подробное описание Path для целей доступности, особенно если заполнено ImageBrush. |
| [AutomationPropertiesName](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/automationpropertiesname/) { get; set; } | Получает или задает имя свойств автоматизации. Краткое описание Path для целей доступности, особенно если заполнено ImageBrush. |
| [Clip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/clip/) { get; set; } | Получает или задает обрезку. Ограничивает область рендеринга элемента. |
| [Data](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/data/) { get; set; } | Получает или задает данные. Описывает геометрию пути. |
| [Fill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/fill/) { get; set; } | Получает или задает заливку. Описывает кисть, используемую для рисования геометрии, указанной в свойстве Data пути. |
| [FixedPageNavigateUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/fixedpagenavigateuri/) { get; set; } | Получает или задает URI навигации фиксированной страницы. Связывает гиперссылку URI с элементом. Может быть относительной ссылкой или URI, указывающим на ресурс, находящийся внутри пакета или вне его. |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/language/) { get; set; } | Получает или задает язык. Указывает язык по умолчанию, используемый для текущего элемента и для всех дочерних или потомковых элементов. Язык указывается в соответствии с RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/name/) { get; set; } | Получает или задает имя. Содержит строковое значение, которое идентифицирует текущий элемент как именованную, адресуемую точку в документе для целей гиперссылок. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность элемента пути. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения за пределами этого диапазона недействительны. |
| [OpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/opacitymask/) { get; set; } | Получает или задает маску непрозрачности. Указывает маску альфа‑значений, применяемую к пути так же, как атрибут Opacity, но позволяющую использовать разные альфа‑значения для разных областей элемента. |
| [PathClip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathclip/) { get; set; } | Получает или задает обрезку пути. Ограничивает отрисованную область элемента. |
| [PathData](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathdata/) { get; set; } | Получает или задает данные пути. Описывает геометрию пути. |
| [PathFill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathfill/) { get; set; } | Получает или задает заливку пути. Описывает кисть, используемую для рисования геометрии, указанной в свойстве Data пути. |
| [PathOpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathopacitymask/) { get; set; } | Получает или задает маску непрозрачности пути. Указывает маску альфа‑значений, применяемую к пути так же, как атрибут Opacity, но позволяющую использовать разные альфа‑значения для разных областей элемента. |
| [PathRenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathrendertransform/) { get; set; } | Получает или задает трансформацию отрисовки пути. Устанавливает новую систему координат для всех атрибутов пути и всех дочерних элементов пути, таких как геометрия, определённая элементом свойства Path.Data. |
| [PathStroke](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/pathstroke/) { get; set; } | Получает или задает обводку пути. Указывает кисть, используемую для рисования обводки. |
| [RenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/rendertransform/) { get; set; } | Получает или задает трансформацию отрисовки. Устанавливает новую систему координат для всех атрибутов пути и всех дочерних элементов пути, таких как геометрия, определённая элементом свойства Path.Data. |
| [SnapsToDevicePixels](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/snapstodevicepixels/) { get; set; } | Получает или задает значение, указывающее, привязывается ли к пикселям устройства. При сглаживании потребители управляют тем, привязываются ли контрольные точки к ближайшим пикселям устройства. Допустимые значения: ‘false’ и ‘true’. Потребители МОГУТ игнорировать этот атрибут. |
| [SnapsToDevicePixelsSpecified](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/snapstodevicepixelsspecified/) { get; set; } | Получает или задает значение, указывающее, привязывается ли к пикселям устройства. |
| [Stroke](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/stroke/) { get; set; } | Получает или задает обводку. Указывает кисть, используемую для рисования обводки. |
| [StrokeDashArray](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedasharray/) { get; set; } | Получает или задает массив штрихов обводки. Указывает длину тире и пробелов контурной обводки. Эти значения задаются как кратные толщине обводки в виде списка, разделённого пробелами, содержащего чётное количество неотрицательных значений. При отрисовке обводки тире и пробелы, указанные этими значениями, повторяются, чтобы покрыть всю длину обводки. Если этот атрибут опущен, обводка рисуется сплошной, без пробелов. |
| [StrokeDashCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedashcap/) { get; set; } | Получает или задает форму конца штриха обводки. Указывает, как рисуются концы каждого тире. Допустимые значения: Flat, Round, Square и Triangle. |
| [StrokeDashOffset](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokedashoffset/) { get; set; } | Получает или задает смещение штриха обводки. Регулирует начальную точку повторения шаблона массива тире. Если значение опущено, массив тире выравнивается с началом обводки. Значения задаются как кратные толщине обводки. |
| [StrokeEndLineCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokeendlinecap/) { get; set; } | Получает или задает форму конца линии обводки. Определяет форму конца последнего тире в обводке. Допустимые значения: Flat, Square, Round и Triangle. |
| [StrokeLineJoin](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokelinejoin/) { get; set; } | Получает или задает соединение линий обводки. Указывает, как обводка рисуется на угле пути. Допустимые значения: Miter, Bevel и Round. Если выбран Miter, значение StrokeMiterLimit используется при рисовании обводки. |
| [StrokeMiterLimit](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokemiterlimit/) { get; set; } | Получает или задает предел среза обводки. Отношение между максимальной длиной среза и половиной толщины обводки. Это значение имеет значение только если атрибут StrokeLineJoin установлен в Miter. |
| [StrokeStartLineCap](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokestartlinecap/) { get; set; } | Получает или задает форму начала линии обводки. Определяет форму начала первого тире в обводке. Допустимые значения: Flat, Square, Round и Triangle. |
| [StrokeThickness](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/path/strokethickness/) { get; set; } | Получает или задает толщину обводки. Указывает толщину обводки в единицах эффективного пространства координат (включает трансформацию отрисовки пути). Обводка рисуется поверх границы геометрии, указанной в свойстве Data элемента Path. Половина StrokeThickness выходит за пределы геометрии, указанной в свойстве Data. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

