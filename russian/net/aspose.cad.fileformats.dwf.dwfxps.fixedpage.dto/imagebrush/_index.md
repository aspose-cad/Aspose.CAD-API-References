---
title: "ImageBrush Класс"
linktitle: "ImageBrush"
articleTitle: "ImageBrush"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.ImageBrush class. Кисть изображения. Элемент ImageBrush используется для заполнения области изображением. Изображение i..."
type: docs
weight: 140
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/"
keywords: "ImageBrush, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## ImageBrush class

Кисть изображения.
Элемент ImageBrush используется для заполнения области изображением.
Изображение определено в координатном пространстве, заданном разрешением изображения.
Изображение ДОЛЖНО ссылаться на часть JPEG, PNG, TIFF или JPEG XR внутри пакета документа.

```csharp
public class ImageBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageBrush](imagebrush/)() | Инициализирует новый экземпляр класса `ImageBrush`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ImageBrushTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/imagebrushtransform/) { get; set; } | Получает или задаёт преобразование кисти изображения. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Область просмотра (viewport) кисти преобразуется с использованием локального эффективного преобразования рендеринга. |
| [ImageSource](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/imagesource/) { get; set; } | Получает или задаёт источник изображения. Указывает URI ресурса изображения или комбинацию URI ресурса изображения и ресурса цветового профиля. URI ДОЛЖЕН ссылаться на части в пакете. |
| [Opacity](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/opacity/) { get; set; } | Получает или задает непрозрачность. Определяет равномерную прозрачность заполнения кисти. Значения находятся в диапазоне от 0 (полностью прозрачный) до 1 (полностью непрозрачный), включительно. Значения вне этого диапазона недействительны. |
| [TileMode](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/tilemode/) { get; set; } | Получает или задает режим плитки. Указывает, как содержимое будет размещаться плиткой в заполненном регионе. Допустимые значения: None, Tile, FlipX, FlipY и FlipXY. |
| [Transform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/transform/) { get; set; } | Получает или задаёт преобразование. Описывает матричное преобразование, применяемое к координатному пространству кисти. Свойство Transform конкатенируется с текущим эффективным преобразованием рендеринга, чтобы получить эффективное преобразование рендеринга, локальное для кисти. Область просмотра (viewport) кисти преобразуется с использованием локального эффективного преобразования рендеринга. |
| [Viewbox](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewbox/) { get; set; } | Получает или задаёт область просмотра (view box). Указывает позицию и размеры исходного содержимого кисти. Указывает четыре разделённых запятыми действительных числа (x, y, ширина, высота), где ширина и высота неотрицательны. Указанные размеры относительны к физическим размерам изображения, выраженным в единицах 1/96\". Углы области просмотра сопоставляются с углами области вывода, обеспечивая стандартную обрезку и преобразование для исходного содержимого кисти. |
| [ViewboxUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewboxunits/) { get; set; } | Получает или задает единицы области просмотра. Указывает взаимосвязь координат области просмотра с содержащим координатным пространством. |
| [Viewport](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewport/) { get; set; } | Получает или задаёт область вывода (viewport). Указывает регион в содержащем координатном пространстве основной плитки кисти, который (возможно многократно) применяется для заполнения региона, к которому применяется кисть. Указывает четыре разделённых запятыми действительных числа (x, y, ширина, высота), где ширина и высота неотрицательны. Выравнивание шаблона кисти контролируется путем корректировки значений x и y. |
| [ViewportUnits](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/imagebrush/viewportunits/) { get; set; } | Получает или задает единицы области просмотра. Указывает взаимосвязь координат viewport с содержащим координатным пространством. |

### См. также

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

