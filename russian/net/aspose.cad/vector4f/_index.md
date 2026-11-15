---
title: "Структура Vector4F"
linktitle: "Vector4F"
articleTitle: "Vector4F"
second_title: "Aspose.CAD для .NET справка API"
description: "Структура Aspose.CAD.Vector4F. Вектор с 4 параметрами типа float"
type: docs
weight: 950
url: "/net/aspose.cad/vector4f/"
product_version: "26.9"
---
## Vector4F struct

Вектор с 4 параметрами типа float

```csharp
public struct Vector4F : IEquatable<Vector4F>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Vector4F](vector4f/)(float) | Инициализирует новый экземпляр структуры `Vector4F`. |

## Свойства

| Имя | Описание |
| --- | --- |
| A { get; set; } | Компонент Alpha |
| B { get; set; } | Компонент Blue |
| G { get; set; } | Компонент Green |
| Item { get; } | Получает координату по указанному индексу. |
| Length { get; } | Length |
| R { get; set; } | Компонент Red |
| SquareLength { get; } | Квадратная длина |

## Методы

| Имя | Описание |
| --- | --- |
| Equals(object) | Возвращает логическое значение, указывающее, равен ли переданный объект этому экземпляру Vector4F. |
| Equals(Vector4F) | Возвращает логическое значение, указывающее, равен ли переданный Vector4F этому экземпляру Vector4F. |
| GetHashCode() | Возвращает хеш-код этого экземпляра. |
| Normalized() | Создаёт нормализованный вектор. |
| SafeNormalized() | Создаёт нормализованный вектор безопасно (возвращает себя, если длина равна нулю). |
| ToVector2F() | Создает Vector2F. |
| ToVector3F() | Создает Vector3F. |
| Zero() | Создает вектор с (0, 0, 0). |

## Поля

| Имя | Описание |
| --- | --- |
| W | Координата W |
| X | Координата X |
| Y | Координата Y |
| Z | Координата Z |

## Operators

| Имя | Описание |
| --- | --- |
| operator == | Возвращает логическое значение, указывающее, равны ли два заданных вектора. |
| operator != | Возвращает логическое значение, указывающее, не равны ли два заданных вектора. |
| operator - | Вычитает второй вектор из первого. |
| operator + | Складывает два вектора. |
| оператор * | Умножает вектор на скалярное значение. |
| оператор / | Делит вектор на скалярное значение. |

### См. также

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

