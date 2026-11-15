---
title: "Класс IgesDrawableBase"
linktitle: "IgesDrawableBase"
articleTitle: "IgesDrawableBase"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.Iges.Drawables.IgesDrawableBase. Предоставляет базовый класс для промежуточного представления сущностей документа в простом геометрическом ..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.iges.drawables/igesdrawablebase/"
keywords: "IgesDrawableBase, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## IgesDrawableBase class

Предоставляет базовый класс для промежуточного представления сущностей документа в простой геометрической форме.

```csharp
public abstract class IgesDrawableBase : IDrawingEntity, IIgesDrawable
```

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
| abstract [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/getnewpropsdrawable/)(IDrawableProperties) | Создает новый drawable, используя геометрию текущего drawable и предоставленные негeометрические свойства |
| abstract [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/gettransformeddrawable/)(Point3D[]) | Создает новый drawable, используя предоставленные точки и негeометрические свойства текущего drawable |

### См. также

* interface [IDrawingEntity](../../aspose.cad/idrawingentity/)
* interface [IIgesDrawable](../iigesdrawable/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

