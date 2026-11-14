---
title: "License 类"
linktitle: "License"
articleTitle: "License"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.License 类。提供对组件进行授权的方法。"
type: docs
weight: 570
url: "/net/aspose.cad/license/"
keywords: "License, Aspose.CAD, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## License class

提供对组件授权的方法。

```csharp
public class License
```

## 示例

在此示例中，将尝试查找名为 MyLicense.lic 的许可证文件。
在包含的文件夹中
组件所在的文件夹中，包含调用程序集的文件夹中，
在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。
 
组件 jar 文件：

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license/)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.cad/license/setlicense/#setlicense)(Stream) | 对组件进行授权。 |
| [SetLicense](../../aspose.cad/license/setlicense/#setlicense_1)(string) | 对组件进行授权。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

