---
title: "AssocStatus Перечисление"
linktitle: "AssocStatus"
articleTitle: "AssocStatus"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.Assoc.AssocStatus enum. Статус AssocActions и AssocDependencies"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cad.cadobjects.assoc/assocstatus/"
product_version: "26.9"
---
## AssocStatus enumeration

Состояние AssocActions и AssocDependencies

```csharp
public enum AssocStatus
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| IsUpToDateAssocStatus | `0` | Все синхронизировано |
| ChangedDirectlyAssocStatus | `1` | Явно изменено (например, пользователем). |
| ChangedTransitivelyAssocStatus | `2` | Изменено косвенно из‑за изменения чего‑то другого. |
| ChangedNoDifferenceAssocStatus | `3` | Фактических изменений нет, только принудительная оценка. |
| FailedToEvaluateAssocStatus | `4` | Не удалось оценить AssocStatus |
| ErasedAssocStatus | `5` | Объект‑зависимость удалён или действие должно быть удалено. |
| SuppressedAssocStatus | `6` | Оценка действия подавлена, считается как выполненная. |

### См. также

* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.Assoc](../../aspose.cad.fileformats.cad.cadobjects.assoc/)
* assembly [Aspose.CAD](../../)

