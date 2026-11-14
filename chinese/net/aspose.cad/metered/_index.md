---
title: "计量类"
linktitle: "计量"
articleTitle: "计量"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.Metered 类。提供设置计量密钥的方法。"
type: docs
weight: 620
url: "/net/aspose.cad/metered/"
keywords: "Metered, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 示例

在此示例中，将尝试设置计量公钥和私钥
组件 jar 文件：

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetProductName](../../aspose.cad/metered/getproductname/)() |  |
| static [IsMeteredLicensed](../../aspose.cad/metered/ismeteredlicensed/)() | 检查计量是否已授权 |
| [SetMeteredKey](../../aspose.cad/metered/setmeteredkey/)(string, string) | 设置计量公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传使用数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

