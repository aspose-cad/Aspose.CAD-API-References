---
title: "CadMaterialMap 类"
linktitle: "CadMaterialMap"
articleTitle: "CadMaterialMap"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadMaterialMap 类。表示一个材料组件映射，定义纹理来源并控制其投射方式..."
type: docs
weight: 930
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/"
keywords: "CadMaterialMap, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadMaterialMap class

表示材质组件映射，定义纹理来源并控制其在对象表面上的投影、平铺和变换方式。

```csharp
public class CadMaterialMap
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadMaterialMap](cadmaterialmap/)() | 初始化 `CadMaterialMap` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoTransform](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/autotransform/) { get; set; } | 映射器的自动变换模式。多个值可以使用逻辑或进行组合。 |
| [BlendFactor](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/blendfactor/) { get; set; } | 图像映射的混合因子，范围在 0.0 到 1.0 之间。 |
| [FileName](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/filename/) { get; set; } | 用作映射源的图像文件路径。 |
| [Projection](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/projection/) { get; set; } | 映射投影，在将映射应用于表面时使用。 |
| [Source](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/source/) { get; set; } | 材料映射的数据源。 |
| [Tiling](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/tiling/) { get; set; } | 映射投射到表面时使用的平铺方式。 |
| [TransformMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/transformmatrix/) { get; set; } | 映射器的变换矩阵，以 16 个值的平面列表存储。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [IdentityMatrix](../../aspose.cad.fileformats.cad.cadobjects/cadmaterialmap/identitymatrix/) | 单位变换矩阵：无旋转、无缩放、无平移。当 [`TransformMatrix`](./transformmatrix/) 未恰好包含 16 个值时，作为回退使用。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

