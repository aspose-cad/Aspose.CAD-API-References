---
title: "Image.GetFileFormat"
linktitle: "GetFileFormat"
articleTitle: "GetFileFormat"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。 获取文件格式。"
type: docs
weight: 50
url: "/net/aspose.cad/image/getfileformat/"
product_version: "26.9"
---
## GetFileFormat(Stream) {#getfileformat}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着可以加载指定的图像。请使用 CanLoad 方法的重载之一来确定是否可以加载流。

## 示例

确定流是否包含 DXF 绘图

```csharp
using (var f = File.OpenRead("file.dxf"))
{
    var fileFormat = Image.GetFileFormat(f);
    if (fileFormat >= FileFormat.DXFCadR010 && fileFormat <= FileFormat.DXFCadR2010)
    {
        Console.WriteLine("This is a DXF drawing");
    }
}
```

### 另请参阅

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## GetFileFormat(string) {#getfileformat_1}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着可以加载指定的图像。请使用 CanLoad 方法的重载之一来确定是否可以加载文件。

## 示例

确定文件是否为 DWG 绘图

```csharp
var fileFormat = Image.GetFileFormat("file.dwg");
if (fileFormat >= FileFormat.CadR010 && fileFormat <= FileFormat.CadR2010)
{
    Console.WriteLine("This is a DWG drawing");
}
```

### 另请参阅

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

