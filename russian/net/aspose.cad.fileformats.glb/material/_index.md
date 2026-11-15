---
title: "Класс Material"
linktitle: "Материал"
articleTitle: "Материал"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Material класс. Внешний вид материала примитива."
type: docs
weight: 330
url: "/net/aspose.cad.fileformats.glb/material/"
keywords: "Material, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Material class

Внешний вид материала примитива.

```csharp
public sealed class Material : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Alpha](../../aspose.cad.fileformats.glb/material/alpha/) { get; set; } | Получает или задает [`AlphaMode`](../alphamode/). |
| [AlphaCutoff](../../aspose.cad.fileformats.glb/material/alphacutoff/) { get; set; } | Получает или задает значение [`AlphaCutoff`](./alphacutoff/). |
| [Channels](../../aspose.cad.fileformats.glb/material/channels/) { get; } | Получает коллекцию элементов [`MaterialChannel`](../materialchannel/), доступных в этом экземпляре `Material`. |
| [DoubleSided](../../aspose.cad.fileformats.glb/material/doublesided/) { get; set; } | Получает или задает значение, указывающее, будет ли этот `Material` отрисовываться двусторонним. |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [IndexOfRefraction](../../aspose.cad.fileformats.glb/material/indexofrefraction/) { get; set; } | Получает или задает показатель преломления. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Unlit](../../aspose.cad.fileformats.glb/material/unlit/) { get; } | Получает значение, указывающее, имеет ли этот экземпляр `Material` расширение Unlit. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindChannel](../../aspose.cad.fileformats.glb/material/findchannel/)(string) | Находит экземпляр [`MaterialChannel`](../materialchannel/). |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [InitializePBRMetallicRoughness](../../aspose.cad.fileformats.glb/material/initializepbrmetallicroughness/)(params string[]) | Инициализирует этот экземпляр `Material` атрибутами PBR Metallic Roughness. |
| [InitializePBRSpecularGlossiness](../../aspose.cad.fileformats.glb/material/initializepbrspecularglossiness/)(bool) | Инициализирует этот экземпляр `Material` атрибутами PBR Specular Glossiness. |
| [InitializeUnlit](../../aspose.cad.fileformats.glb/material/initializeunlit/)() | Инициализирует этот экземпляр `Material` атрибутами Unlit. |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

