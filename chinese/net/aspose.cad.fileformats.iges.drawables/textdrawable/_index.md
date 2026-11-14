---
title: "文本可绘制类"
linktitle: "文本可绘制"
articleTitle: "文本可绘制"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Iges.Drawables.TextDrawable 类。提供绘图中文本的中间可绘制表示"
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.iges.drawables/textdrawable/"
keywords: "TextDrawable, Aspose.CAD.FileFormats.Iges.Drawables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TextDrawable class

提供绘图中文本的中间 Drawable 表示

```csharp
public class TextDrawable : IgesDrawableBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextDrawable](textdrawable/)(string, Point3D, double, double, double, IDrawableProperties) | 创建文本可绘制对象并确定其文本边界 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllPoints](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/allpoints/) { get; } | 定义几何形状的所有点数组 |
| [Childs](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/childs/) { get; } |  |
| [EndBottomLine](../../aspose.cad.fileformats.iges.drawables/textdrawable/endbottomline/) { get; } | 文本边界的右下点，对应 AllPoints[3] |
| [EntityUID](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/entityuid/) { get; set; } |  |
| [Id](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/id/) { get; } |  |
| [Mirrioring](../../aspose.cad.fileformats.iges.drawables/textdrawable/mirrioring/) { get; } | 文本镜像 |
| [Orientation](../../aspose.cad.fileformats.iges.drawables/textdrawable/orientation/) { get; } | 水平或垂直文本 |
| [Origin](../../aspose.cad.fileformats.iges.drawables/textdrawable/origin/) { get; } | 文本边界的左下点，用作原始点，对应 AllPoints[0] |
| [Properties](../../aspose.cad.fileformats.iges.drawables/igesdrawablebase/properties/) { get; } | 几何形状的非几何属性 |
| [Text](../../aspose.cad.fileformats.iges.drawables/textdrawable/text/) { get; } | 文本 |
| [UpperLeft](../../aspose.cad.fileformats.iges.drawables/textdrawable/upperleft/) { get; } | 文本边界的左上点，对应 AllPoints[1] |
| [UpperRight](../../aspose.cad.fileformats.iges.drawables/textdrawable/upperright/) { get; } | 文本边界的右上点，对应 AllPoints[2] |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetNewPropsDrawable](../../aspose.cad.fileformats.iges.drawables/textdrawable/getnewpropsdrawable/)(IDrawableProperties) | 使用当前文本可绘制对象的几何形状和提供的非几何属性创建新的文本可绘制对象 |
| override [GetTransformedDrawable](../../aspose.cad.fileformats.iges.drawables/textdrawable/gettransformeddrawable/)(Point3D[]) | 使用提供的点和当前 Text 可绘制对象的非几何属性创建一个新的 Text 可绘制对象 |

### 另请参阅

* class [IgesDrawableBase](../igesdrawablebase/)
* namespace [Aspose.CAD.FileFormats.Iges.Drawables](../../aspose.cad.fileformats.iges.drawables/)
* assembly [Aspose.CAD](../../)

