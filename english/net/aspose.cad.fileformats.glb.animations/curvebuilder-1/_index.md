---
title: "CurveBuilder<T> Class"
linktitle: "CurveBuilder<T>"
articleTitle: "CurveBuilder<T>"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Animations.CurveBuilder class. Represents an editable curve of T elements."
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.animations/curvebuilder-1/"
keywords: "CurveBuilder<T>, Aspose.CAD.FileFormats.GLB.Animations, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CurveBuilder&lt;T&gt; class

Represents an editable curve of *T* elements.

```csharp
public abstract class CurveBuilder<T> : #=zyZjE7ClmmKXThqa5yJUpRyJNXDM8VjCnzcrxdgn_Khjj<T>, 
    ICurveSampler<T>
    where T : struct
```

| Parameter | Description |
| --- | --- |
| T | An element of the curve. |

## Properties

| Name | Description |
| --- | --- |
| [Keys](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/keys/) { get; } |  |
| [MaxDegree](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/maxdegree/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [Clear](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clear/)() |  |
| abstract [Clone](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clone/)() |  |
| abstract [GetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/getpoint/)(float) | Samples the curve at a given *offset* |
| [RemoveKey](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/removekey/)(float) |  |
| [SetCurve](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setcurve/)(ICurveSampler&lt;T&gt;) |  |
| [SetIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setincomingtangent/)(float, T) | Sets the incoming tangent to an existing point. |
| [SetOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setoutgoingtangent/)(float, T) | Sets the outgoing tangent to an existing point. |
| [SetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setpoint/)(float, T, bool) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent)(float, params float[]) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent_1)(float, T) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent)(float, params float[]) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent_1)(float, T) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint)(float, params float[]) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint_1)(float, T, bool) |  |

### See Also

* interface [ICurveSampler&lt;T&gt;](../icurvesampler-1/)
* namespace [Aspose.CAD.FileFormats.GLB.Animations](../../aspose.cad.fileformats.glb.animations/)
* assembly [Aspose.CAD](../../)

