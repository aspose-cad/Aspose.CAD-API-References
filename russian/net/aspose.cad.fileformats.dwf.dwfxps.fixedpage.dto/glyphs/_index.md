---
title: "Класс Glyphs"
linktitle: "Glyphs"
articleTitle: "Glyphs"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Glyphs class. Глифы. Элемент Glyphs представляет последовательность текста с одинаковым форматированием из одного шрифта...."
type: docs
weight: 120
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/"
keywords: "Glyphs, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Glyphs class

Глифы.
Элемент Glyphs представляет последовательность текста с одинаковым форматированием из одного шрифта.
Он предоставляет информацию, необходимую для точного рендеринга, и поддерживает поиск
а также функции выбора в потребителях просмотра.

```csharp
public class Glyphs
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Glyphs](glyphs/)() | Инициализирует новый экземпляр класса `Glyphs`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BidiLevel](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/bidilevel/) { get; set; } | Получает или задает уровень BIDI. Указывает уровень вложенности двунаправленного алгоритма Unicode. Чётные значения означают раскладку слева направо, нечётные — справа налево. При раскладке справа налево начало последовательности размещается справа от первого глифа, а положительные ширины продвижения (обозначающие продвижение влево) размещают последующие глифы слева от предыдущего глифа. Допустимые значения находятся в диапазоне от 0 до 61 включительно. |
| [CaretStops](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/caretstops/) { get; set; } | Получает или задает позиции остановки каретки. Определяет позиции в последовательности символов Unicode, в которых инструмент выбора текста может разместить каретку редактирования. Возможные позиции остановки каретки определяются их индексами в кодовых единицах UTF‑16, представленных значением атрибута UnicodeString. Если этот атрибут отсутствует, текст в значении атрибута UnicodeString ДОЛЖЕН интерпретироваться как имеющий остановку каретки между каждой кодовой единицей UTF‑16 и в начале и в конце текста. Значение ДОЛЖНО указывать, что каретка не может останавливаться перед большинством комбинирующих знаков или перед второй кодовой единицей UTF‑16 суррогатных пар. |
| [Clip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/clip/) { get; set; } | Получает или задает обрезку (clip). Ограничивает область отрисовки элемента. Только части элемента Glyphs, попадающие в область обрезки (даже частично обрезанные символы), оставляют отметки на странице. |
| [DeviceFontName](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/devicefontname/) { get; set; } | Получает или задает имя шрифта устройства. Уникально идентифицирует конкретный шрифт устройства. Идентификатор обычно определяется поставщиком оборудования или поставщиком шрифтов. |
| [Fill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/fill/) { get; set; } | Получает или задает заливку. |
| [FixedPageNavigateUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/fixedpagenavigateuri/) { get; set; } | Получает или задает URI навигации фиксированной страницы. Связывает гиперссылку URI с элементом. Может быть относительной ссылкой или URI, указывающим на ресурс, находящийся внутри пакета или вне его. |
| [FontRenderingEmSize](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/fontrenderingemsize/) { get; set; } | Получает или задает размер шрифта в EM для рендеринга. Указывает размер шрифта в единицах поверхности рисования, выраженный как число с плавающей запятой в единицах эффективного координатного пространства. Значение 0 приводит к отсутствию видимого текста. |
| [FontUri](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/fonturi/) { get; set; } | Получает или задает URI шрифта. URI физического шрифта, из которого берутся все глифы в последовательности. URI ДОЛЖЕН ссылаться на шрифт, содержащийся в пакете. Если указанный физический шрифт является коллекцией TrueType (содержащей несколько начертаний), часть URI после знака # представляет собой индекс, начинающийся с 0, указывающий, какое начертание коллекции TrueType следует использовать. |
| [GlyphsClip](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/glyphsclip/) { get; set; } | Получает или задает обрезку глифов. Ограничивает область отрисовки элемента. Только части элемента Glyphs, попадающие в область обрезки (даже частично обрезанные символы), оставляют отметки на странице. |
| [GlyphsFill](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/glyphsfill/) { get; set; } | Получает или задает заливку глифов. Описывает кисть, используемую для заполнения формы отрисованных глифов. |
| [GlyphsOpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/glyphsopacitymask/) { get; set; } | Получает или задает маску непрозрачности глифов. Указывает маску альфа‑значений, применяемую к глифам так же, как атрибут Opacity, но позволяющую использовать разные альфа‑значения для разных областей элемента. |
| [GlyphsRenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/glyphsrendertransform/) { get; set; } | Получает или задает трансформацию рендеринга глифов. Устанавливает новую систему координат для последовательности глифов, указанной элементом Glyphs. Трансформация рендеринга влияет на обрезку, маску непрозрачности, заливку, начало координат X и Y, фактическую форму отдельных глифов и ширины продвижения. Трансформация также влияет на размер шрифта и значения, указанные в атрибуте Indices. |
| [Indices](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/indices/) { get; set; } | Получает или задает индексы. Указывает серию индексов глифов и их атрибутов, используемых для рендеринга последовательности глифов. Если атрибут UnicodeString элемента Glyphs не указан или содержит пустое значение «» или «{ }», и если атрибут Indices не указан или не содержит индексов глифов, потребитель ДОЛЖЕН вызвать ошибку. |
| [IsSideways](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/issideways/) { get; set; } | Получает или задает значение, указывающее, находится ли glyph боком. Указывает, что glyph повернут на бок, при этом origin определяется как верхний центр неповернутого glyph. |
| [Language](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/language/) { get; set; } | Получает или задает язык. Указывает язык по умолчанию, используемый для текущего элемента и для всех дочерних или потомковых элементов. Язык указывается в соответствии с RFC 3066. |
| [Name](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/name/) { get; set; } | Получает или задает имя. Содержит строковое значение, которое идентифицирует текущий элемент как именованную, адресуемую точку в документе для целей гиперссылок. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/opacity/) { get; set; } | Получает или задает opacity. Определяет равномерную прозрачность элемента glyph. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения вне этого диапазона недействительны. |
| [OpacityMask](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/opacitymask/) { get; set; } | Получает или задает opacity mask. Указывает маску альфа‑значений, применяемую к glyphs так же, как атрибут Opacity, но позволяющую использовать разные альфа‑значения для разных областей элемента. |
| [OriginX](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/originx/) { get; set; } | Получает или задает origin x. Указывает координату x первого glyph в последовательности, в единицах эффективного координатного пространства. glyph размещается так, чтобы передний край его вектора продвижения и базовая линия пересекались с точкой, определённой атрибутами OriginX и OriginY. |
| [OriginY](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/originy/) { get; set; } | Получает или задает origin y. Указывает координату y первого glyph в последовательности, в единицах эффективного координатного пространства. glyph размещается так, чтобы передний край его вектора продвижения и базовая линия пересекались с точкой, определённой атрибутами OriginX и OriginY. |
| [RenderTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/rendertransform/) { get; set; } | Получает или задает render transform. Устанавливает новую систему координат для последовательности glyph, указанной элементом Glyphs. render transform влияет на обрезку (clip), opacity mask, заливку, origin x, origin y, фактическую форму отдельных glyph и ширины продвижения. render transform также влияет на размер шрифта и значения, указанные в атрибуте Indices. |
| [StyleSimulations](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/stylesimulations/) { get; set; } | Получает или задает style simulations. Указывает симуляцию стиля. Допустимые значения: None, ItalicSimulation, BoldSimulation и BoldItalicSimulation. |
| [UnicodeString](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/glyphs/unicodestring/) { get; set; } | Получает или задает unicode string. Содержит строку текста, отрисованного элементом Glyphs. Текст задаётся в виде кодовых точек Unicode. Если атрибут UnicodeString элемента Glyphs не указан или содержит пустое значение («» или «{ }»), и если атрибут Indices не указан или не содержит индексов glyph, тогда потребитель ДОЛЖЕН вызвать ошибку. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

