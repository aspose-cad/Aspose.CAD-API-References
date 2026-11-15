---
title: "Класс Polyline"
linktitle: "Polyline"
articleTitle: "Polyline"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Iges.Drawables.Polyline class. Предоставляет промежуточное представление Drawable в виде сегментированной линии"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.iges.drawables/polyline/"
keywords: "Polyline, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Polyline class

Предоставляет промежуточное представление Drawable в виде сегментированной линии.

```csharp
public class Polyline : IgesDrawableBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Polyline](polyline/)(IDrawableProperties, Point3D[]) | Создает новое геометрическое представление Miltisegment линии из геометрических точек и негeометрических свойств |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/allpoints/) { get; } | Массив всех точек, определяющих геометрию |
| [Childs](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/childs/) { get; } |  |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/entityuid/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/id/) { get; } |  |
| [Properties](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/properties/) { get; } | Негеометрические свойства для геометрии |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/polyline/getnewpropsdrawable/)(IDrawableProperties) | Создает новый drawable, используя геометрию текущего drawable и предоставленные негeометрические свойства |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/polyline/gettransformeddrawable/)(Point3D[]) | Создает новый drawable, используя предоставленные точки и негeометрические свойства текущего drawable |

### См. также

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

