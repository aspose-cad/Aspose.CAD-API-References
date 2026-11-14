---
title: "Image.CanLoad"
linktitle: "CanLoad"
articleTitle: "CanLoad"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。确定是否可以从指定的文件路径加载图像。"
type: docs
weight: 10
url: "/net/aspose.cad/image/canload/"
product_version: "26.9"
---
## CanLoad(Stream) {#canload}

确定是否可以从指定的流加载图像。

```csharp
public static bool CanLoad(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要加载的流。 |

### 返回值

`true` 如果可以从指定的流加载图像；否则为 `false`。

## 示例

检查是否可以从指定的流加载绘图

```csharp
using (var f = File.OpenRead("file.dxf"))
{
    var currentPosition = f.Position;
    if (Image.CanLoad(f))
    {
        AssertLegacy.That(currentPosition, f.Position);
        // 处理绘图...
    }
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## CanLoad(string) {#canload_1}

确定是否可以从指定的文件路径加载图像。

```csharp
public static bool CanLoad(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

`true` 如果可以从指定的文件加载图像；否则为 `false`。

## 示例

检查是否可以加载绘图

```csharp
var fileName = @"C:\path\drawing.dwg";
if (Aspose.CAD.Image.CanLoad(fileName))
{
    using (Aspose.CAD.Image drawing = Aspose.CAD.Image.Load(fileName))
    {
        // 处理绘图
    }
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## CanLoad(Stream, LoadOptions) {#canload_2}

确定是否可以从指定的流加载图像，并可选地使用指定的 *loadOptions*。

```csharp
public static bool CanLoad(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要加载的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`true` 如果可以从指定的流加载图像；否则为 `false`。

## 示例

检查是否可以从使用相应编码的指定流加载绘图

```csharp
using (var f = File.OpenRead("file.dwg", new LoadOptions
{
    SpecifiedEncoding = CodePages.Japanese
}))
{
    var currentPosition = f.Position;
    if (Image.CanLoad(f))
    {
        AssertLegacy.That(currentPosition, f.Position);
        // 处理绘图...
    }
}
```

### 另请参阅

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## CanLoad(string, LoadOptions) {#canload_3}

确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项

```csharp
public static bool CanLoad(string filePath, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`true` 如果可以从指定的文件加载图像；否则为 `false`。

## 示例

检查是否可以使用指定编码加载绘图

```csharp
var fileName = @"C:\path\drawing.dwg";
if (Aspose.CAD.Image.CanLoad(fileName, new LoadOptions
{
    SpecifiedEncoding = CodePages.Japanese
}))
{
    using (Aspose.CAD.Image drawing = Aspose.CAD.Image.Load(fileName))
    {
        // 处理绘图
    }
}
```

### 另请参阅

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

