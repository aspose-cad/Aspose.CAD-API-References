---
title: "CifReplacingEncoderFallback Class"
linktitle: "CifReplacingEncoderFallback"
articleTitle: "CifReplacingEncoderFallback"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.CifReplacingEncoderFallback class. Encoder fallback that replaces out of codepage characters with CIF sequence"
type: docs
weight: 60
url: "/net/aspose.cad/cifreplacingencoderfallback/"
keywords: "CifReplacingEncoderFallback, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CifReplacingEncoderFallback class

Encoder fallback that replaces out of codepage characters with CIF sequence

```csharp
public class CifReplacingEncoderFallback : EncoderFallback
```

## Constructors

| Name | Description |
| --- | --- |
| [CifReplacingEncoderFallback](cifreplacingencoderfallback/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [MaxCharCount](../../aspose.cad/cifreplacingencoderfallback/maxcharcount/) { get; } | For surrogate pair of two UTF-16 characters that are encoded as two consequent CIF entries in AutoCad format (slash-escaped) it is 14, so we return 14 |

## Methods

| Name | Description |
| --- | --- |
| override [CreateFallbackBuffer](../../aspose.cad/cifreplacingencoderfallback/createfallbackbuffer/)() | Creates the actual fallback buffer |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

