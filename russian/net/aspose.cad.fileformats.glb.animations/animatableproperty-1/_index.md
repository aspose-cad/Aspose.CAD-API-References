---
title: "AnimatableProperty<T> Класс"
linktitle: "AnimatableProperty<T>"
articleTitle: "AnimatableProperty<T>"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.GLB.Animations.AnimatableProperty класс. Представляет значение свойства, которое может быть анимировано с использованием ICurveSampler."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.glb.animations/animatableproperty-1/"
keywords: "AnimatableProperty<T>, Aspose.CAD.FileFormats.GLB.Animations, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## AnimatableProperty&lt;T&gt; class

Представляет значение свойства, которое может быть анимировано с использованием `ICurveSampler`.

```csharp
public class AnimatableProperty<T>
    where T : struct
```

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsAnimated](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/isanimated/) { get; } |  |
| [Tracks](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/tracks/) { get; } |  |
| [Value](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/value/) { get; set; } | Получает или задает значение по умолчанию этого экземпляра. Когда анимация отключена или нет доступного трека анимации, будет возвращено это значение. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/clone/)() |  |
| [GetValueAt](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/getvalueat/)(string, float) | Вычисляет значение этого `AnimatableProperty` при заданном *offset* для заданного *track*. |
| [RemoveTrack](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/removetrack/)(string) | Удаляет анимацию *track*. |
| [SetTrack](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/settrack/)(string, ICurveSampler&lt;T&gt;) | Назначает кривую анимации заданному треку. |
| [SetValue](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/setvalue/)(params float[]) |  |
| [UseTrackBuilder](../../aspose.cad.fileformats.glb.animations/animatableproperty-1/usetrackbuilder/)(string) |  |

### См. также

* namespace [Aspose.CAD.FileFormats.GLB.Animations](../../aspose.cad.fileformats.glb.animations/)
* assembly [Aspose.CAD](../../)

