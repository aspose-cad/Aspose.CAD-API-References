---
title: "Структура Vector3F"
linktitle: "Vector3F"
articleTitle: "Vector3F"
second_title: "Aspose.CAD для .NET справка API"
description: "Структура Aspose.CAD.Vector3F. Вектор с 3 параметрами типа float"
type: docs
weight: 940
url: "/net/aspose.cad/vector3f/"
product_version: "26.9"
---
## Vector3F struct

Вектор с 3 параметрами типа float

```csharp
public struct Vector3F : IEquatable<Vector3F>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Vector3F](vector3f/)(float, float, float) | Инициализирует новый экземпляр структуры `Vector3F`. |

## Свойства

| Имя | Описание |
| --- | --- |
| B { get; set; } | Компонент Blue |
| G { get; set; } | Компонент Green |
| Item { get; } | Получает координату по указанному индексу. |
| Length { get; } | Length |
| R { get; set; } | Компонент Red |
| SquareLength { get; } | Квадратная длина |

## Методы

| Имя | Описание |
| --- | --- |
| CrossProduct(Vector3F, Vector3F) | Возвращает векторное произведение двух векторов. |
| DotProduct(Vector3F, Vector3F) | Возвращает скалярное произведение двух векторов. |
| Equals(object) | Возвращает логическое значение, указывающее, равен ли заданный объект этому экземпляру Vector3F. |
| Equals(Vector3F) | Возвращает логическое значение, указывающее, равен ли заданный Vector3F этому экземпляру Vector3F. |
| GetHashCode() | Возвращает хеш-код этого экземпляра. |
| NewellFaceNormal(List&lt;Vector3F&gt;, List&lt;int&gt;) | Вычисляет нормаль грани методом Ньюэлла. |
| Normalized() | Создаёт нормализованный вектор. |
| Reflect(Vector3F, Vector3F) | Вычисляет отражённый вектор. |
| SafeNormalized() | Создаёт нормализованный вектор безопасно (возвращает себя, если длина равна нулю). |
| To2F() | Создает Vector2F. |
| ToVector4F(float) | Создаёт Vector4F. |
| XAxis() | Создаёт ось X. |
| YAxis() | Создаёт ось Y. |
| ZAxis() | Создаёт ось Z. |
| Zero() | Создает вектор с (0, 0, 0). |

## Поля

| Имя | Описание |
| --- | --- |
| X | Координата X |
| Y | Координата Y |
| Z | Координата Z |

## Operators

| Имя | Описание |
| --- | --- |
| operator == | Возвращает логическое значение, указывающее, равны ли два заданных вектора. |
| operator != | Возвращает логическое значение, указывающее, не равны ли два заданных вектора. |
| operator - | Инвертирует заданный вектор. |
| operator - | Вычитает второй вектор из первого. |
| operator + | Складывает два вектора. |
| оператор * | Умножает вектор на скалярное значение. |
| оператор * | Умножает вектор на скалярное значение. |
| оператор * | Вычитает второй вектор из первого. |

### См. также

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

