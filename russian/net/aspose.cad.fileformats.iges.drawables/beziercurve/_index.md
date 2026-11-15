---
title: "Класс BezierCurve"
linktitle: "BezierCurve"
articleTitle: "BezierCurve"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Iges.Drawables.BezierCurve class. Предоставляет промежуточное представление Drawable в виде кубической кривой Безье"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.iges.drawables/beziercurve/"
keywords: "BezierCurve, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## BezierCurve class

Предоставляет промежуточное представление Drawable в виде кубической кривой Безье.

```csharp
public class BezierCurve : IgesDrawableBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BezierCurve](beziercurve/)(IDrawableProperties, Point3D[]) | Создает новое геометрическое представление кривой Безье из геометрических точек и негeометрических свойств |

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
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/beziercurve/getnewpropsdrawable/)(IDrawableProperties) | Создает новую кривую Безье, используя геометрию текущей BEzier кривой и предоставленные негeометрические свойства |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/beziercurve/gettransformeddrawable/)(Point3D[]) | Создает новую кривую Безье, используя предоставленные точки и негeометрические свойства текущей кривой Безье |

### См. также

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

