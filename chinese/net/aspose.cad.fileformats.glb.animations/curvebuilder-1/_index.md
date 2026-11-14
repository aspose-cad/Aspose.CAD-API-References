---
title: "CurveBuilder<T> 类"
linktitle: "CurveBuilder<T>"
articleTitle: "CurveBuilder<T>"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Animations.CurveBuilder 类。表示由 T 元素组成的可编辑曲线。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.glb.animations/curvebuilder-1/"
keywords: "CurveBuilder<T>, Aspose.CAD.FileFormats.GLB.Animations, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CurveBuilder&lt;T&gt; class

表示具有 *T* 元素的可编辑曲线。

```csharp
public abstract class CurveBuilder<T> : #=zyZjE7ClmmKXThqa5yJUpRyJNXDM8VjCnzcrxdgn_Khjj<T>, 
    ICurveSampler<T>
    where T : struct
```

| 参数 | 描述 |
| --- | --- |
| T | 曲线的一个元素。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Keys](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/keys/) { get; } |  |
| [MaxDegree](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/maxdegree/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clear](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clear/)() |  |
| abstract [Clone](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/clone/)() |  |
| abstract [GetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/getpoint/)(float) | 在给定的 *offset* 处对曲线进行采样 |
| [RemoveKey](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/removekey/)(float) |  |
| [SetCurve](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setcurve/)(ICurveSampler&lt;T&gt;) |  |
| [SetIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setincomingtangent/)(float, T) | 将入切线设置为已有点。 |
| [SetOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setoutgoingtangent/)(float, T) | 将出切线设置为已有点。 |
| [SetPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/setpoint/)(float, T, bool) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent)(float, params float[]) |  |
| [WithIncomingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withincomingtangent/#withincomingtangent_1)(float, T) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent)(float, params float[]) |  |
| [WithOutgoingTangent](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withoutgoingtangent/#withoutgoingtangent_1)(float, T) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint)(float, params float[]) |  |
| [WithPoint](../../aspose.cad.fileformats.glb.animations/curvebuilder-1/withpoint/#withpoint_1)(float, T, bool) |  |

### 另请参阅

* interface [ICurveSampler&lt;T&gt;](../icurvesampler-1/)
* namespace [Aspose.CAD.FileFormats.GLB.Animations](../../aspose.cad.fileformats.glb.animations/)
* assembly [Aspose.CAD](../../)

