---
title: "IgesDrawableBase 类"
linktitle: "IgesDrawableBase"
articleTitle: "IgesDrawableBase"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Iges.Drawables.IgesDrawableBase 类。提供用于在简单几何中对文档实体进行中间表示的基类..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.iges.drawables/igesdrawablebase/"
keywords: "IgesDrawableBase, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## IgesDrawableBase class

提供用于以简单几何形式表示文档实体的中间表示的基类

```csharp
public abstract class IgesDrawableBase : IDrawingEntity, IIgesDrawable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/allpoints/) { get; } | 定义几何形状的所有点数组 |
| [Childs](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/childs/) { get; } |  |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/entityuid/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/id/) { get; } |  |
| [Properties](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/properties/) { get; } | 几何形状的非几何属性 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/getnewpropsdrawable/)(IDrawableProperties) | 使用当前可绘制对象的几何形状和提供的非几何属性创建新的可绘制对象 |
| abstract [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/gettransformeddrawable/)(Point3D[]) | 使用提供的点以及当前可绘制对象的非几何属性创建新的可绘制对象 |

### 另请参阅

* interface [IDrawingEntity](../../aspose.cad/idrawingentity/)
* interface [IIgesDrawable](../iigesdrawable/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

