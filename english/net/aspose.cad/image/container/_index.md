---
title: "Image.Container"
linktitle: "Container"
articleTitle: "Container"
second_title: "Aspose.CAD for .NET API Reference"
description: "Image property. Gets the Image container."
type: docs
weight: 200
url: "/net/aspose.cad/image/container/"
product_version: "26.9"
---
## Image.Container property

Gets the [`Image`](../) container.

```csharp
public Image Container { get; }
```

### Property Value

The [`Image`](../) container.

## Remarks

If this property is not null it indicates the image is contained whithin another image.

## Examples

Gets root (top-level) drawing where current drawing is nested in

```csharp
Image drawing = ...
while (drawing.Container != null)
{
    drawing = drawing.Container;
}
```

### See Also

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

