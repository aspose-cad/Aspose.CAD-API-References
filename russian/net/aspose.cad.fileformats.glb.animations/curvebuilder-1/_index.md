---
title: "Класс CurveBuilder<T>"
linktitle: "CurveBuilder<T>"
articleTitle: "CurveBuilder<T>"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.Animations.CurveBuilder. Представляет редактируемую кривую элементов T."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.animations/curvebuilder-1/"
keywords: "CurveBuilder<T>, Aspose.CAD.FileFormats.GLB.Animations, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CurveBuilder&lt;T&gt; class

Представляет редактируемую кривую из *T* элементов.

```csharp
public abstract class CurveBuilder<T> : #=zyZjE7ClmmKXThqa5yJUpRyJNXDM8VjCnzcrxdgn_Khjj<T>, 
    ICurveSampler<T>
    where T : struct
```

| Параметр | Описание |
| --- | --- |
| T | Элемент кривой. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Keys](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/keys/) { get; } |  |
| [MaxDegree](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/maxdegree/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Clear](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clear/)() |  |
| abstract [Clone](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clone/)() |  |
| abstract [GetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/getpoint/)(float) | Сэмплирует кривую в заданном *offset*. |
| [RemoveKey](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/removekey/)(float) |  |
| [SetCurve](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setcurve/)(ICurveSampler&lt;T&gt;) |  |
| [SetIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setincomingtangent/)(float, T) | Устанавливает входную касательную к существующей точке. |
| [SetOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setoutgoingtangent/)(float, T) | Устанавливает выходную касательную к существующей точке. |
| [SetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setpoint/)(float, T, bool) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent)(float, params float[]) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent_1)(float, T) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent)(float, params float[]) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent_1)(float, T) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint)(float, params float[]) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint_1)(float, T, bool) |  |

### См. также

* interface [ICurveSampler&lt;T&gt;](../icurvesampler-1/)
* namespace [Aspose.CAD.FileFormats.GLB.Animations](../../aspose.cad.fileformats.glb.animations/)
* assembly [Aspose.CAD](../../)

