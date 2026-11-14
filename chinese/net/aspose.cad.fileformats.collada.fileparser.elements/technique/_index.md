---
title: "Technique 类"
linktitle: "Technique"
articleTitle: "Technique"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Collada.FileParser.Elements.Technique 类。该 technique。technique 元素声明用于处理部分内容的信息。"
type: docs
weight: 1200
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/technique/"
keywords: "Technique, Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Technique class

该技术。
technique 元素声明用于处理内容某部分的信息。
每个 technique 符合关联的配置文件。Techniques 通常充当“开关”。
如果针对特定内容部分存在多个，则在导入时会选择其一，但通常不会同时选择两个。
应根据导入应用程序能够支持的配置文件进行选择。
Techniques 包含应用数据和程序，使其成为可以作为整体管理的资产。

```csharp
public class Technique : ColladaElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Technique](technique/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Profile](../../aspose.cad.fileformats.collada.fileparser.elements/technique/profile/) { get; set; } | 获取或设置配置文件。profile 属性指示配置文件的类型。这是供应商定义的字符串，用于指示技术的平台或能力目标。此属性为必需。 |

### 另请参阅

* class [ColladaElement](../colladaelement/)
* namespace [Aspose.CAD.FileFormats.Collada.FileParser.Elements](../../aspose.cad.fileformats.collada.fileparser.elements/)
* assembly [Aspose.CAD](../../)

