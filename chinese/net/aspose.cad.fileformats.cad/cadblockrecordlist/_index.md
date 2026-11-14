---
title: "CadBlockRecordList 类"
linktitle: "CadBlockRecordList"
articleTitle: "CadBlockRecordList"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadBlockRecordList 类。cad 视图字典 以下组代码适用于 VPORT 符号表条目。VPORT 表 i..."
type: docs
weight: 90
url: "/net/aspose.cad.fileformats.cad/cadblockrecordlist/"
keywords: "CadBlockRecordList, Aspose.CAD.FileFormats.Cad, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadBlockRecordList class

cad 视图字典
以下组代码适用于 VPORT 符号表条目。VPORT
表是唯一的：它可能包含多个具有相同名称的条目（表示
多视口配置）。对应活动的条目
视口配置全部具有名称 *ACTIVE。第一个此类条目
描述当前视口。
由于名称不是唯一的，我们使用 List 作为容器

```csharp
public class CadBlockRecordList : NonGenericList, ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadBlockRecordList](cadblockrecordlist/)() | 初始化 `CadBlockRecordList` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CadSymbolTableGroupCodes](../../aspose.cad.fileformats.cad/cadblockrecordlist/cadsymboltablegroupcodes/) { get; set; } | 获取或设置 cad 符号表组代码。 |
| [Count](../../aspose.cad/nongenericlist/count/) { get; } | 获取 ICollection 中包含的元素数量。 |
| [IsFixedSize](../../aspose.cad/nongenericlist/isfixedsize/) { get; } | 获取一个值，指示 IList 是否具有固定大小。 |
| [IsReadOnly](../../aspose.cad/nongenericlist/isreadonly/) { get; } | 获取一个值，指示 IList 是否为只读。 |
| [IsSynchronized](../../aspose.cad/nongenericlist/issynchronized/) { get; } | 获取一个值，指示对 ICollection 的访问是否已同步（线程安全）。 |
| [Item](../../aspose.cad/nongenericlist/item/) { get; set; } | 获取或设置指定索引处的元素。 |
| [SyncRoot](../../aspose.cad/nongenericlist/syncroot/) { get; } | 获取一个可用于同步对 ICollection 访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.cad/nongenericlist/add/)(object) | 向 IList 添加一个项。 |
| [AddRange](../../aspose.cad.fileformats.cad/cadblockrecordlist/addrange/)(CadBlockTableObject[]) | 将对象范围添加到容器中。 |
| [Clear](../../aspose.cad/nongenericlist/clear/)() | 从 IList 中移除所有项。 |
| [Clone](../../aspose.cad.fileformats.cad/cadblockrecordlist/clone/)() | 克隆。 |
| [Contains](../../aspose.cad/nongenericlist/contains/)(object) | 确定 IList 是否包含特定值。 |
| [CopyTo](../../aspose.cad/nongenericlist/copyto/)(Array, int) | 将 ICollection 的元素复制到数组，从特定的数组索引开始。 |
| [GetBlockByLayoutHandle](../../aspose.cad.fileformats.cad/cadblockrecordlist/getblockbylayouthandle/)(string) | 通过布局句柄获取块表 |
| [GetEnumerator](../../aspose.cad/nongenericlist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [IndexOf](../../aspose.cad/nongenericlist/indexof/)(object) | 确定 IList 中特定项的索引。 |
| [Insert](../../aspose.cad/nongenericlist/insert/)(int, object) | 在指定索引处向 IList 插入一项。 |
| [Remove](../../aspose.cad/nongenericlist/remove/)(object) | 从 IList 中移除特定对象的第一次出现。 |
| [RemoveAt](../../aspose.cad/nongenericlist/removeat/)(int) | 移除指定索引处的 IList 项目。 |

### 另请参阅

* class [NonGenericList](../../aspose.cad/nongenericlist/)
* namespace [Aspose.CAD.FileFormats.Cad](../../aspose.cad.fileformats.cad/)
* assembly [Aspose.CAD](../../)

