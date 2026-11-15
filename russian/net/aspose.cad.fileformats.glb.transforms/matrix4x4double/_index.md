---
title: "Matrix4x4Double Структура"
linktitle: "Matrix4x4Double"
articleTitle: "Matrix4x4Double"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Transforms.Matrix4x4Double структура."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.transforms/matrix4x4double/"
product_version: "26.9"
---
## Matrix4x4Double struct



```csharp
public struct Matrix4x4Double : IEquatable<Matrix4x4Double>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Matrix4x4Double](matrix4x4double/)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Создает Matrix4x4 из заданных компонентов. |

## Свойства

| Имя | Описание |
| --- | --- |
| Identity { get; } | Возвращает мультипликативную единичную матрицу. |

## Методы

| Имя | Описание |
| --- | --- |
| CreateFromQuaternion(Quaternion) | Создает матрицу вращения из заданного значения вращения Quaternion. |
| CreateScale(double, double, double) | Создает матрицу масштабирования. |
| CreateTranslation(double, double, double) | Создает матрицу переноса. |
| Equals(Matrix4x4Double) | Возвращает логическое значение, указывающее, равен ли данный экземпляр матрицы другой переданной матрице. |
| Equals(object) | Возвращает логическое значение, указывающее, равен ли переданный объект этому экземпляру матрицы. |
| GetHashCode() | Возвращает хеш-код этого экземпляра. |
| Invert(Matrix4x4Double, out Matrix4x4Double) | Пытается вычислить обратную матрицу для заданной матрицы. При успешном выполнении результат будет содержать инвертированную матрицу. |
| Multiply(Matrix4x4Double, Matrix4x4Double) | Умножает одну матрицу на другую матрицу. |

## Поля

| Имя | Описание |
| --- | --- |
| M11 | Значение в строке 1, столбце 1 матрицы. |
| M12 | Значение в строке 1, столбце 2 матрицы. |
| M13 | Значение в строке 1, столбце 3 матрицы. |
| M14 | Значение в строке 1, столбце 4 матрицы. |
| M21 | Значение в строке 2, столбце 1 матрицы. |
| M22 | Значение в строке 2, столбце 2 матрицы. |
| M23 | Значение в строке 2, столбце 3 матрицы. |
| M24 | Значение в строке 2, столбце 4 матрицы. |
| M31 | Значение в строке 3, столбце 1 матрицы. |
| M32 | Значение в строке 3, столбце 2 матрицы. |
| M33 | Значение в строке 3, столбце 3 матрицы. |
| M34 | Значение в строке 3, столбце 4 матрицы. |
| M41 | Значение в строке 4, столбце 1 матрицы. |
| M42 | Значение в строке 4, столбце 2 матрицы. |
| M43 | Значение в строке 4, столбце 3 матрицы. |
| M44 | Значение в строке 4, столбце 4 матрицы. |

## Operators

| Имя | Описание |
| --- | --- |
| оператор Matrix4x4 | Преобразует `Matrix4x4Double` в Matrix4x4 |
| оператор Matrix4x4Double | преобразует из Matrix4x4 в `Matrix4x4Double` |
| operator == | Возвращает логическое значение, указывающее, равны ли две заданные матрицы. |
| operator != | Возвращает логическое значение, указывающее, не равны ли две заданные матрицы. |
| оператор * | Умножает одну матрицу на другую матрицу. |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

