---
title: "AssocStatus 枚举"
linktitle: "AssocStatus"
articleTitle: "AssocStatus"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.Assoc.AssocStatus 枚举。AssocActions 和 AssocDependencies 的状态。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cad.cadobjects.assoc/assocstatus/"
product_version: "26.9"
---
## AssocStatus enumeration

AssocActions 和 AssocDependencies 的状态

```csharp
public enum AssocStatus
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| IsUpToDateAssocStatus | `0` | 所有内容已同步。 |
| ChangedDirectlyAssocStatus | `1` | 显式更改（例如由用户）。 |
| ChangedTransitivelyAssocStatus | `2` | 因其他更改而间接更改。 |
| ChangedNoDifferenceAssocStatus | `3` | 没有实际更改，仅强制评估。 |
| FailedToEvaluateAssocStatus | `4` | 无法评估 **AssocStatus**。 |
| ErasedAssocStatus | `5` | 被依赖的对象已删除或操作将被删除。 |
| SuppressedAssocStatus | `6` | 操作评估被抑制，视为已评估。 |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.Assoc](../../aspose.cad.fileformats.cad.cadobjects.assoc/)
* assembly [Aspose.CAD](../../)

