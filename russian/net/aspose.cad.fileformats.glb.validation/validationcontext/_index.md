---
title: "ValidationContext Структура"
linktitle: "ValidationContext"
articleTitle: "ValidationContext"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Validation.ValidationContext структура. Вспомогательный класс, используемый в процессе проверки модели."
type: docs
weight: 80
url: "/net/aspose.cad.fileformats.glb.validation/validationcontext/"
product_version: "26.9"
---
## ValidationContext struct

Вспомогательный класс, используемый в процессе проверки модели.

```csharp
public struct ValidationContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ValidationContext](validationcontext/)(ValidationResult) | Инициализирует новый экземпляр класса ValidationContext. |

## Свойства

| Имя | Описание |
| --- | --- |
| Root { get; } |  |
| TryFix { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| AreEqual(ValueLocation, TValue, TValue) |  |
| AreJoints(ValueLocation, IList&lt;Vector4&gt;, int) |  |
| AreNormals(ValueLocation, IList&lt;Vector3&gt;) |  |
| ArePositions(ValueLocation, IList&lt;Vector3&gt;) |  |
| AreRotations(ValueLocation, IList&lt;Quaternion&gt;) |  |
| AreSameReference(ValueLocation, TRef, TRef) |  |
| AreTangents(ValueLocation, IList&lt;Vector4&gt;) |  |
| ПеречисленияРавны(ValueLocation, TValue, TValue) |  |
| ПолучитьКонтекст(JsonSerializable) |  |
| ЯвляетсяЛюбымИз(ValueLocation, AttributeFormat, params AttributeFormat[]) |  |
| ЯвляетсяЛюбымИз(ValueLocation, T, params T[]) |  |
| ПоУмолчаниюИлиВДиапазоне(ValueLocation, TValue?, TValue, TValue) |  |
| Определено(ValueLocation, T) |  |
| Определено(ValueLocation, T?) |  |
| Больше(ValueLocation, TValue, TValue) |  |
| БольшеИлиРавно(ValueLocation, TValue, TValue) |  |
| ВДиапазоне(ValueLocation, T, T, T) |  |
| ЯвляетсяJSONСериализуемым(ValueLocation, object) |  |
| Меньше(ValueLocation, TValue, TValue) |  |
| МеньшеИлиРавно(ValueLocation, TValue, TValue) |  |
| ЯвляетсяМатрицей(ValueLocation, ref Matrix4x4, bool, bool) |  |
| ЯвляетсяМатрицей4x3(ValueLocation, ref Matrix4x4, bool, bool) |  |
| Кратно(ValueLocation, int, int) |  |
| Нормально(ValueLocation, ref Vector3, ExceptionSeverity) |  |
| НулевойИлиВДиапазоне(ValueLocation, int?, int, IReadOnlyList&lt;T&gt;) |  |
| НулевойИлиИндекс(ValueLocation, int?, IReadOnlyList&lt;T&gt;) |  |
| НулевойИлиМатрица(ValueLocation, Matrix4x4?, bool, bool) |  |
| НулевойИлиМатрица4x3(ValueLocation, Matrix4x4?, bool, bool) |  |
| НулевойИлиДействительныйURI(ValueLocation, string, params string[]) |  |
| Позиция(ValueLocation, ref Vector3) |  |
| Вращение(ValueLocation, ref Quaternion) |  |
| НаборКоллекция(ValueLocation, IEnumerable&lt;T&gt;) |  |
| IsTrue(ValueLocation, bool, string, ExceptionSeverity) |  |
| IsUndefined(ValueLocation, T) |  |
| IsUndefined(ValueLocation, T?) |  |
| IsValidURI(ValueLocation, string, params string[]) |  |
| MustBeNull(ValueLocation, object) |  |
| NonNegative(ValueLocation, int?) |  |
| NotNull(ValueLocation, object) |  |
| That(Action) |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Validation](../../aspose.cad.fileformats.glb.validation/)
* assembly [Aspose.CAD](../../)

