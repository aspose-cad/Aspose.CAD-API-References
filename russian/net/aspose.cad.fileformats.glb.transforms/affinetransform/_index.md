---
title: "Структура AffineTransform"
linktitle: "AffineTransform"
articleTitle: "AffineTransform"
second_title: "Aspose.CAD для .NET справка API"
description: "Структура Aspose.CAD.FileFormats.GLB.Transforms.AffineTransform. Представляет аффинное преобразование в 3D‑пространстве, с двумя взаимоисключающими представлениями: Как ..."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.transforms/affinetransform/"
product_version: "26.9"
---
## AffineTransform struct

Представляет аффинное преобразование в 3D‑пространстве с двумя взаимоисключающими представлениями:

Как 4x3 матрица. Когда [`IsMatrix`](./ismatrix/) равно true.

Публично доступно как [`Matrix`](./matrix/).
 
Как цепочка Scale/Rotation/Translation. Когда [`IsSRT`](./issrt/) равно true.

Публично доступно как: [`Scale`](./scale/), [`Rotation`](./rotation/), [`Translation`](./translation/).

```csharp
public struct AffineTransform : IEquatable<AffineTransform>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AffineTransform](affinetransform/)(Vector3?, Quaternion?, Vector3?) | Инициализирует новый экземпляр класса AffineTransform. |

## Свойства

| Имя | Описание |
| --- | --- |
| IsIdentity { get; } |  |
| IsLosslessDecomposable { get; } | Возвращает значение, указывающее, может ли этот трансформ быть разложен в SRT без потери точности. |
| IsMatrix { get; } | Возвращает значение, указывающее, представляет ли этот `AffineTransform` объект Matrix4x4. |
| IsSRT { get; } | Возвращает значение, указывающее, представляет ли этот `AffineTransform` цепочку SRT. |
| IsValid { get; } |  |
| Matrix { get; } | Возвращает преобразование Matrix4x4 текущего `AffineTransform` |
| Rotation { get; } | Возвращает вращение. |
| Scale { get; } | Возвращает масштаб. |
| Translation { get; } | Возвращает трансляцию |

## Методы

| Имя | Описание |
| --- | --- |
| AreGeometricallyEquivalent(ref AffineTransform, ref AffineTransform, float) | Проверяет, представляют ли два трансформа одинаковое геометрическое пространственное преобразование. |
| Blend(AffineTransform[], float[]) |  |
| CreateDecomposed(Matrix4x4) |  |
| CreateFromAny(Matrix4x4?, Vector3?, Quaternion?, Vector3?) |  |
| Equals(AffineTransform) |  |
| Equals(object) |  |
| GetDecomposed() | Если этот объект представляет Matrix4x4, он возвращает разложенное представление. |
| GetHashCode() |  |
| Multiply(ref AffineTransform, ref AffineTransform) | Умножает *a* на *b*. |
| TransformNormal(Vector3, ref AffineTransform) | Преобразует нормаль вектора с помощью указанного преобразования. |
| TryDecompose(out AffineTransform) |  |
| TryDecompose(out Vector3, out Quaternion, out Vector3) |  |
| TryInvert(ref AffineTransform, out AffineTransform) | Инвертирует указанное преобразование. Возвращаемое значение указывает, удалось ли выполнить операцию. |
| WithRotation(Quaternion) |  |
| WithScale(Vector3) |  |
| WithTranslation(Vector3) |  |

## Поля

| Имя | Описание |
| --- | --- |
| Identity |  |

## Operators

| Имя | Описание |
| --- | --- |
| operator AffineTransform |  |
| operator AffineTransform |  |
| operator == |  |
| operator != |  |
| оператор * |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Transforms](../../aspose.cad.fileformats.glb.transforms/)
* assembly [Aspose.CAD](../../)

