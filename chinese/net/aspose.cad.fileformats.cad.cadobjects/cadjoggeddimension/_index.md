---
title: "CadJoggedDimension 类"
linktitle: "CadJoggedDimension"
articleTitle: "CadJoggedDimension"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadJoggedDimension 类。Cad 折线尺寸"
type: docs
weight: 710
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/"
keywords: "CadJoggedDimension, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadJoggedDimension class

cad 折线尺寸

```csharp
public class CadJoggedDimension : CadDimensionBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadJoggedDimension](cadjoggeddimension/)() | 初始化 `CadJoggedDimension` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualMeasurement](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/actualmeasurement/) { get; set; } | 获取或设置实际测量值。 |
| [AnnotationScales](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/annotationscales/) { get; } | 获取实体绑定的注释比例。 |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | 获取或设置应用程序定义的代码容器。 |
| [Area](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/area/) { get; } | 获取实体的面积。 |
| [ArrowSize](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/arrowsize/) { get; set; } | 获取或设置箭头的大小。通过表示箭头的实体（插入）的实体大小进行评估。包括整体标注比例因子。设置新大小会更新标注的 XData 中的相应字段并更改相关的实体（插入）对象。 |
| [AssocViewPortHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/assocviewporthandle/) { get; } | 获取或设置关联的视口句柄。 |
| [AttachmentType](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/attachmenttype/) { get; set; } | 获取或设置附件类型。 |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | 获取或设置 attribute102 值。 |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | 获取或设置属性。 |
| [BlockName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/blockname/) { get; set; } | 获取或设置块名称。 |
| [BlockTranslationVector](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/blocktranslationvector/) { get; set; } | 获取或设置块平移向量。该向量来自旧版本 CadDimensionBaseR12，因为在某些情况下块平移向量会出现在新版本 CadDimensionBase 中。 |
| [Bounds](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/bounds/) { get; set; } | 实体的最小和最大点。调用 CadImage 的 GetBounds 后填充。 |
| [CenterPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/centerpoint/) { get; set; } | 获取或设置中心点。 |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childobjects/) { get; set; } | 获取或设置构成当前实体的子实体。 |
| [Childs](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childs/) { get; } |  |
| [ChordPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/chordpoint/) { get; set; } | 获取或设置弦点。 |
| [ColorHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorhandle/) { get; set; } | 获取或设置颜色句柄。 |
| [ColorId](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorid/) { get; set; } | 获取或设置实体的颜色 ID（ACI 颜色）。 |
| [ColorName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorname/) { get; set; } | 获取或设置颜色的名称。 |
| [ColorValue](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorvalue/) { get; set; } | 获取或设置实体的真实颜色值（RGB）。 |
| [DefinitionPoint](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/definitionpoint/) { get; set; } | 获取或设置定义点。 |
| [DimAssocHandle](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimassochandle/) { get; set; } | Dim 关联句柄 |
| [DimensionTextLineSpacingFactor](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimensiontextlinespacingfactor/) { get; set; } | 获取或设置标注文本行间距因子。 |
| [DimensionType](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimensiontype/) { get; set; } | 获取或设置标注类型。 |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | 获取或设置嵌入对象容器。 |
| [Entmode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/entmode/) { get; set; } | 获取或设置实体模式。 |
| override [ExtrusionDirection](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/extrusiondirection/) { get; set; } | 获取或设置挤出方向。 |
| [Flag1](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/flag1/) { get; set; } | Flag1 标志 |
| [GroupHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/grouphandle/) { get; set; } | 组句柄 |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | 获取或设置硬所有者。 |
| [HorizontalDirection](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/horizontaldirection/) { get; set; } | 获取或设置水平方向。 |
| [Hyperlink](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/hyperlink/) { get; set; } | 获取或设置指向实体的超链接，并显示超链接名称或描述（如果已指定）。 |
| virtual [Id](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) { get; set; } | 获取标识符。 |
| [IsAssocViewPortHandleSet](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isassocviewporthandleset/) { get; } | 获取一个值，指示是否已设置关联的视口句柄。 |
| [IsByLayer](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isbylayer/) { get; set; } | 获取或设置一个值，指示实体的线型是否由图层设置。 |
| [IsNoLinks](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isnolinks/) { get; set; } | 获取或设置一个值，指示实体没有链接。 |
| [IsSingleUse](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/issingleuse/) { get; } | 获取一个值，指示是否为单次使用。 |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | 获取一个值，指示是否已设置软所有者。 |
| [IsUserDimension](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isuserdimension/) { get; } | 获取一个值，指示此实例是否为用户标注。 |
| [IsXOrdinate](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isxordinate/) { get; } | 获取一个值，指示此实例是否为 X 坐标。 |
| [IsYordinate](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isyordinate/) { get; } | 获取一个值，指示此实例是否为 yordinate。 |
| [JogPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/jogpoint/) { get; set; } | 获取或设置折线点。 |
| [LType](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) { get; set; } | 获取或设置实体当前线型的值。 |
| [LayerName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layername/) { get; set; } | 获取或设置实体所属图层的名称。 |
| [LayoutTabName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layouttabname/) { get; set; } | 获取或设置布局选项卡的名称。 |
| [Length](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/length/) { get; } | 获取实体的长度。 |
| [LineScale](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linescale/) { get; set; } | 获取或设置实体的线型比例因子。 |
| [LineTypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linetypename/) { get; set; } | 获取或设置基于 [`LType`](../cadentitybase/ltype/) 值的线型名称。 |
| [LineWeight](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/lineweight/) { get; set; } | 获取或设置实体的线宽。 |
| [Material](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/material/) { get; set; } | 获取或设置材质。 |
| [MiddleTextLocation](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/middletextlocation/) { get; set; } | 获取或设置中间文本位置。 |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | 该 Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | 获取或设置对象句柄。 |
| [OverrideCenter](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/overridecenter/) { get; set; } | 获取或设置覆盖中心。 |
| [PlotStyle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyle/) { get; set; } | 获取或设置打印样式。获取或设置打印样式句柄。 |
| [PlotStyleFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyleflag/) { get; set; } | 获取或设置实体当前打印样式的值。 |
| [ProxyBytesCount](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxybytescount/) { get; set; } | 获取或设置代理字节计数。 |
| [ProxyData](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxydata/) { get; set; } | 获取或设置代理数据。 |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | 获取或设置反应器句柄 |
| [ShadowMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/shadowmode/) { get; set; } | 获取或设置阴影模式。 |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | 获取或设置软所有者。 |
| [SpaceMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/spacemode/) { get; set; } | 获取或设置指示实体所属空间的值。 |
| override [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/storageflag/) { get; set; } | 获取或设置一个值，指示此实体在数据存储中具有关联的二进制数据。 |
| [StyleName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/stylename/) { get; set; } | 获取或设置样式名称。 |
| [Text](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/text/) { get; set; } | 获取或设置文本。 |
| [TextLineSpacing](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/textlinespacing/) { get; set; } | 获取或设置文本行间距。 |
| [TextRotationAngle](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/textrotationangle/) { get; set; } | 获取或设置 textRotationAngle 角度。 |
| [Transparency](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/transparency/) { get; set; } | 获取或设置实体的透明度值。 |
| override [TypeName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/typename/) { get; } | 获取类型的名称。 |
| [TypeOfDimension](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/typeofdimension/) { get; set; } | 获取或设置维度的类型。 |
| [Unknown](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/unknown/) { get; set; } | 获取或设置未知。 |
| [VersionNumber](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/versionnumber/) { get; set; } | 获取或设置版本号。 |
| virtual [Visible](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/visible/) { get; set; } | 获取或设置一个值，指示此 [`CadEntityBase`](../cadentitybase/) 是否可见。 |
| [XDirMissingFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/xdirmissingflag/) { get; set; } | 获取或设置指示此实体未存储 XDictionary 句柄的值。 |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | 获取或设置 xdata 容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | 如果对象句柄不起作用时使用的标识符。作为方法实现，以免干扰 FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | 设置 |

### 另请参阅

* class [CadDimensionBase](../caddimensionbase/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

