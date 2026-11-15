---
title: "Класс Canvas"
linktitle: "Canvas"
articleTitle: "Canvas"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Canvas class. Холст. Элемент Canvas группирует элементы вместе. Glyphs и Path элементы могут быть groupe..."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/"
keywords: "Canvas, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Canvas class

Холст.
Элемент Canvas группирует элементы вместе.
 [Glyphs](../glyphs/) and [Path](../path/) elements can be grouped in a canvas in order to be identified as a unit(as a hyperlink destination)
или применить составное значение свойства к каждому дочернему и предковому элементу.

```csharp
public class Canvas
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Canvas](canvas/)() | Инициализирует новый экземпляр класса `Canvas`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutomationPropertiesHelpText](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/automationpropertieshelptext/) { get; set; } | Получает или задает текст справки свойств автоматизации. Подробное описание содержимого Canvas для целей доступности, особенно если оно заполнено набором графических и текстовых элементов, предназначенных для формирования единой векторной графики. |
| [AutomationPropertiesName](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/automationpropertiesname/) { get; set; } | Получает или задает имя свойств автоматизации. Краткое описание содержимого Canvas для целей доступности, особенно если оно заполнено набором векторных графических и текстовых элементов, предназначенных для формирования единой векторной графики. |
| [CanvasClip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasclip/) { get; set; } | Получает или задает обрезку холста. Ограничивает область рендеринга элемента. |
| [CanvasOpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasopacitymask/) { get; set; } | Получает или задает маску непрозрачности холста. Указывает маску альфа‑значений, применяемую к холсту так же, как атрибут Opacity, но позволяющую использовать разные альфа‑значения для разных областей элемента. |
| [CanvasRenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasrendertransform/) { get; set; } | Получает или задает преобразование рендеринга холста. Устанавливает новую систему координат для дочерних и наследуемых элементов холста, например другого холста. Также влияет на обрезку и маску непрозрачности. |
| [CanvasResources](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/canvasresources/) { get; set; } | Получает или задает ресурсы холста. Содержит словарь ресурсов для элемента Canvas. |
| [Clip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/clip/) { get; set; } | Получает или задает обрезку. Ограничивает область рендеринга элемента. |
| [FixedPageNavigateUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/fixedpagenavigateuri/) { get; set; } | Получает или задает URI навигации фиксированной страницы. Связывает гиперссылку URI с элементом. Может быть относительной ссылкой или URI, указывающим на ресурс, находящийся внутри пакета или вне его. |
| [Items](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/items/) { get; set; } | Получает или задает элементы. Сгруппированные наследники FixedPage. |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/language/) { get; set; } | Получает или задает язык. Указывает язык по умолчанию, используемый для текущего элемента и для всех дочерних или потомковых элементов. Язык указывается в соответствии с RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/name/) { get; set; } | Получает или задает имя. Содержит строковое значение, которое идентифицирует текущий элемент как именованную, адресуемую точку в документе для целей гиперссылок. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность холста. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения за пределами этого диапазона недействительны. |
| [OpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/opacitymask/) { get; set; } | Получает или задает маску непрозрачности. Указывает маску альфа‑значений, которая применяется к холсту так же, как атрибут Opacity, но позволяет использовать разные альфа‑значения для разных областей элемента. |
| [RenderOptionsEdgeMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/renderoptionsedgemode/) { get; set; } | Получает или задает режим краев параметров рендеринга. Управляет тем, как отображаются края путей внутри холста. Единственное допустимое значение — Aliased. Если этот атрибут опущен, края рендерятся способом, установленным по умолчанию у потребителя. |
| [RenderOptionsEdgeModeSpecified](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/renderoptionsedgemodespecified/) { get; set; } | Получает или задает значение, указывающее, указан ли режим краев параметров рендеринга. |
| [RenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/canvas/rendertransform/) { get; set; } | Получает или задает преобразование рендеринга. Устанавливает новую систему координат для дочерних и наследуемых элементов холста, например другого холста. Также влияет на обрезку и маску непрозрачности. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

