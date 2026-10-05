---
title: "License.License"
linktitle: "License"
articleTitle: "License"
second_title: "Aspose.CAD for .NET API Reference"
description: "License constructor. Initializes a new instance of this class."
type: docs
weight: 10
url: "/net/aspose.cad/license/license/"
product_version: "26.9"
---
## License constructor

Initializes a new instance of this class.

```csharp
public License()
```

## Examples

In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains 
 the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
 
 the component jar file:

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### See Also

* class [License](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

