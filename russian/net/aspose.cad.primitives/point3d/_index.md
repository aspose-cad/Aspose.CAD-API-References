---
title: "Point3D класс"
linktitle: "Point3D"
articleTitle: "Point3D"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.Primitives.Point3D класс. Представляет класс для работы с 3D точкой и специальными операциями для неё."
type: docs
weight: 30
url: "/net/aspose.cad.primitives/point3d/"
keywords: "Point3D, Aspose.CAD.Primitives, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Point3D class

Представляет класс для работы с точкой 3D и специальными операциями над ней.

```csharp
public class Point3D : Point2D
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Point3D](point3d/#constructor)() | Инициализирует новый экземпляр класса Point3D |
| [Point3D](point3d/#constructor_1)(double, double) | Инициализирует новый экземпляр класса Point3D |
| [Point3D](point3d/#constructor_2)(double, double, double) | Инициализирует новый экземпляр класса Point3D |
| [Point3D](point3d/#constructor_3)(double, double, double, double) | Инициализирует новый экземпляр класса Point3D |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateArray](../../aspose.cad.primitives/point3d/coordinatearray/) { get; } |  |
| [W](../../aspose.cad.primitives/point3d/w/) { get; set; } | Получает или задает координату W |
| [X](../../aspose.cad.primitives/point2d/x/) { get; set; } | Получает или задает x. |
| [Y](../../aspose.cad.primitives/point2d/y/) { get; set; } | Получает или задает y. |
| [Z](../../aspose.cad.primitives/point3d/z/) { get; set; } | Получает или задает координату Z |

## Методы

| Имя | Описание |
| --- | --- |
| [Copy](../../aspose.cad.primitives/point3d/copy/)() | Создает копию текущей точки |
| static [CrossProduct](../../aspose.cad.primitives/point3d/crossproduct/)(Point3D, Point3D) | Получает векторное произведение точек |
| [Distance](../../aspose.cad.primitives/point2d/distance/)(Point2D) |  |
| [Distance](../../aspose.cad.primitives/point3d/distance/#distance)(Point3D) |  |
| static [Distance](../../aspose.cad.primitives/point3d/distance/#distance_1)(Point3D, Point3D) | Получает расстояние между точками |
| static [DotProduct](../../aspose.cad.primitives/point3d/dotproduct/)(Point3D, Point3D) | Получает скалярное произведение двух векторов. |
| [Equality](../../aspose.cad.primitives/point3d/equality/)(object) | Выполняет реальное сравнение 3D точек |
| override [Equals](../../aspose.cad.primitives/point3d/equals/#equals)(object) | Позволяет сравнивать 3D точки. |
| override [Equals](../../aspose.cad.primitives/point3d/equals/#equals_1)(Point2D) | Переопределяет метод Equals 2D точки, чтобы вызванное сравнение было 3D |
| [EqualsSoft](../../aspose.cad.primitives/point3d/equalssoft/)(object, double) | Позволяет сравнивать 3D точки с указанным порогом. |
| override [GetHashCode](../../aspose.cad.primitives/point3d/gethashcode/)() | Возвращает хеш-код объекта. |
| static [NormalVector](../../aspose.cad.primitives/point3d/normalvector/)(Point3D, Point3D, Point3D) | Получить нормальный вектор плоскости. |
| [Normalize](../../aspose.cad.primitives/point3d/normalize/)() | Нормализует указанное начало. |
| static [Spherical](../../aspose.cad.primitives/point3d/spherical/)(double, double, double) | Получить точку в сферических координатах |
| [operator ==](../../aspose.cad.primitives/point3d/op_equality/) | Позволяет сравнивать 3D точки. |
| [operator !=](../../aspose.cad.primitives/point3d/op_inequality/) | Позволяет сравнивать 3D точки. |
| [operator -](../../aspose.cad.primitives/point3d/op_subtraction/) | Реализует оператор -. |
| [operator +](../../aspose.cad.primitives/point3d/op_addition/) | Реализует оператор +. |
| [operator *](../../aspose.cad.primitives/point3d/op_multiply/) | Реализует оператор *. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Zero](../../aspose.cad.primitives/point3d/zero/) |  |

### См. также

* class [Point2D](../point2d/)
* namespace [Aspose.CAD.Primitives](../../aspose.cad.primitives/)
* assembly [Aspose.CAD](../../)

