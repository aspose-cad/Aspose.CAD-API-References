---
title: "BezierCurve 类"
linktitle: "BezierCurve"
articleTitle: "BezierCurve"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Iges.Drawables.BezierCurve 类。提供以三次贝塞尔曲线形式的中间可绘制表示"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.iges.drawables/beziercurve/"
keywords: "BezierCurve, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## BezierCurve class

提供以三次贝塞尔曲线形式的中间 Drawable 表示

```csharp
public class BezierCurve : IgesDrawableBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BezierCurve](beziercurve/)(IDrawableProperties, Point3D[]) | 从几何点和非几何属性创建新的贝塞尔曲线几何表示 |

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
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/beziercurve/getnewpropsdrawable/)(IDrawableProperties) | 使用当前贝塞尔曲线的几何形状和提供的非几何属性创建新的贝塞尔曲线 |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/beziercurve/gettransformeddrawable/)(Point3D[]) | 使用提供的点以及当前贝塞尔曲线的非几何属性创建新的贝塞尔曲线 |

### 另请参阅

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

