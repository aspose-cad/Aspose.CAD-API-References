---
title: "Brep.Source"
linktitle: "Source"
articleTitle: "Source"
second_title: "Aspose.CAD for .NET API 参考"
description: "Brep 属性。获取或设置源。source 元素定义顶点、边和面元素对其几何实体的访问。至少..."
type: docs
weight: 50
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/brep/source/"
product_version: "26.9"
---
## Brep.Source property

获取或设置源。
source 元素定义顶点、边和面元素对其几何实体的访问。
至少需要一个 source 元素用于顶点。
如果存在边，则需要第二个 source 元素通过 IDREF_array 访问 curve 元素中的曲线。
如果存在面，则需要第三个 source 元素通过 IDREF_array 访问 surface 元素中的表面。

```csharp
public Source[] Source { get; set; }
```

### 另请参阅

* class [Source](../../source/)
* class [Brep](../)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../../)

