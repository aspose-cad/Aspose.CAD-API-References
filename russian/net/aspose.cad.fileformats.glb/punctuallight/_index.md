---
title: "Класс PunctualLight"
linktitle: "PunctualLight"
articleTitle: "PunctualLight"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.PunctualLight. Направленный, точечный или прожекторный свет."
type: docs
weight: 430
url: "/net/aspose.cad.fileformats.glb/punctuallight/"
keywords: "PunctualLight, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PunctualLight class

Направленный, точечный или прожекторный свет.

```csharp
public sealed class PunctualLight : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.cad.fileformats.glb/punctuallight/color/) { get; set; } | Получает или задает значение RGB для цвета света в линейном пространстве. |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [InnerConeAngle](../../aspose.cad.fileformats.glb/punctuallight/innerconeangle/) { get; } | Получает угол в радианах от центра прожектора, где начинается падение. Должен быть больше или равен 0 и меньше outerConeAngle. |
| [Intensity](../../aspose.cad.fileformats.glb/punctuallight/intensity/) { get; set; } | Получает или задает яркость света. Единицы измерения зависят от типа света. Точечные и прожекторные источники используют световую интенсивность в канделах (lm/sr), а направленные источники — освещённость в люксах (lm/m2). |
| [LightType](../../aspose.cad.fileformats.glb/punctuallight/lighttype/) { get; } | Получает тип света. |
| static [LocalDirection](../../aspose.cad.fileformats.glb/punctuallight/localdirection/) { get; } | Получает локальное направление света. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [OuterConeAngle](../../aspose.cad.fileformats.glb/punctuallight/outerconeangle/) { get; } | Получает угол в радианах от центра прожектора, где заканчивается падение. Должен быть больше innerConeAngle и меньше или равен PI / 2.0. |
| [Range](../../aspose.cad.fileformats.glb/punctuallight/range/) { get; set; } | Получает или задает подсказку, определяющую предельное расстояние, при котором интенсивность света считается равной нулю. Поддерживается только для точечных и прожекторных источников. Если не указано, диапазон считается бесконечным. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetColor](../../aspose.cad.fileformats.glb/punctuallight/setcolor/)(Vector3, float, float) | Определяет цвет света, интенсивность и диапазон для текущего `PunctualLight`. |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetSpotCone](../../aspose.cad.fileformats.glb/punctuallight/setspotcone/)(float, float) | Устанавливает углы конуса для Spot‑света. |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

