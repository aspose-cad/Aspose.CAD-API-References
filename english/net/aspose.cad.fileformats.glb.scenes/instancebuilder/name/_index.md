---
title: "InstanceBuilder.Name"
linktitle: "Name"
articleTitle: "Name"
second_title: "Aspose.CAD for .NET API Reference"
description: "InstanceBuilder property. Gets the display text name of this object, or null. ⚠️ DO NOT USE AS AN OBJECT ID ⚠️ see remarks."
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.glb.scenes/instancebuilder/name/"
product_version: "26.9"
---
## InstanceBuilder.Name property

Gets the display text name of this object, or null.
 

**⚠️ DO NOT USE AS AN OBJECT ID ⚠️** see remarks.

```csharp
public string Name { get; }
```

## Remarks

glTF does not define any rule for object names.

 This means that names can be null or non unique.

 So don't use names for anything other than object name display.

 If you need to reference objects by some ID, use lookup tables instead.

### See Also

* class [InstanceBuilder](../)
* namespace [Aspose.CAD.FileFormats.GLB.Scenes](../../../aspose.cad.fileformats.glb.scenes/)
* assembly [Aspose.CAD](../../../)

