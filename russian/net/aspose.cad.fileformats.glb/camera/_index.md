---
title: "Класс Camera"
linktitle: "Camera"
articleTitle: "Camera"
second_title: "Aspose.CAD для .NET справка API"
description: "Класс Aspose.CAD.FileFormats.GLB.Camera. Проекция камеры. Узел **MAY** может ссылаться на камеру, чтобы применить преобразование и разместить камеру в сцене."
type: docs
weight: 130
url: "/net/aspose.cad.fileformats.glb/camera/"
keywords: "Camera, Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Camera class

Проекция камеры.
Узел **MAY** может ссылаться на камеру, чтобы применить преобразование и разместить камеру в сцене.

```csharp
public sealed class Camera : LogicalChildOfRoot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extensions](../../aspose.cad.fileformats.glb/extraproperties/extensions/) { get; } | Получает коллекцию экземпляров [`JsonSerializable`](../../aspose.cad.fileformats.glb.io/jsonserializable/). |
| [Extras](../../aspose.cad.fileformats.glb/extraproperties/extras/) { get; set; } | Получает или задает дополнительное содержимое этого экземпляра. |
| [LogicalIndex](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalindex/) { get; } | Получает нулевой индекс этого объекта в логических ресурсах [`GlbData`](../glbdata/). |
| [LogicalParent](../../aspose.cad.fileformats.glb/logicalchildofroot/logicalparent/) { get; } | Получает экземпляр [`GlbData`](../glbdata/), которому принадлежит этот объект. |
| [Matrix](../../aspose.cad.fileformats.glb/camera/matrix/) { get; } | Получает матрицу проекции для текущих [`Settings`](./settings/) |
| [Name](../../aspose.cad.fileformats.glb/logicalchildofroot/name/) { get; set; } | Получает или задает отображаемое текстовое имя или null. |
| [Settings](../../aspose.cad.fileformats.glb/camera/settings/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [GetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/getextension/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)() |  |
| [RemoveExtensions&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/removeextensions/)(T) |  |
| [SetExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/setextension/)(T) |  |
| [SetOrthographicMode](../../aspose.cad.fileformats.glb/camera/setorthographicmode/)(float, float, float, float) | Настраивает этот `Camera` для использования ортографической проекции. |
| [SetPerspectiveMode](../../aspose.cad.fileformats.glb/camera/setperspectivemode/)(float?, float, float, float) | Настраивает этот `Camera` для использования перспективной проекции. |
| [UseExtension&lt;T&gt;](../../aspose.cad.fileformats.glb/extraproperties/useextension/)() |  |

### См. также

* class [LogicalChildOfRoot](../logicalchildofroot/)
* namespace [Aspose.CAD.FileFormats.GLB](../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../)

