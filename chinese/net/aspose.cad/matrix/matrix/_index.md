---
title: "Matrix.Matrix"
linktitle: "矩阵"
articleTitle: "矩阵"
second_title: "Aspose.CAD for .NET API 参考"
description: "Matrix 构造函数。将 Matrix 类的新实例初始化为单位矩阵。"
type: docs
weight: 10
url: "/net/aspose.cad/matrix/matrix/"
product_version: "26.9"
---
## Matrix() {#constructor}

将 Matrix 类的新实例初始化为单位矩阵。

```csharp
public Matrix()
```

### 另请参阅

* class [Matrix](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_1}

将 [`Matrix`](../) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 一个表示待变换矩形的 [`Rectangle`](../../../aspose.cad/rectangle/) 结构。 |
| plgpts | Point[] | 一个包含三个 [`Point`](../../../aspose.cad/point/) 结构的数组，表示用于将矩形的左上、右上和左下角变换到的平行四边形的点。平行四边形的右下角由前三个角隐含。 |

### 另请参阅

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_2}

将 [`Matrix`](../) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 一个表示待变换矩形的 [`RectangleF`](../../../aspose.cad/rectanglef/) 结构。 |
| plgpts | PointF[] | 一个包含三个 [`PointF`](../../../aspose.cad/pointf/) 结构的数组，表示用于将矩形的左上、右上和左下角变换到的平行四边形的点。平行四边形的右下角由前三个角隐含。 |

### 另请参阅

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_3}

将 [`Matrix`](../) 类的新实例初始化。

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | Single | m00 M11 缩放 X |
| m12 | Single | m10 M12 剪切 Y |
| m21 | Single | m01 M21 剪切 X |
| m22 | Single | m11 M22 缩放 Y |
| m31 | Single | m02 M31 平移 X |
| m32 | Single | m12 M32 平移 Y |

### 另请参阅

* class [Matrix](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

