---
title: "License.SetLicense"
linktitle: "SetLicense"
articleTitle: "SetLicense"
second_title: "Aspose.CAD for .NET API 参考"
description: "License 方法。为组件授权。"
type: docs
weight: 20
url: "/net/aspose.cad/license/setlicense/"
product_version: "26.9"
---
## SetLicense(Stream) {#setlicense}

对组件进行授权。

```csharp
public void SetLicense(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含许可证的流。 |

## 备注

使用此方法从流中加载许可证。

## 示例

```csharp
<ms>
  [C#]

  License license = new License();
  license.SetLicense(myStream);


  [Visual Basic]

  Dim license as License = new License
  license.SetLicense(myStream)
  </ms>
<java>
  License license = new License();
  license.setLicense(myStream);
  </java>
```

### 另请参阅

* class [License](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## SetLicense(string) {#setlicense_1}

对组件进行授权。

```csharp
public void SetLicense(string licenseName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | String | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串切换到评估模式。 |

## 备注

尝试在以下位置查找许可证：
1. 明确路径。
 
2. 包含 Aspose 组件程序集的文件夹。
3. 包含客户端调用程序集的文件夹。
4. 包含入口（启动）程序集的文件夹。
5. 客户端调用程序集中的嵌入资源。
 
 **Note:**On the .NET Compact Framework, tries to find the license only in these locations:
1. 明确路径。
2. 客户端调用程序集中的嵌入资源。
 
 
2. 包含 Aspose 组件 JAR 文件的文件夹。
3. 包含客户端调用 JAR 文件的文件夹。

## 示例

在此示例中，将尝试查找名为 MyLicense.lic 的许可证文件。
在包含的文件夹中
组件所在的文件夹中，包含调用程序集的文件夹中，
在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。
 
组件 jar 文件：
可以是完整或简短的文件名，或嵌入资源的名称。
使用空字符串切换到评估模式。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### 另请参阅

* class [License](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

