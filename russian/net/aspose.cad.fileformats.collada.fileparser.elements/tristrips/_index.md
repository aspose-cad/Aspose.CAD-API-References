---
title: Tristrips
second_title: Справочник по Aspose.CAD для .NET API
description: ТРИСТРИПСЫ. Элемент TRISTRIPS предоставляет информацию необходимую для связывания атрибутов вершин вместе а затем организации этих вершин в соединенные треугольники. Каждый треугольник описываемый сеткой имеет три вершины. Первый треугольник формируется из первой второй и третьей вершин Каждый последующий треугольник формируется из текущей вершины повторно используя две предыдущие вершины.
type: docs
weight: 5520
url: /ru/net/aspose.cad.fileformats.collada.fileparser.elements/tristrips/
---
## Tristrips class

ТРИСТРИПСЫ. Элемент TRISTRIPS предоставляет информацию, необходимую для связывания атрибутов вершин вместе, а затем организации этих вершин в соединенные треугольники. Каждый треугольник, описываемый сеткой, имеет три вершины. Первый треугольник формируется из первой, второй и третьей вершин Каждый последующий треугольник формируется из текущей вершины, повторно используя две предыдущие вершины.

```csharp
public class Tristrips : ColladaElement
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Tristrips](tristrips)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/count) { get; set; } | Получает или устанавливает счетчик. Атрибут count указывает количество примитивов треугольной полосы. Обязательный атрибут. |
| [Extra](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/extra) { get; set; } | Получает или устанавливает доп. |
| [Input](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/input) { get; set; } | Получает или устанавливает ввод. Элемент ввода может встречаться любое количество раз. Этот ввод является локальным вводом с атрибутами смещения и установки. |
| [Material](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/material) { get; set; } | Получает или устанавливает материал. Атрибут материала объявляет символ материала. Этот символ привязывается к материалу во время создания экземпляра. Если атрибут материала не указан, результаты освещения и затенения определяются приложением. Необязательный атрибут. |
| [Name](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/name) { get; set; } | Получает или задает имя. Атрибут name представляет собой текстовую строку имени этого элемента. Необязательный атрибут. |
| [Primitives](../../aspose.cad.fileformats.collada.fileparser.elements/tristrips/primitives) { get; set; } | Получает или устанавливает примитивы. Элемент TRISTRIPS может иметь любое количество элементов p. |

### Смотрите также

* class [ColladaElement](../colladaelement)
* пространство имен [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->