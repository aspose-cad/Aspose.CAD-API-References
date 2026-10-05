---
title: "IgesDrawableBase Class"
linktitle: "IgesDrawableBase"
articleTitle: "IgesDrawableBase"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Iges.Drawables.IgesDrawableBase class. Provides a base class for intermediate representation of document entities in simple geometric ..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.iges.drawables/igesdrawablebase/"
keywords: "IgesDrawableBase, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## IgesDrawableBase class

Provides a base class for intermediate representation of document entities in simple geometric form

```csharp
public abstract class IgesDrawableBase : IDrawingEntity, IIgesDrawable
```

## Properties

| Name | Description |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/allpoints/) { get; } | Array of all points defining geometry |
| [Childs](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/childs/) { get; } |  |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/entityuid/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/id/) { get; } |  |
| [Properties](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/properties/) { get; } | Non-geometric properties for geometry |

## Methods

| Name | Description |
| --- | --- |
| abstract [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/getnewpropsdrawable/)(IDrawableProperties) | Creates a new drawable using geometry of current drawable and provided non-geometric properties |
| abstract [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/gettransformeddrawable/)(Point3D[]) | Creates a new drawable using provided points and non-geometric properties of current drawable |

### See Also

* interface [IDrawingEntity](../../aspose.cad/idrawingentity/)
* interface [IIgesDrawable](../iigesdrawable/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

