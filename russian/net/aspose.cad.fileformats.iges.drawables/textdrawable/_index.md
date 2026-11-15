---
title: "Класс TextDrawable"
linktitle: "TextDrawable"
articleTitle: "TextDrawable"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Iges.Drawables.TextDrawable class. Предоставляет промежуточное представление Drawable текста в чертеже"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.iges.drawables/textdrawable/"
keywords: "TextDrawable, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TextDrawable class

Предоставляет промежуточное представление Drawable текста в чертеже.

```csharp
public class TextDrawable : IgesDrawableBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextDrawable](textdrawable/)(string, Point3D, double, double, double, IDrawableProperties) | Создает текстовый Drawable и определяет его границы текста |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/allpoints/) { get; } | Массив всех точек, определяющих геометрию |
| [Childs](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/childs/) { get; } |  |
| [EndBottomLine](../../aspose.cad.fileformats.iges.drawables/textdrawable/endbottomline/) { get; } | Правый нижний пункт границы текста, соответствует AllPoints[3] |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/entityuid/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/id/) { get; } |  |
| [Mirrioring](../../aspose.cad.fileformats.iges.drawables/textdrawable/mirrioring/) { get; } | Отражение текста |
| [Orientation](../../aspose.cad.fileformats.iges.drawables/textdrawable/orientation/) { get; } | Горизонтальный или вертикальный текст |
| [Origin](../../aspose.cad.fileformats.iges.drawables/textdrawable/origin/) { get; } | Левый нижний пункт границы текста, используется как начальная точка примитива, соответствует AllPoints[0] |
| [Properties](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/properties/) { get; } | Негеометрические свойства для геометрии |
| [Text](../../aspose.cad.fileformats.iges.drawables/textdrawable/text/) { get; } | Текст |
| [UpperLeft](../../aspose.cad.fileformats.iges.drawables/textdrawable/upperleft/) { get; } | Левый верхний пункт границы текста, соответствует AllPoints[1] |
| [UpperRight](../../aspose.cad.fileformats.iges.drawables/textdrawable/upperright/) { get; } | Правый верхний пункт границы текста, соответствует AllPoints[2] |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/textdrawable/getnewpropsdrawable/)(IDrawableProperties) | Создает новый Text drawable, используя геометрию текущего Text drawable и предоставленные негеометрические свойства |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/textdrawable/gettransformeddrawable/)(Point3D[]) | Создает новый Text drawable, используя предоставленные точки и негеометрические свойства текущего Text drawable |

### См. также

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

