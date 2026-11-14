---
title: "IIgesDrawable 接口"
linktitle: "IIgesDrawable"
articleTitle: "IIgesDrawable"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Iges.Drawables.IIgesDrawable 接口。用于实体或其部分的简单几何表示的父接口"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.iges.drawables/iigesdrawable/"
product_version: "26.9"
---
## IIgesDrawable interface

实体或其部分的简单几何表示的父接口

```csharp
public interface IIgesDrawable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/allpoints/) { get; } | 定义几何形状的所有点数组 |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/entityuid/) { get; set; } | 创建此实体的实体的唯一标识符（行号） |
| [Properties](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/properties/) { get; } | 几何表示的非几何属性 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/getnewpropsdrawable/)(IDrawableProperties) | 使用当前可绘制对象的几何形状和提供的非几何属性创建新的可绘制对象 |
| [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/iigesdrawable/gettransformeddrawable/)(Point3D[]) | 使用提供的点以及当前可绘制对象的非几何属性创建新的可绘制对象 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

