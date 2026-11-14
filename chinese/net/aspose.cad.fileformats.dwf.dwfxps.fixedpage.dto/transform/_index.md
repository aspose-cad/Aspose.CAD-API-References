---
title: "Transform 类"
linktitle: "Transform"
articleTitle: "Transform"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO.Transform 类。该 transform。OpenXPS Document 标记支持通过 R... 表示的仿射变换。"
type: docs
weight: 340
url: "/net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/transform/"
keywords: "Transform, Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Transform class

该 transform。
OpenXPS Document 标记支持通过表达的仿射变换。
RenderTransform 和 Transform 属性。仿射变换表示为
作为六个实数的列表：m11, m12, m21, m22, OffsetX, OffsetY。
RenderTransform 和 Transform 属性都指定仿射矩阵变换
到本地坐标空间，使用 [MatrixTransform](../matrixtransform/) 元素作为其值。
可以使用缩写的矩阵变换语法来指定 RenderTransform 或 Transform 属性值。

```csharp
public class Transform
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Transform](transform/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MatrixTransform](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/transform/matrixtransform/) { get; set; } | 获取或设置矩阵变换。创建任意仿射矩阵变换，以在二维平面中操作对象或坐标系。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Dwf.DwfXps.FixedPage.DTO](../../aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/)
* assembly [Aspose.CAD](../../)

