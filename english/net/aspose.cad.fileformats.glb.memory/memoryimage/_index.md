---
title: "MemoryImage Struct"
linktitle: "MemoryImage"
articleTitle: "MemoryImage"
second_title: "Aspose.CAD for .NET API Reference"
description: "Aspose.CAD.FileFormats.GLB.Memory.MemoryImage struct. Represents an image file stored as an in-memory byte array"
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.glb.memory/memoryimage/"
product_version: "26.9"
---
## MemoryImage struct

Represents an image file stored as an in-memory byte array

```csharp
public struct MemoryImage : IEquatable<MemoryImage>
```

## Constructors

| Name | Description |
| --- | --- |
| [MemoryImage](memoryimage/)(ArraySegment&lt;byte&gt;) | Initializes a new instance of the MemoryImage class. |

## Properties

| Name | Description |
| --- | --- |
| Content { get; } | Gets the file bytes of the image. |
| Empty { get; } |  |
| FileExtension { get; } | Gets the most appropriate extension string for this image. |
| IsDds { get; } | Gets a value indicating whether this object represents a valid DDS image. |
| IsEmpty { get; } |  |
| IsExtendedFormat { get; } | Gets a value indicating whether this object represents an image backed by a glTF extension. |
| IsJpg { get; } | Gets a value indicating whether this object represents a valid JPG image. |
| IsKtx2 { get; } | Gets a value indicating whether this object represents a valid KTX2 image. |
| IsPng { get; } | Gets a value indicating whether this object represents a valid PNG image. |
| IsValid { get; } | Gets a value indicating whether this object represents a valid image. |
| IsWebp { get; } | Gets a value indicating whether this object represents a valid WEBP image. |
| MimeType { get; } | Gets the most appropriate Mime type string for this image. |
| SourcePath { get; } | Gets the source path of this image, or **null**. |

## Methods

| Name | Description |
| --- | --- |
| AreEqual(MemoryImage, MemoryImage) |  |
| Equals(MemoryImage) |  |
| Equals(object) |  |
| GetHashCode() |  |
| IsImageOfType(string) | identifies an image of a specific type. |
| Open() | Opens the image file for reading its contents |
| SaveToFile(string) | Saves the image stored in this `MemoryImage` to a file. |
| ToDebuggerDisplay() |  |
| TryParseMime64(string, out MemoryImage) | Tries to parse a Mime64 string to `MemoryImage` |

## Operators

| Name | Description |
| --- | --- |
| operator MemoryImage |  |
| operator MemoryImage |  |
| operator MemoryImage |  |
| operator == |  |
| operator != |  |

### See Also

* namespace [Aspose.CAD.FileFormats.GLB.Memory](../../aspose.cad.fileformats.glb.memory/)
* assembly [Aspose.CAD](../../)

