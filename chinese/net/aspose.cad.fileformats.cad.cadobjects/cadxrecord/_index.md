---
title: "CadXRecord 类"
linktitle: "CadXRecord"
articleTitle: "CadXRecord"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadXRecord 类。描述 CadXRecord 的类。"
type: docs
weight: 1460
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadxrecord/"
keywords: "CadXRecord, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadXRecord class

描述 CadXRecord 的类

```csharp
public class CadXRecord : CadBaseObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadXRecord](cadxrecord/)() | 初始化 `CadXRecord` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | 获取或设置应用程序定义的代码容器。 |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | 获取或设置 attribute102 值。 |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | 获取或设置属性。 |
| [BinaryData310](../../aspose.cad.fileformats.cad.cadobjects/cadxrecord/binarydata310/) { get; set; } | 获取或设置二进制数据 310。 |
| [BinaryData311](../../aspose.cad.fileformats.cad.cadobjects/cadxrecord/binarydata311/) { get; set; } | 获取或设置二进制数据 311。 |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/childobjects/) { get; set; } | 获取或设置子对象。 |
| [DuplicateCloningFlag](../../aspose.cad.fileformats.cad.cadobjects/cadxrecord/duplicatecloningflag/) { get; set; } | 获取或设置重复克隆标志。 |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | 获取或设置嵌入对象容器。 |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | 获取或设置硬所有者。 |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | 获取一个值，指示是否已设置软所有者。 |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | 该 Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | 获取或设置对象句柄。 |
| [Objects](../../aspose.cad.fileformats.cad.cadobjects/cadxrecord/objects/) { get; set; } | 获取或设置对象。Xrecord 对象用于存储和管理任意数据。它们由带有“normal object”组的 DXF 组码组成（即非 xdata 组码），范围为 1 到 369（支持的范围）。此对象在概念上类似于 xdata，但不受大小或顺序的限制。 |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | 获取或设置反应器句柄 |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | 获取或设置软所有者。 |
| virtual [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/storageflag/) { get; set; } | 获取或设置一个值，指示此实体在数据存储中具有关联的二进制数据。 |
| [TypeName](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/typename/) { get; } | 获取类型的名称。 |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | 获取或设置 xdata 容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | 如果对象句柄不起作用时使用的标识符。作为方法实现，以免干扰 FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | 设置 |

### 另请参阅

* class [CadBaseObject](../cadbaseobject/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

