---
title: "GlbData.ApplyBasisTransform"
linktitle: "ApplyBasisTransform"
articleTitle: "ApplyBasisTransform"
second_title: "Aspose.CAD для .NET справка API"
description: "Метод GlbData. Применяет мировое преобразование ко всем сценам модели."
type: docs
weight: 220
url: "/net/aspose.cad.fileformats.glb/glbdata/applybasistransform/"
product_version: "26.9"
---
## GlbData.ApplyBasisTransform method

Применяет мировое преобразование ко всем сценам модели.

```csharp
public void ApplyBasisTransform(Matrix4x4 basisTransform, string basisNodeName = "BasisTransform")
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| basisTransform | Matrix4x4 | Преобразование для применения. |
| basisNodeName | String | Имя нового корневого узла, если его нужно создать. |

## Примечания

Этот метод подходит для применения общего изменения оси или масштаба ко всей модели.
Анимации сохраняются путем инкапсуляции анимированных узлов внутри главного базового трансформационного узла.
Тем временем, неанимированные узлы преобразуются напрямую.
Если определитель *basisTransform* отрицательный, отсечение граней должно быть
перевёрнуто при рендеринге.

### См. также

* class [GlbData](../)
* namespace [Aspose.CAD.FileFormats.GLB](../../../aspose.cad.fileformats.glb/)
* assembly [Aspose.CAD](../../../)

