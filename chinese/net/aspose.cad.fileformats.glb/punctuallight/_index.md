---
title: "PunctualLight 类"
linktitle: "PunctualLight"
articleTitle: "PunctualLight"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.PunctualLight 类。方向光、点光或聚光灯。"
type: docs
weight: 430
url: "/net/aspose.cad.fileformats.glb/punctuallight/"
keywords: "PunctualLight, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## PunctualLight class

方向光、点光或聚光灯。

```csharp
public sealed class PunctualLight : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.cad.fileformats.glb/punctuallight/color/) { get; set; } | 获取或设置光在线性空间中的 RGB 颜色值。 |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [InnerConeAngle](../../aspose.cad.fileformats.glb/punctuallight/innerconeangle/) { get; } | 获取聚光灯中心开始衰减的角度（弧度）。必须大于或等于 0 且小于 *outerConeAngle*。 |
| [Intensity](../../aspose.cad.fileformats.glb/punctuallight/intensity/) { get; set; } | 获取或设置光的 Brightness。此属性的单位取决于光的类型。点光和聚光灯使用坎德拉（lm/sr）的光强，而方向光使用勒克斯（lm/m2）的照度。 |
| [LightType](../../aspose.cad.fileformats.glb/punctuallight/lighttype/) { get; } | 获取光的类型。 |
| static [LocalDirection](../../aspose.cad.fileformats.glb/punctuallight/localdirection/) { get; } | 获取本地光方向。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [OuterConeAngle](../../aspose.cad.fileformats.glb/punctuallight/outerconeangle/) { get; } | 获取角度（以弧度为单位），该角度是从聚光灯中心到衰减结束处的角度。必须大于 innerConeAngle 且小于或等于 PI / 2.0。 |
| [Range](../../aspose.cad.fileformats.glb/punctuallight/range/) { get; set; } | 获取或设置一个 Hint，定义光强被视为为零的距离截断。仅支持点光和聚光灯。当未定义时，范围被视为无限。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetColor](../../aspose.cad.fileformats.glb/punctuallight/setcolor/)(Vector3, float, float) | 为当前 `PunctualLight` 定义光的颜色、强度和范围。 |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetSpotCone](../../aspose.cad.fileformats.glb/punctuallight/setspotcone/)(float, float) | 设置 Spot 光的锥角。 |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

