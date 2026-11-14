---
title: "CadAttDef 类"
linktitle: "CadAttDef"
articleTitle: "CadAttDef"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.AttEntities.CadAttDef 类. 描述 Cad AttributeDefinitions 的类"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/"
keywords: "CadAttDef, Aspose.CAD.FileFormats.Cad.CadObjects.AttEntities, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadAttDef class

描述 Cad AttributeDefinitions 的类

```csharp
public class CadAttDef : CadXrecordObject, ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadAttDef](cadattdef/)() | 初始化 `CadAttDef` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnnotationScales](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/annotationscales/) { get; } | 获取实体绑定的注释比例。 |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | 获取或设置应用程序定义的代码容器。 |
| [Area](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/area/) { get; } | 获取实体的面积。 |
| [AssocViewPortHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/assocviewporthandle/) { get; } | 获取或设置关联的视口句柄。 |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | 获取或设置 attribute102 值。 |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | 获取或设置属性。 |
| [Bounds](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/bounds/) { get; set; } | 实体的最小和最大点。调用 CadImage 的 GetBounds 后填充。 |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childobjects/) { get; set; } | 获取或设置构成当前实体的子实体。 |
| [Childs](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childs/) { get; } |  |
| [ColorHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorhandle/) { get; set; } | 获取或设置颜色句柄。 |
| [ColorId](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorid/) { get; set; } | 获取或设置实体的颜色 ID（ACI 颜色）。 |
| [ColorName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorname/) { get; set; } | 获取或设置颜色的名称。 |
| [ColorValue](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorvalue/) { get; set; } | 获取或设置实体的真实颜色值（RGB）。 |
| [CurrentAnnotationScale](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/currentannotationscale/) { get; set; } | 获取或设置当前注释比例。 |
| [DefaultString](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/defaultstring/) { get; set; } | 获取或设置默认字符串。 |
| virtual [DefinitionTagString](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/definitiontagstring/) { get; set; } | 获取或设置定义标签字符串。 |
| [DuplicateRecordCloningFlag](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/duplicaterecordcloningflag/) { get; set; } | 获取或设置重复记录克隆标志。 |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | 获取或设置嵌入对象容器。 |
| [Entmode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/entmode/) { get; set; } | 获取或设置实体模式。 |
| override [ExtrusionDirection](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/extrusiondirection/) { get; set; } | 获取或设置挤出方向。 |
| [FieldLength](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/fieldlength/) { get; set; } | 获取或设置字段长度。 |
| [FirstAlignment](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/firstalignment/) { get; set; } | 获取或设置首个对齐方式。 |
| [Flags](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/flags/) { get; set; } | 获取或设置标志。 |
| [GenerationFlag](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/generationflag/) { get; set; } | 获取或设置生成标志。 |
| [GroupHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/grouphandle/) { get; set; } | 组句柄 |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | 获取或设置硬所有者。 |
| [HardPointerIds](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/hardpointerids/) { get; set; } | 获取或设置硬指针 ID。 |
| [HorizontalAlignment](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/horizontalalignment/) { get; set; } | 获取或设置水平对齐方式。 |
| [Hyperlink](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/hyperlink/) { get; set; } | 获取或设置指向实体的超链接，并显示超链接名称或描述（如果已指定）。 |
| override [Id](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/id/) { get; set; } | 获取或设置 id。 |
| [IsAssocViewPortHandleSet](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isassocviewporthandleset/) { get; } | 获取一个值，指示是否已设置关联的视口句柄。 |
| [IsByLayer](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isbylayer/) { get; set; } | 获取或设置一个值，指示实体的线型是否由图层设置。 |
| [IsNoLinks](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isnolinks/) { get; set; } | 获取或设置一个值，指示实体没有链接。 |
| [IsReallyLockedFlag](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/isreallylockedflag/) { get; set; } | 获取或设置真正锁定标志。 |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | 获取一个值，指示是否已设置软所有者。 |
| [LType](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) { get; set; } | 获取或设置实体当前线型的值。 |
| [LayerName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layername/) { get; set; } | 获取或设置实体所属图层的名称。 |
| [LayoutTabName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layouttabname/) { get; set; } | 获取或设置布局选项卡的名称。 |
| [Length](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/length/) { get; } | 获取实体的长度。 |
| [LineScale](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linescale/) { get; set; } | 获取或设置实体的线型比例因子。 |
| [LineTypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linetypename/) { get; set; } | 获取或设置基于 [`LType`](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) 值的线型名称。 |
| [LineWeight](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/lineweight/) { get; set; } | 获取或设置实体的线宽。 |
| [LockPositionFlag](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/lockpositionflag/) { get; set; } | 获取或设置锁定位置标志。 |
| [MTextFlag](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/mtextflag/) { get; set; } | 获取或设置 m text 标志。 |
| [Material](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/material/) { get; set; } | 获取或设置材质。 |
| [MultiText](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/multitext/) { get; set; } | 获取或设置多行文本。 |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | 该 Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | 获取或设置对象句柄。 |
| [ObliqueAngle](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/obliqueangle/) { get; set; } | 获取或设置倾斜角度。 |
| [PlotStyle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyle/) { get; set; } | 获取或设置打印样式。获取或设置打印样式句柄。 |
| [PlotStyleFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyleflag/) { get; set; } | 获取或设置实体当前打印样式的值。 |
| [PromptString](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/promptstring/) { get; set; } | 获取或设置提示字符串。 |
| [ProxyBytesCount](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxybytescount/) { get; set; } | 获取或设置代理字节计数。 |
| [ProxyData](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxydata/) { get; set; } | 获取或设置代理数据。 |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | 获取或设置反应器句柄 |
| [RotationAngle](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/rotationangle/) { get; set; } | 获取或设置旋转角度。 |
| [ScaleX](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/scalex/) { get; set; } | 获取或设置 X 轴比例。 |
| [SecondAlignment](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/secondalignment/) { get; set; } | 获取或设置次要对齐方式。 |
| [SecondaryAttributesOrAttributeDefinitionsNumber](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadxrecordobject/secondaryattributesorattributedefinitionsnumber/) { get; set; } | 获取或设置次要属性或属性定义的数量。 |
| [ShadowMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/shadowmode/) { get; set; } | 获取或设置阴影模式。 |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | 获取或设置软所有者。 |
| [SpaceMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/spacemode/) { get; set; } | 获取或设置指示实体所属空间的值。 |
| override [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/storageflag/) { get; set; } | 获取或设置一个值，指示此实体在数据存储中具有关联的二进制数据。 |
| [StyleName](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/stylename/) { get; set; } | 获取或设置样式名称。 |
| [TextHeight](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/textheight/) { get; set; } | 获取或设置文本高度。 |
| [Thickness](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/thickness/) { get; set; } | 获取或设置厚度。 |
| [Transparency](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/transparency/) { get; set; } | 获取或设置实体的透明度值。 |
| override [TypeName](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/typename/) { get; } | 获取类型的名称。 |
| [VersionNumber](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/versionnumber/) { get; set; } | 获取或设置版本号。 |
| [VerticalJustification](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/verticaljustification/) { get; set; } | 获取或设置垂直对齐方式。 |
| virtual [Visible](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/visible/) { get; set; } | 获取或设置指示此 [`CadEntityBase`](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/) 是否可见的值。 |
| [XDirMissingFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/xdirmissingflag/) { get; set; } | 获取或设置指示此实体未存储 XDictionary 句柄的值。 |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | 获取或设置 xdata 容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.cad.fileformats.cad.cadobjects.attentities/cadattdef/clone/)() | 克隆当前对象 |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | 如果对象句柄不起作用时使用的标识符。作为方法实现，以免干扰 FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | 设置 |

### 另请参阅

* class [CadXrecordObject](../cadxrecordobject/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.AttEntities](../../aspose.cad.fileformats.cad.cadobjects.attentities/)
* assembly [Aspose.CAD](../../)

