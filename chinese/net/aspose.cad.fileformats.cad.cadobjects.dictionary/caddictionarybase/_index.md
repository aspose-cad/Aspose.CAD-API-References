---
title: "CadDictionaryBase 类"
linktitle: "CadDictionaryBase"
articleTitle: "CadDictionaryBase"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.Dictionary.CadDictionaryBase 类。描述 DICTIONARY 基础对象的类。"
type: docs
weight: 30
url: "/net/aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/"
keywords: "CadDictionaryBase, Aspose.CAD.FileFormats.Cad.CadObjects.Dictionary, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadDictionaryBase class

描述 DICTIONARY 基础对象的类。

```csharp
public abstract class CadDictionaryBase : CadBaseObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadDictionaryBase](caddictionarybase/)() | 初始化 `CadDictionaryBase` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | 获取或设置应用程序定义的代码容器。 |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | 获取或设置 attribute102 值。 |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | 获取或设置属性。 |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/childobjects/) { get; set; } | 获取或设置子对象。 |
| [CloningFlag](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/cloningflag/) { get; set; } | 获取或设置克隆标志。 |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | 获取或设置嵌入对象容器。 |
| [EntryNames](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/entrynames/) { get; set; } | 获取或设置条目的名称。 |
| [EntrySoftOwners](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/entrysoftowners/) { get; set; } | 获取或设置条目的软所有者。 |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | 获取或设置硬所有者。 |
| [HardOwnerFlag](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/hardownerflag/) { get; set; } | 获取或设置硬所有者标志。 |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | 获取一个值，指示是否已设置软所有者。 |
| [Item](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/item/) { get; } | 获取或设置通过键的条目软所有者。 |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | 该 Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | 获取或设置对象句柄。 |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | 获取或设置反应器句柄 |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | 获取或设置软所有者。 |
| virtual [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/storageflag/) { get; set; } | 获取或设置一个值，指示此实体在数据存储中具有关联的二进制数据。 |
| [TypeName](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/typename/) { get; } | 获取类型的名称。 |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | 获取或设置 xdata 容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | 如果对象句柄不起作用时使用的标识符。作为方法实现，以免干扰 FileComparer's property comparer |
| [RemoveByValue](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/removebyvalue/)(string) | 通过值移除条目软所有者和条目名称。 |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | 设置 |
| [TryGetValue](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/trygetvalue/#trygetvalue)(string, out string) | 获取通过键的条目软所有者。 |
| [TryGetValue](../../aspose.cad.fileformats.cad.cadobjects.dictionary/caddictionarybase/trygetvalue/#trygetvalue_1)(string, out CadEntityAttribute, out string) | 获取通过键的条目软所有者。 |

### 另请参阅

* class [CadBaseObject](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.Dictionary](../../aspose.cad.fileformats.cad.cadobjects.dictionary/)
* assembly [Aspose.CAD](../../)

