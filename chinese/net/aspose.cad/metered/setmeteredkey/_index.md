---
title: "Metered.SetMeteredKey"
linktitle: "SetMeteredKey"
articleTitle: "SetMeteredKey"
second_title: "Aspose.CAD for .NET API 参考"
description: "Metered 方法。设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时，应调用此 API，通常，这已经足够..."
type: docs
weight: 20
url: "/net/aspose.cad/metered/setmeteredkey/"
product_version: "26.9"
---
## Metered.SetMeteredKey method

设置计量的公钥和私钥。
如果您购买了计量许可证，在启动应用程序时，应调用此 API，通常，这已经足够。
但是，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态，
为避免这种情况，您应该定期检查许可证状态，如果它是评估状态，请再次调用此 API。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | String | 公钥 |
| privateKey | String | 私钥 |

### 另请参阅

* class [Metered](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

