---
title: Class CadEntityBase
second_title: Aspose.CAD for .NET API Reference
description: Aspose.CAD.FileFormats.Cad.CadObjects.CadEntityBase class. The Cad base entity object
type: docs
weight: 2520
url: /net/aspose.cad.fileformats.cad.cadobjects/cadentitybase/
---
## CadEntityBase class

The Cad base entity object.

```csharp
public abstract class CadEntityBase : CadOwnedObjectBase, IDrawingEntity
```

## Constructors

| Name | Description |
| --- | --- |
| [CadEntityBase](cadentitybase/)() | Initializes a new instance of the `CadEntityBase` class. |

## Properties

| Name | Description |
| --- | --- |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | Gets or sets the application defined codes container. |
| [AssocViewPortHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/assocviewporthandle/) { get; } | Gets or sets of the associated view port handle. |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | Gets or sets the attribute102 values. |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | Gets or sets the attributes. |
| [Bounds](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/bounds/) { get; set; } | Minimal and maximal points of entity. Filled after GetBounds is called for CadImage. |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childobjects/) { get; set; } | Gets or sets the child entities that make up the current entity. |
| [ColorHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorhandle/) { get; set; } | Gets or sets the color handle. |
| [ColorId](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorid/) { get; set; } | Gets or sets the color id (ACI color) of the entity. |
| [ColorName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorname/) { get; set; } | Gets or sets the name of the color. |
| [ColorValue](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorvalue/) { get; set; } | Gets or sets the true color value (RGB) of the entity. |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | Gets or sets the embedded objects container. |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | Gets or sets the hard owner. |
| [Hyperlink](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/hyperlink/) { get; set; } | Gets or sets a hyperlink to an entity and displays the hyperlink name or description (if one is specified). |
| virtual [Id](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) { get; set; } | Gets the identifier. |
| [IsAssocViewPortHandleSet](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isassocviewporthandleset/) { get; } | Gets a value indicating whether associated view port handle is set. |
| [IsByLayer](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isbylayer/) { get; set; } | Gets or sets a value indicating that the entity has linetype set by layer. |
| [IsNoLinks](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isnolinks/) { get; set; } | Gets or sets a value indicating that the entity has no links. |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | Gets a value indicating whether soft owner is set. |
| [LayerName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layername/) { get; set; } | Gets or sets the name of the layer the entity belongs to. |
| [LayoutTabName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layouttabname/) { get; set; } | Gets or sets the name of the layout tab. |
| [LineScale](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linescale/) { get; set; } | Gets or sets the linetype scale factor of the entity. |
| [LineTypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linetypename/) { get; set; } | Gets or sets the name of the line type based on the [`LType`](./ltype/) value. |
| [LineWeight](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/lineweight/) { get; set; } | Gets or sets the line weight for the entity. |
| [LType](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) { get; set; } | Gets or sets a value the current linetype of the entity. |
| [Material](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/material/) { get; set; } | Gets or sets the material. |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | The Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | Gets or sets the object handle. |
| [PlotStyle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyle/) { get; set; } | Gets or sets the plot style. Gets or sets the plot style handle. |
| [PlotStyleFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyleflag/) { get; set; } | Gets or sets a value the current plot style of the entity |
| [ProxyBytesCount](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxybytescount/) { get; set; } | Gets or sets the proxy bytes count. |
| [ProxyData](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxydata/) { get; set; } | Gets or sets the proxy data. |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | Get or sets the reactors handle |
| [ShadowMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/shadowmode/) { get; set; } | Gets or sets the shadow mode. |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | Gets or sets the soft owner. |
| [SpaceMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/spacemode/) { get; set; } | Gets or sets a value indicating which space the entity belongs to. |
| [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/storageflag/) { get; set; } | Gets or sets a value indicating that this entity has associated binary data in the data store. |
| [Transparency](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/transparency/) { get; set; } | Gets or sets the transparency value for the entity. |
| virtual [TypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/typename/) { get; } | Gets the name of the type. |
| virtual [Visible](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/visible/) { get; set; } | Gets or sets a value indicating whether this `CadEntityBase` is visible. |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | Gets or sets the xdata container. |
| [XDirMissingFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/xdirmissingflag/) { get; set; } | Gets or sets a value indicating that no XDictionary handle is stored for this entity. |

## Methods

| Name | Description |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | Identifier to use if object handle doesn't work. Done as method not to disturb FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | Sets |

### See Also

* class [CadOwnedObjectBase](../cadownedobjectbase/)
* interface [IDrawingEntity](../../aspose.cad/idrawingentity/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

