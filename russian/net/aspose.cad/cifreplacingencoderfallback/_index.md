---
title: CifReplacingEncoderFallback
second_title: Справочник по Aspose.CAD для .NET API
description: Резервный кодировщик который заменяет символы вне кодовой страницы последовательностью CIF
type: docs
weight: 300
url: /ru/net/aspose.cad/cifreplacingencoderfallback/
---
## CifReplacingEncoderFallback class

Резервный кодировщик, который заменяет символы вне кодовой страницы последовательностью CIF

```csharp
public class CifReplacingEncoderFallback : EncoderFallback
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CifReplacingEncoderFallback](cifreplacingencoderfallback)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [MaxCharCount](../../aspose.cad/cifreplacingencoderfallback/maxcharcount) { get; } | Для суррогатной пары из двух символов UTF-16, которые закодированы как две последовательные записи CIF в формате AutoCad (с косой чертой), это 14, поэтому мы возвращаем 14 |

## Методы

| Имя | Описание |
| --- | --- |
| override [CreateFallbackBuffer](../../aspose.cad/cifreplacingencoderfallback/createfallbackbuffer)() | Создает резервный буфер |

### Смотрите также

* пространство имен [Aspose.CAD](../../aspose.cad)
* сборка [Aspose.CAD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
