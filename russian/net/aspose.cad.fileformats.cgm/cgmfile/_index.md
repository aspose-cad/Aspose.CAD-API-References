---
title: "Класс CgmFile"
linktitle: "CgmFile"
articleTitle: "CgmFile"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.Cgm.CgmFile. Класс изображения CGM."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.cgm/cgmfile/"
keywords: "CgmFile, Aspose.CAD.FileFormats.Cgm, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CgmFile class

Класс изображения CGM.

```csharp
public class CgmFile
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ColourIndexPrecision](../../aspose.cad.fileformats.cgm/cgmfile/colourindexprecision/) { get; set; } | Получает или задает текущую точность индекса цвета при чтении |
| [ColourModel](../../aspose.cad.fileformats.cgm/cgmfile/colourmodel/) { get; set; } | Получает или задает текущую модель цвета при чтении |
| [ColourPrecision](../../aspose.cad.fileformats.cgm/cgmfile/colourprecision/) { get; set; } | Получает или задает текущую точность цвета при чтении |
| [ColourSelectionMode](../../aspose.cad.fileformats.cgm/cgmfile/colourselectionmode/) { get; set; } | Получает или задает текущий режим выбора цвета при чтении |
| [ColourValueExtentMaximumColorValueRGB](../../aspose.cad.fileformats.cgm/cgmfile/colourvalueextentmaximumcolorvaluergb/) { get; set; } | Получает или задает текущий максимальный RGB‑значение цвета при чтении |
| [ColourValueExtentMinimumColorValueRGB](../../aspose.cad.fileformats.cgm/cgmfile/colourvalueextentminimumcolorvaluergb/) { get; set; } | Получает или задает текущий минимальный RGB‑значение цвета при чтении |
| [Commands](../../aspose.cad.fileformats.cgm/cgmfile/commands/) { get; } | Прочитанные команды CGM |
| [DeviceViewportSpecificationMode](../../aspose.cad.fileformats.cgm/cgmfile/deviceviewportspecificationmode/) { get; set; } | Получает или задает текущий режим спецификации области просмотра устройства при чтении |
| [EdgeWidthSpecificationMode](../../aspose.cad.fileformats.cgm/cgmfile/edgewidthspecificationmode/) { get; set; } | Получает или задает текущий режим спецификации ширины ребра при чтении |
| [IndexPrecision](../../aspose.cad.fileformats.cgm/cgmfile/indexprecision/) { get; set; } | Получает или задает текущую точность индекса при чтении |
| [IntegerPrecision](../../aspose.cad.fileformats.cgm/cgmfile/integerprecision/) { get; set; } | Получает или задает текущую точность целого числа при чтении |
| [InteriorStyleSpecificationMode](../../aspose.cad.fileformats.cgm/cgmfile/interiorstylespecificationmode/) { get; set; } | Получает или задает текущий режим спецификации внутреннего стиля при чтении |
| [LineWidthSpecificationMode](../../aspose.cad.fileformats.cgm/cgmfile/linewidthspecificationmode/) { get; set; } | Получает или задает текущий режим спецификации ширины линии при чтении |
| [MarkerSizeSpecificationMode](../../aspose.cad.fileformats.cgm/cgmfile/markersizespecificationmode/) { get; set; } | Получает или задает текущий режим спецификации размера маркера при чтении |
| [Messages](../../aspose.cad.fileformats.cgm/cgmfile/messages/) { get; } | Любые сообщения, возникшие при чтении или записи файла |
| [Name](../../aspose.cad.fileformats.cgm/cgmfile/name/) { get; } | Получает имя файла |
| [NamePrecision](../../aspose.cad.fileformats.cgm/cgmfile/nameprecision/) { get; set; } | Получает или задает текущую точность имени чтения Precision |
| [RealPrecision](../../aspose.cad.fileformats.cgm/cgmfile/realprecision/) { get; set; } | Получает или задает текущую реальную точность чтения Precision |
| [RealPrecisionProcessed](../../aspose.cad.fileformats.cgm/cgmfile/realprecisionprocessed/) { get; set; } | Получает или задает флаг обработки текущей реальной точности чтения Precision |
| [RestrictedTextType](../../aspose.cad.fileformats.cgm/cgmfile/restrictedtexttype/) { get; set; } | Получает или задает текущий тип ограниченного текста RestrictedTextType |
| [VDCIntegerPrecision](../../aspose.cad.fileformats.cgm/cgmfile/vdcintegerprecision/) { get; set; } | Получает или задает текущую целочисленную точность vdc Precision |
| [VDCRealPrecision](../../aspose.cad.fileformats.cgm/cgmfile/vdcrealprecision/) { get; set; } | Получает или задает текущую реальную точность vdc Precision |
| [VDCType](../../aspose.cad.fileformats.cgm/cgmfile/vdctype/) { get; set; } | Получает или задает текущий тип VDC |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyValues](../../aspose.cad.fileformats.cgm/cgmfile/applyvalues/)(CgmFile) | Копирует текущую метаинформацию |
| [ContainsConsumableNumber](../../aspose.cad.fileformats.cgm/cgmfile/containsconsumablenumber/)(string) | Определяет, содержит ли CGM определённый текст количества расходного материала |
| [ContainsFigureItemText](../../aspose.cad.fileformats.cgm/cgmfile/containsfigureitemtext/)(string) | Определяет, содержит ли CGM определённый текст элемента рисунка. |
| [ContainsTextElement](../../aspose.cad.fileformats.cgm/cgmfile/containstextelement/)(string) | Определяет, равен ли любой текстовый элемент указанному тексту. |
| [ContainsTorqueTextToFigItem](../../aspose.cad.fileformats.cgm/cgmfile/containstorquetexttofigitem/)(string, string) | Определяет, существует ли текст крутящего момента ("20 Nm (177 lb-in)") рядом с элементом рисунка |
| [GetFigureItemTexts](../../aspose.cad.fileformats.cgm/cgmfile/getfigureitemtexts/)(bool) | Получает все тексты элементов рисунка. |
| [GetGraphicName](../../aspose.cad.fileformats.cgm/cgmfile/getgraphicname/)() | Получает заголовок иллюстрации. |
| [GetInformation](../../aspose.cad.fileformats.cgm/cgmfile/getinformation/)(TextCommand) |  |
| [GetMetaTitle](../../aspose.cad.fileformats.cgm/cgmfile/getmetatitle/)() | Получает заголовок. |
| [GetRectangles](../../aspose.cad.fileformats.cgm/cgmfile/getrectangles/)() | Получает все найденные прямоугольники. |
| [IsWrittenDownToUp](../../aspose.cad.fileformats.cgm/cgmfile/iswrittendowntoup/)(TextCommand) | Определяет, повернут ли текст на 90 градусов против часовой стрелки |
| [ResetMetaDefinitions](../../aspose.cad.fileformats.cgm/cgmfile/resetmetadefinitions/)() | Сбрасывает настройки, такие как VDCRealPrecision или ColourModel |

### См. также

* namespace [Aspose.CAD.FileFormats.Cgm](../../aspose.cad.fileformats.cgm/)
* assembly [Aspose.CAD](../../)

