---
title: "CifReplacingEncoderFallbackBuffer.Fallback"
linktitle: "回退"
articleTitle: "回退"
second_title: "Aspose.CAD for .NET API 参考"
description: "CifReplacingEncoderFallbackBuffer 方法。当遇到单字符超出输出代码页时调用"
type: docs
weight: 20
url: "/net/aspose.cad/cifreplacingencoderfallbackbuffer/fallback/"
product_version: "26.9"
---
## Fallback(char, int) {#fallback}

当遇到超出输出代码页的单字符时调用

```csharp
public override bool Fallback(char charUnknown, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknown | 字符 | 超出代码页的字符 |
| 索引 | Int32 | 输入字符串中字符的索引 |

### 返回值

如果进行替换则为 true，否则为 false

### 另请参阅

* class [CifReplacingEncoderFallbackBuffer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Fallback(char, char, int) {#fallback_1}

当遇到超出输出代码页的代理对字符时调用

```csharp
public override bool Fallback(char charUnknownHigh, char charUnknownLow, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknownHigh | 字符 | 超出代码页的字符 - 高位代理项 |
| charUnknownLow | 字符 | 超出代码页的字符 - 低位代理项 |
| 索引 | Int32 | 输入字符串中字符的索引 |

### 返回值

如果进行替换则为 true，否则为 false

### 另请参阅

* class [CifReplacingEncoderFallbackBuffer](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

