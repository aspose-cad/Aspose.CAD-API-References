---
title: TransformationMatrix
second_title: Aspose.CAD for .NET API 参考
description: 表示 3d 变换矩阵
type: docs
weight: 770
url: /zh/net/aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/
---
## TransformationMatrix class

表示 3d 变换矩阵

```csharp
public class TransformationMatrix : ICloneable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TransformationMatrix](transformationmatrix#constructor)() | 初始化[`TransformationMatrix`](../transformationmatrix)class |
| [TransformationMatrix](transformationmatrix#constructor_1)(double[], bool) | 初始化[`TransformationMatrix`](../transformationmatrix)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Matrix](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/matrix) { get; set; } | 获取或设置变换矩阵。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Axonometric](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/axonometric)(double, double) | 轴测投影 |
| static [Copy](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/copy)(TransformationMatrix) | 将一个 TransformationMatrix 复制到另一个。 |
| static [FromAxis](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/fromaxis)(Point3D, Point3D, Point3D) | 从轴。 |
| static [FrontView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/frontview)() | FrontView 矩阵 |
| static [GetWCS](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/getwcs)(Point3D) | WCSs 指定的法线向量。 |
| static [OCStoWCS](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/ocstowcs)(Point3D) | 将 OCS 坐标转换为 WSC |
| static [Perspective](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/perspective)(double, double, double, double, double) | 创建透视矩阵。 |
| static [RotateX](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatex)(double) | 围绕 X 的旋转矩阵 |
| static [RotateY](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatey)(double) | 绕 Y 旋转矩阵 |
| static [RotateZ](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatez)(double) | 绕 Z 旋转矩阵 |
| static [Scale](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/scale)(double, double, double) | 矩阵缩放 |
| static [SideView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/sideview)() | 侧视矩阵 |
| static [TopView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/topview)() | 顶视图矩阵 |
| static [Translate](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/translate)(double, double, double) | 平移矩阵 |
| static [Transpose](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/transpose)(TransformationMatrix) | 执行矩阵的转置。 |
| static [UcsToWcs](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/ucstowcs)(Point3D, Point3D) | Ucses 到 WCS。 |
| [Clone](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/clone)() | 创建一个作为当前实例副本的新对象。 |
| [Determinant](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/determinant)() | 估计矩阵的行列式。 |
| [Invert](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/invert)() | 给定一个 nXn 矩阵 A，求解 n 个线性方程以求 A 的逆。 |
| [VectorMultiply](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/vectormultiply)(double[]) | 对点应用变换 |
| [operator +](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/op_addition) | 对两个矩阵求和。 |
| [operator *](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/op_multiply#op_multiply_1) | 将矩阵乘以值。 (2 operators) |

### 也可以看看

* 命名空间 [Aspose.CAD.Exporters.CadApsEntitiesExporter.CadAps3D](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d)
* 部件 [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->