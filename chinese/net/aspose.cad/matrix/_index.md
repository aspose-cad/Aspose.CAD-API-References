---
title: "Matrix 类"
linktitle: "矩阵"
articleTitle: "矩阵"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Matrix 类。替代 GDI+ Matrix。"
type: docs
weight: 600
url: "/net/aspose.cad/matrix/"
keywords: "Matrix, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Matrix class

替代 GDI+ 矩阵。

```csharp
public class Matrix
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix](matrix/#constructor_1)(Rectangle, Point[]) | 将 `Matrix` 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_2)(RectangleF, PointF[]) | 将 `Matrix` 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_3)(float, float, float, float, float, float) | 初始化 `Matrix` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Elements](../../aspose.cad/matrix/elements/) { get; } | 获取一个浮点值数组，表示此 `Matrix` 的元素。 |
| [M11](../../aspose.cad/matrix/m11/) { get; } | 获取矩阵第一行第一列的元素。表示沿 X 轴的缩放。 |
| [M12](../../aspose.cad/matrix/m12/) { get; } | 获取矩阵第一行第二列的元素。表示沿 Y 轴的剪切。 |
| [M21](../../aspose.cad/matrix/m21/) { get; } | 获取矩阵第二行第一列的元素。表示沿 X 轴的剪切。 |
| [M22](../../aspose.cad/matrix/m22/) { get; } | 获取矩阵第二行第二列的元素。表示沿 Y 轴的缩放。 |
| [M31](../../aspose.cad/matrix/m31/) { get; } | 获取矩阵第三行第一列的元素。表示沿 X 轴的平移。 |
| [M32](../../aspose.cad/matrix/m32/) { get; } | 获取矩阵第三行第一列的元素。表示沿 Y 轴的平移。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.cad/matrix/equals/#equals)(object) | 确定指定的对象是否等于此实例。 |
| static [Equals](../../aspose.cad/matrix/equals/#equals_1)(Matrix, Matrix) | 确定两个矩阵是否相等。 |
| [GetElements](../../aspose.cad/matrix/getelements/)() | 获取矩阵元素的副本。 |
| override [GetHashCode](../../aspose.cad/matrix/gethashcode/)() | 返回此实例的哈希码。 |
| [Multiply](../../aspose.cad/matrix/multiply/#multiply)(Matrix) | 使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [Multiply](../../aspose.cad/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。 |
| [Reset](../../aspose.cad/matrix/reset/)() | 将此 Matrix 重置为具有单位矩阵的元素。 |
| [Rotate](../../aspose.cad/matrix/rotate/#rotate)(float) | 在默认（Prepend）顺序下，对此 Matrix 进行以原点（零 x 和 y 坐标）为中心、角度参数指定的顺时针旋转。 |
| [Rotate](../../aspose.cad/matrix/rotate/#rotate_1)(float, MatrixOrder) | 在指定的顺序下，对此 Matrix 进行以原点（零 x 和 y 坐标）为中心、角度参数指定的顺时针旋转。 |
| [RotateAt](../../aspose.cad/matrix/rotateat/#rotateat)(float, PointF) | 在默认（Prepend）顺序下，对此 Matrix 进行围绕指定点的顺时针旋转。 |
| [RotateAt](../../aspose.cad/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 在指定的顺序下，对此 Matrix 进行围绕指定点的顺时针旋转。 |
| [Scale](../../aspose.cad/matrix/scale/#scale)(float, float) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [Scale](../../aspose.cad/matrix/scale/#scale_1)(float, float, MatrixOrder) | 使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 `Matrix`。 |
| override [ToString](../../aspose.cad/matrix/tostring/)() | 返回表示此实例的字符串。 |
| [TransformPoints](../../aspose.cad/matrix/transformpoints/)(PointF[]) | 将此 `Matrix` 表示的几何变换应用于指定的点数组。 |
| [Translate](../../aspose.cad/matrix/translate/#translate)(float, float) | 使用（默认）Prepend 顺序，将指定的平移向量应用于此 `Matrix`。 |
| [Translate](../../aspose.cad/matrix/translate/#translate_1)(float, float, MatrixOrder) | 在指定的顺序下，将指定的平移向量应用于此 Matrix。 |
| [operator ==](../../aspose.cad/matrix/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.cad/matrix/op_inequality/) | 实现运算符 !=。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeFlip](../../aspose.cad/matrix/typeflip/) | 此标志位表示此对象定义的变换在某轴上执行镜像翻转，除了其他标志位指示的转换外，还会将通常的右手坐标系转换为左手坐标系。右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，类似于右手拇指指向你时手指的卷曲方向。左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，类似于左手拇指指向你时手指的卷曲方向。由于在适当的调整旋转下所有翻转角度相同，无法通过数学方式确定原始翻转或镜像变换的角度。注意：TypeFlip 是在 GENERAL_TRANSFORM 已公开流通后添加的，标志位已无法方便地重新编号，否则会在外部代码中引入二进制不兼容性。 |
| const [TypeGeneralRotation](../../aspose.cad/matrix/typegeneralrotation/) | 此标志位表示此对象定义的变换在执行其他标志位指示的转换之外，还会进行任意角度的旋转。旋转会以相同的量改变向量的角度，无论向量的原始方向如何，且不会改变向量的长度。此标志位与 |
| const [TypeGeneralScale](../../aspose.cad/matrix/typegeneralscale/) | 通用缩放会在 x 和 y 方向上以不同的比例乘以向量的长度，而不改变垂直向量之间的角度。此标志位与 TypeUniformScale 标志互斥。 |
| const [TypeGeneralTransform](../../aspose.cad/matrix/typegeneraltransform/) | 此常量表示此对象定义的变换对输入坐标执行任意转换。如果此变换可以由上述任意常量分类，则其类型将是常量 TypeIdentity，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| const [TypeIdentity](../../aspose.cad/matrix/typeidentity/) | 恒等变换是指输出坐标始终与输入坐标相同的变换。如果此变换不是恒等变换，则其类型将是常量 GENERAL_TRANSFORM，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| const [TypeMaskRotation](../../aspose.cad/matrix/typemaskrotation/) | 此常量是任意旋转标志位的位掩码。 |
| const [TypeMaskScale](../../aspose.cad/matrix/typemaskscale/) | 此常量是任意缩放标志位的位掩码。 |
| const [TypeQuadrantRotation](../../aspose.cad/matrix/typequadrantrotation/) | 此标志位表示此对象定义的变换在执行其他标志位指示的转换之外，还会进行以 90 度的整数倍为单位的象限旋转。旋转会以相同的量改变向量的角度，无论向量的原始方向如何，且不会改变向量的长度。此标志位与 TypeGeneralRotation 标志互斥。 |
| const [TypeTranslation](../../aspose.cad/matrix/typetranslation/) | 平移会在 x 和 y 方向上以恒定量移动坐标，而不改变向量的长度或角度。 |
| const [TypeUniformScale](../../aspose.cad/matrix/typeuniformscale/) | 统一缩放会在 x 和 y 方向上以相同的比例乘以向量的长度，而不改变向量之间的角度。此标志位与 TypeGeneralScale 标志互斥。 |

## 备注

大多数算法取自 Sun 的 AffineTransform.java。
Java 对内部使用的矩阵元素的命名。
Java 名称映射到 .net 名称及其描述：
m00 M11 缩放 X
m10 M12 剪切 Y
m01 M21 剪切 X
m11 M22 缩放 Y
m02 M31 平移 X
m12 M32 平移 Y

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

