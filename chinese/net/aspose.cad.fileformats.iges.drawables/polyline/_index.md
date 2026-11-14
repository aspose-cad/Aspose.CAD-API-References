---
title: "折线类"
linktitle: "折线"
articleTitle: "折线"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Iges.Drawables.Polyline 类。提供以分段线形式的中间可绘制表示"
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.iges.drawables/polyline/"
keywords: "Polyline, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Polyline class

提供以分段线形式的中间 Drawable 表示

```csharp
public class Polyline : IgesDrawableBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Polyline](polyline/)(IDrawableProperties, Point3D[]) | 从几何点和非几何属性创建新的多段线几何表示 |

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
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/polyline/getnewpropsdrawable/)(IDrawableProperties) | 使用当前可绘制对象的几何形状和提供的非几何属性创建新的可绘制对象 |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/polyline/gettransformeddrawable/)(Point3D[]) | 使用提供的点以及当前可绘制对象的非几何属性创建新的可绘制对象 |

### 另请参阅

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

