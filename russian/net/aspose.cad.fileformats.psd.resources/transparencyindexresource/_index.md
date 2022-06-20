---
title: TransparencyIndexResource
second_title: Справочник по Aspose.CAD для .NET API
description: Блок ресурсов индекса прозрачности.
type: docs
weight: 28850
url: /ru/net/aspose.cad.fileformats.psd.resources/transparencyindexresource/
---
## TransparencyIndexResource class

Блок ресурсов индекса прозрачности.

```csharp
public sealed class TransparencyIndexResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransparencyIndexResource](transparencyindexresource)() | Инициализирует новый экземпляр класса[`TransparencyIndexResource`](../transparencyindexresource). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.cad.fileformats.psd.resources/transparencyindexresource/datasize) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.cad.fileformats.psd/resourceblock/id) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.cad.fileformats.psd.resources/transparencyindexresource/minimalversion) { get; } | Получает минимальную требуемую версию psd. |
| [Name](../../aspose.cad.fileformats.psd/resourceblock/name) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы размер был четным (нулевое имя состоит из двух байтов, равных 0). |
| [Signature](../../aspose.cad.fileformats.psd/resourceblock/signature) { get; } | Получает подпись ресурса. Должно быть всегда «8BIM». |
| [Size](../../aspose.cad.fileformats.psd/resourceblock/size) { get; } | Получает размер блока ресурса в байтах, включая его данные. |
| [TransparencyIndex](../../aspose.cad.fileformats.psd.resources/transparencyindexresource/transparencyindex) { get; set; } | Получает или задает индекс цвета прозрачности. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.cad.fileformats.psd/resourceblock/save)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.cad.fileformats.psd/resourceblock/validatevalues)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.cad.fileformats.psd/resourceblock)
* пространство имен [Aspose.CAD.FileFormats.Psd.Resources](../../aspose.cad.fileformats.psd.resources)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->