---
title: "Интерфейс IIgesDrawable"
linktitle: "IIgesDrawable"
articleTitle: "IIgesDrawable"
second_title: "Aspose.CAD для .NET справка API"
description: "Интерфейс Aspose.CAD.FileFormats.Iges.Drawables.IIgesDrawable. Родительский интерфейс для простого геометрического представления сущности или её части."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.iges.drawables/iigesdrawable/"
product_version: "26.9"
---
## IIgesDrawable interface

Родительский интерфейс для простого геометрического представления сущности или её части.

```csharp
public interface IIgesDrawable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/allpoints/) { get; } | Массив всех точек, определяющих геометрию |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/entityuid/) { get; set; } | Уникальный идентификатор (номер строки) сущности, создавшей эту сущность. |
| [Properties](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/properties/) { get; } | Негеометрические свойства геометрического представления. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/getnewpropsdrawable/)(IDrawableProperties) | Создает новый drawable, используя геометрию текущего drawable и предоставленные негeометрические свойства |
| [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/gettransformeddrawable/)(Point3D[]) | Создает новый drawable, используя предоставленные точки и негeометрические свойства текущего drawable |

### См. также

* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

