---
title: Load
second_title: Aspose.CAD for .NET API 参考
description: 从指定文件加载新图像
type: docs
weight: 10
url: /zh/net/aspose.cad/image/load/
---
## Load(string, LoadOptions) {#load_3}

从指定文件加载新图像。

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 加载图像的文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

加载的图纸。

### 例子

加载要处理的图形并在调用 dispose 时卸载所有相关资源

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg", new LoadOptions
{
    UnloadOnDispose = true
}))
{
    // 处理绘图
}
```

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.CAD](../../image)
* 部件 [Aspose.CAD](../../../)

---

## Load(string) {#load_2}

从指定文件加载新图像。

```csharp
public static Image Load(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 加载图像的文件路径。 |

### 返回值

加载的图纸。

### 例子

加载要处理的图形

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    // 处理绘图
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.CAD](../../image)
* 部件 [Aspose.CAD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

从指定的流中加载新图像。

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 要从中加载图像的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

加载的图纸。

### 例子

从相应的流中加载要处理的图形，并在调用 dispose 时卸载所有相关资源

```csharp
using (var image = Aspose.CAD.Image.Load(File.OpenRead("fileName.dwg"), new LoadOptions
{
    UnloadOnDispose = true
}))
{
    // 处理绘图
}
```

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.CAD](../../image)
* 部件 [Aspose.CAD](../../../)

---

## Load(Stream) {#load}

从指定的流中加载新图像。

```csharp
public static Image Load(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 要从中加载图像的流。 |

### 返回值

加载的图纸。

### 例子

从相应的流中加载要处理的图形

```csharp
using (var image = Aspose.CAD.Image.Load(File.OpenRead("fileName.dwg"))
{
    // 处理绘图
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.CAD](../../image)
* 部件 [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
