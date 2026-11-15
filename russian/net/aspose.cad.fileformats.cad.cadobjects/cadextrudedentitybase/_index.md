---
title: "CadExtrudedEntityBase класс"
linktitle: "CadExtrudedEntityBase"
articleTitle: "CadExtrudedEntityBase"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadExtrudedEntityBase класс. Базовый объект вытесненной сущности Cad."
type: docs
weight: 610
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadextrudedentitybase/"
keywords: "CadExtrudedEntityBase, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadExtrudedEntityBase class

Базовый вытесненный объект сущности Cad.

```csharp
public abstract class CadExtrudedEntityBase : CadEntityBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AnnotationScales](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/annotationscales/) { get; } | Получает масштабы аннотаций, к которым привязана сущность. |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | Получает или задает контейнер кодов, определённых приложением. |
| [Area](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/area/) { get; } | Получает площадь сущности. |
| [AssocViewPortHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/assocviewporthandle/) { get; } | Получает или задает связанный дескриптор окна просмотра. |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | Получает или задает значения attribute102. |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | Получает или задает атрибуты. |
| [Bounds](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/bounds/) { get; set; } | Минимальная и максимальная точки сущности. Заполняются после вызова GetBounds для CadImage. |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childobjects/) { get; set; } | Получает или задает дочерние сущности, составляющие текущую сущность. |
| [Childs](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childs/) { get; } |  |
| [ColorHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorhandle/) { get; set; } | Получает или задает дескриптор цвета. |
| [ColorId](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorid/) { get; set; } | Получает или задает идентификатор цвета (ACI color) сущности. |
| [ColorName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorname/) { get; set; } | Получает или задает имя цвета. |
| [ColorValue](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorvalue/) { get; set; } | Получает или задает истинное значение цвета (RGB) сущности. |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | Получает или задает контейнер встроенных объектов. |
| [Entmode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/entmode/) { get; set; } | Получает или задает режим сущности |
| virtual [ExtrusionDirection](../../aspose.cad.fileformats.cad.cadobjects/cadextrudedentitybase/extrusiondirection/) { get; set; } | Получает или задает направление экструдирования. |
| [GroupHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/grouphandle/) { get; set; } | Дескриптор группы |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | Получает или задает жёсткого владельца. |
| [Hyperlink](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/hyperlink/) { get; set; } | Получает или задает гиперссылку на сущность и отображает имя или описание гиперссылки (если оно указано). |
| virtual [Id](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) { get; set; } | Получает идентификатор. |
| [IsAssocViewPortHandleSet](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isassocviewporthandleset/) { get; } | Получает значение, указывающее, установлен ли связанный дескриптор окна просмотра. |
| [IsByLayer](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isbylayer/) { get; set; } | Получает или задает значение, указывающее, что тип линии сущности задается слоем. |
| [IsNoLinks](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isnolinks/) { get; set; } | Получает или задает значение, указывающее, что у сущности нет ссылок. |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | Получает значение, указывающее, установлен ли мягкий владелец. |
| [LType](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) { get; set; } | Получает или задает значение текущего типа линии сущности. |
| [LayerName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layername/) { get; set; } | Получает или задает имя слоя, к которому принадлежит сущность. |
| [LayoutTabName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layouttabname/) { get; set; } | Получает или задает имя вкладки макета. |
| [Length](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/length/) { get; } | Получает длину сущности. |
| [LineScale](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linescale/) { get; set; } | Получает или задает коэффициент масштаба типа линии сущности. |
| [LineTypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linetypename/) { get; set; } | Получает или задает имя типа линии на основе значения [`LType`](../cadentitybase/ltype/). |
| [LineWeight](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/lineweight/) { get; set; } | Получает или задает толщину линии для сущности. |
| [Material](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/material/) { get; set; } | Получает или задает материал. |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | Получает или задает дескриптор объекта. |
| [PlotStyle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyle/) { get; set; } | Получает или задает стиль печати. Получает или задает дескриптор стиля печати. |
| [PlotStyleFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyleflag/) { get; set; } | Получает или задает значение текущего стиля печати сущности |
| [ProxyBytesCount](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxybytescount/) { get; set; } | Получает или задает количество байтов прокси. |
| [ProxyData](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxydata/) { get; set; } | Получает или задает данные прокси. |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | Получает или задает дескриптор реакторов |
| [ShadowMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/shadowmode/) { get; set; } | Получает или задает режим тени. |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | Получает или задает мягкого владельца. |
| [SpaceMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/spacemode/) { get; set; } | Получает или задает значение, указывающее, к какому пространству принадлежит сущность. |
| override [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/storageflag/) { get; set; } | Получает или задает значение, указывающее, что у этой сущности есть связанные бинарные данные в хранилище данных. |
| [Transparency](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/transparency/) { get; set; } | Получает или задает значение прозрачности для сущности. |
| virtual [TypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/typename/) { get; } | Получает имя типа. |
| virtual [Visible](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/visible/) { get; set; } | Получает или задает значение, указывающее, видим ли этот [`CadEntityBase`](../cadentitybase/). |
| [XDirMissingFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/xdirmissingflag/) { get; set; } | Получает или задает значение, указывающее, что для этой сущности не хранится дескриптор XDictionary. |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | Получает или задает контейнер xdata. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | Идентификатор, используемый если дескриптор объекта не работает. Выполнено как метод, чтобы не нарушать FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | Устанавливает |

### См. также

* class [CadEntityBase](../cadentitybase/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

