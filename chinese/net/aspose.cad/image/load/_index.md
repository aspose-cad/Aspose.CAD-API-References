---
title: "Image.Load"
linktitle: "Load"
articleTitle: "Load"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。 从指定文件加载新图像。"
type: docs
weight: 80
url: "/net/aspose.cad/image/load/"
product_version: "26.9"
---
## Load(Stream) {#load}

从指定的流加载新图像。

```csharp
public static Image Load(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |

### 返回值

已加载的绘图。

## 示例

从相应流加载要处理的绘图

```csharp
using (var image = Aspose.CAD.Image.Load(File.OpenRead("fileName.dwg"))
{
    // 处理绘图
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Load(string) {#load_1}

从指定的文件加载新图像。

```csharp
public static Image Load(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于加载图像的文件路径。 |

### 返回值

已加载的绘图。

## 示例

加载要处理的绘图

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    // 处理绘图
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Load(Stream, LoadOptions) {#load_2}

从指定的流加载新图像。

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

已加载的绘图。

## 示例

从相应流加载要处理的绘图，并在调用 dispose 时卸载所有相关资源

```csharp
using (var image = Aspose.CAD.Image.Load(File.OpenRead("fileName.dwg"), new LoadOptions
{
    UnloadOnDispose = true
}))
{
    // 处理绘图
}
```

### 另请参阅

* class [Image](../)
* class [LoadOptions](../../loadoptions/)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Load(string, LoadOptions) {#load_3}

从指定的文件加载新图像。

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于加载图像的文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

已加载的绘图。

## 示例

加载要处理的绘图，并在调用 dispose 时卸载所有相关资源

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg", new LoadOptions
{
    UnloadOnDispose = true
}))
{
    // 处理绘图
}
```

### 另请参阅

* class [Image](../)
* class [LoadOptions](../../loadoptions/)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Load(Stream, string, LoadOptions) {#load_4}

从指定的流加载新图像。

```csharp
public static Image Load(Stream stream, string fileName, LoadOptions loadOptions = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |
| fileName | String | 文件名。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

已加载的绘图。

## 示例

从相应流加载要处理的绘图

```csharp
string filePath = "C:\\fileName.dgn";
string fileName = "fileName.dgn";
var ms = new MemoryStream(File.ReadAllBytes(filePath);
var image = Image.Load(ms, fileName)
    // 处理绘图
```

### 另请参阅

* class [Image](../)
* class [LoadOptions](../../loadoptions/)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

