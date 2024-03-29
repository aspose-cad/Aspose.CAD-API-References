---
title: TransformationMatrix
second_title: Справочник по Aspose.CAD для .NET API
description: Представляет матрицу трехмерного преобразования
type: docs
weight: 770
url: /ru/net/aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/
---
## TransformationMatrix class

Представляет матрицу трехмерного преобразования

```csharp
public class TransformationMatrix : ICloneable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransformationMatrix](transformationmatrix#constructor)() | Инициализирует новый экземпляр[`TransformationMatrix`](../transformationmatrix)class |
| [TransformationMatrix](transformationmatrix#constructor_1)(double[], bool) | Инициализирует новый экземпляр класса[`TransformationMatrix`](../transformationmatrix). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Matrix](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/matrix) { get; set; } | Получает или задает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Axonometric](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/axonometric)(double, double) | Аксонометрическая проекция |
| static [Copy](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/copy)(TransformationMatrix) | Выполняет копирование одной TransformationMatrix в другую. |
| static [FromAxis](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/fromaxis)(Point3D, Point3D, Point3D) | От оси. |
| static [FrontView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/frontview)() | Матрица FrontView |
| static [GetWCS](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/getwcs)(Point3D) | WCSs указанный вектор нормали. |
| static [OCStoWCS](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/ocstowcs)(Point3D) | Преобразует координаты OCS в WSC |
| static [Perspective](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/perspective)(double, double, double, double, double) | Создает матрицу перспективы. |
| static [RotateX](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatex)(double) | Матрица вращения вокруг X |
| static [RotateY](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatey)(double) | Матрица вращения вокруг оси Y |
| static [RotateZ](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/rotatez)(double) | Матрица вращения вокруг Z |
| static [Scale](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/scale)(double, double, double) | Масштабирование матрицы |
| static [SideView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/sideview)() | Матрица бокового обзора |
| static [TopView](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/topview)() | Матрица TopView |
| static [Translate](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/translate)(double, double, double) | Матрица перевода |
| static [Transpose](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/transpose)(TransformationMatrix) | Выполняет транспонирование матрицы. |
| static [UcsToWcs](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/ucstowcs)(Point3D, Point3D) | Ucses to WCS. |
| [Clone](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/clone)() | Создает новый объект, являющийся копией текущего экземпляра. |
| [Determinant](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/determinant)() | Оценивает определитель матрицы. |
| [Invert](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/invert)() | Для матрицы A размера nXn решить n линейных уравнений, чтобы найти обратную матрицу A. |
| [VectorMultiply](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/vectormultiply)(double[]) | Применяет преобразование к точке |
| [operator +](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/op_addition) | Выполняет суммирование двух матриц. |
| [operator *](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d/transformationmatrix/op_multiply#op_multiply_1) | Умножает матрицу на значение. (2 operators) |

### Смотрите также

* пространство имен [Aspose.CAD.Exporters.CadApsEntitiesExporter.CadAps3D](../../aspose.cad.exporters.cadapsentitiesexporter.cadaps3d)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
