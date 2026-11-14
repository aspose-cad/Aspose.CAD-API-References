---
title: "Material 类"
linktitle: "材质"
articleTitle: "材质"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.GLB.Material 类。原始体的材质外观。"
type: docs
weight: 330
url: "/net/aspose.cad.fileformats.glb/material/"
keywords: "Material, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Material class

原语的材质外观。

```csharp
public sealed class Material : LogicalChildOfRoot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alpha](../../aspose.cad.fileformats.glb/material/alpha/) { get; set; } | 获取或设置 [`AlphaMode`](../alphamode/)。 |
| [AlphaCutoff](../../aspose.cad.fileformats.glb/material/alphacutoff/) { get; set; } | 获取或设置 [`AlphaCutoff`](./alphacutoff/) 值。 |
| [Channels](../../aspose.cad.fileformats.glb/material/channels/) { get; } | 获取此 `Material` 实例中可用的 [`MaterialChannel`](../materialchannel/) 元素集合。 |
| [DoubleSided](../../aspose.cad.fileformats.glb/material/doublesided/) { get; set; } | 获取或设置一个值，指示此 `Material` 是否以双面方式渲染。 |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | 获取一组 [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/) 实例。 |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | 获取或设置此实例的 extras 内容。 |
| [IndexOfRefraction](../../aspose.cad.fileformats.glb/material/indexofrefraction/) { get; set; } | 获取或设置折射率。 |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | 获取此对象在 [`GlbData`](../glbdata/) 的逻辑资源中的零基索引。 |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | 获取拥有此对象的 [`GlbData`](../glbdata/) 实例。 |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | 获取或设置显示文本名称，或 null。 |
| [Unlit](../../aspose.cad.fileformats.glb/material/unlit/) { get; } | 获取一个值，指示此 `Material` 实例是否具有 Unlit 扩展。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindChannel](../../aspose.cad.fileformats.glb/material/findchannel/)(string) | 查找 [`MaterialChannel`](../materialchannel/) 的实例。 |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [InitializePBRMetallicRoughness](../../aspose.cad.fileformats.glb/material/initializepbrmetallicroughness/)(params string[]) | 使用 PBR 金属粗糙度属性初始化此 `Material` 实例。 |
| [InitializePBRSpecularGlossiness](../../aspose.cad.fileformats.glb/material/initializepbrspecularglossiness/)(bool) | 使用 PBR 镜面光泽属性初始化此 `Material` 实例。 |
| [InitializeUnlit](../../aspose.cad.fileformats.glb/material/initializeunlit/)() | 使用 Unlit 属性初始化此 `Material` 实例。 |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### 另请参阅

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

