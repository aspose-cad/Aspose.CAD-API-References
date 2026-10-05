---
title: "AssocStatus Enum"
linktitle: "AssocStatus"
articleTitle: "AssocStatus"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.Assoc.AssocStatus enum. The status of AssocActions and AssocDependencies"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cad.cadobjects.assoc/assocstatus/"
product_version: "26.9"
---
## AssocStatus enumeration

The status of AssocActions and AssocDependencies

```csharp
public enum AssocStatus
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| IsUpToDateAssocStatus | `0` | Everything is in sync |
| ChangedDirectlyAssocStatus | `1` | Explicitly changed (such as by the user). |
| ChangedTransitivelyAssocStatus | `2` | Changed indirectly due to something else changed. |
| ChangedNoDifferenceAssocStatus | `3` | No real change, only forces to evaluate. |
| FailedToEvaluateAssocStatus | `4` | Unable to evaluate AssocStatus |
| ErasedAssocStatus | `5` | Dependent-on object erased or action is to be erased. |
| SuppressedAssocStatus | `6` | Action evaluation suppressed, treated as if evaluated. |

### See Also

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.Assoc](../../aspose.cad.fileformats.cad.cadobjects.assoc/)
* assembly [Aspose.CAD](../../)

