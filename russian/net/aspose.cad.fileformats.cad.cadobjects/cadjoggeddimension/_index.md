---
title: "Класс CadJoggedDimension"
linktitle: "CadJoggedDimension"
articleTitle: "CadJoggedDimension"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.CadJoggedDimension class. Размер с зазорами Cad"
type: docs
weight: 710
url: "/net/aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/"
keywords: "CadJoggedDimension, Aspose.CAD.FileFormats.Cad.CadObjects, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadJoggedDimension class

Смещённый размер cad

```csharp
public class CadJoggedDimension : CadDimensionBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadJoggedDimension](cadjoggeddimension/)() | Инициализирует новый экземпляр класса `CadJoggedDimension`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualMeasurement](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/actualmeasurement/) { get; set; } | Получает или задает фактическое измерение. |
| [AnnotationScales](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/annotationscales/) { get; } | Получает масштабы аннотаций, к которым привязана сущность. |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | Получает или задает контейнер кодов, определённых приложением. |
| [Area](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/area/) { get; } | Получает площадь сущности. |
| [ArrowSize](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/arrowsize/) { get; set; } | Получает или задает размер стрелки. Оценивается по размеру твердой (insert) сущности, представляющей стрелку. Включён общий коэффициент масштабирования размера. Установка нового размера обновляет соответствующие поля в XData для размера и изменяет связанные твердые (insert) объекты. |
| [AssocViewPortHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/assocviewporthandle/) { get; } | Получает или задает связанный дескриптор окна просмотра. |
| [AttachmentType](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/attachmenttype/) { get; set; } | Получает или задает тип вложения. |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | Получает или задает значения attribute102. |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | Получает или задает атрибуты. |
| [BlockName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/blockname/) { get; set; } | Получает или задает имя блока. |
| [BlockTranslationVector](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/blocktranslationvector/) { get; set; } | Получает или задает вектор перемещения блока. Он был получен из старой версии CadDimensionBaseR12, потому что у нас бывают случаи, когда вектор перемещения блока появляется в новой версии CadDimensionBase. |
| [Bounds](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/bounds/) { get; set; } | Минимальная и максимальная точки сущности. Заполняются после вызова GetBounds для CadImage. |
| [CenterPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/centerpoint/) { get; set; } | Получает или задает центральную точку. |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childobjects/) { get; set; } | Получает или задает дочерние сущности, составляющие текущую сущность. |
| [Childs](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/childs/) { get; } |  |
| [ChordPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/chordpoint/) { get; set; } | Получает или задает точку хорды. |
| [ColorHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorhandle/) { get; set; } | Получает или задает дескриптор цвета. |
| [ColorId](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorid/) { get; set; } | Получает или задает идентификатор цвета (ACI color) сущности. |
| [ColorName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorname/) { get; set; } | Получает или задает имя цвета. |
| [ColorValue](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/colorvalue/) { get; set; } | Получает или задает истинное значение цвета (RGB) сущности. |
| [DefinitionPoint](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/definitionpoint/) { get; set; } | Получает или задает точку определения. |
| [DimAssocHandle](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimassochandle/) { get; set; } | Объект Dim Assoc Handle |
| [DimensionTextLineSpacingFactor](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimensiontextlinespacingfactor/) { get; set; } | Получает или задает коэффициент межстрочного интервала текста размерности. |
| [DimensionType](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/dimensiontype/) { get; set; } | Получает или задает тип размерности. |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | Получает или задает контейнер встроенных объектов. |
| [Entmode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/entmode/) { get; set; } | Получает или задает режим сущности |
| override [ExtrusionDirection](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/extrusiondirection/) { get; set; } | Получает или задает направление экструдирования. |
| [Flag1](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/flag1/) { get; set; } | Флаг1 |
| [GroupHandle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/grouphandle/) { get; set; } | Дескриптор группы |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | Получает или задает жёсткого владельца. |
| [HorizontalDirection](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/horizontaldirection/) { get; set; } | Получает или задает горизонтальное направление. |
| [Hyperlink](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/hyperlink/) { get; set; } | Получает или задает гиперссылку на сущность и отображает имя или описание гиперссылки (если оно указано). |
| virtual [Id](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/id/) { get; set; } | Получает идентификатор. |
| [IsAssocViewPortHandleSet](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isassocviewporthandleset/) { get; } | Получает значение, указывающее, установлен ли связанный дескриптор окна просмотра. |
| [IsByLayer](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isbylayer/) { get; set; } | Получает или задает значение, указывающее, что тип линии сущности задается слоем. |
| [IsNoLinks](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/isnolinks/) { get; set; } | Получает или задает значение, указывающее, что у сущности нет ссылок. |
| [IsSingleUse](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/issingleuse/) { get; } | Возвращает значение, указывающее, является ли однократным. |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | Получает значение, указывающее, установлен ли мягкий владелец. |
| [IsUserDimension](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isuserdimension/) { get; } | Возвращает значение, указывающее, является ли данный экземпляр пользовательской размерностью. |
| [IsXOrdinate](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isxordinate/) { get; } | Возвращает значение, указывающее, является ли данный экземпляр координатой X. |
| [IsYordinate](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/isyordinate/) { get; } | Возвращает значение, указывающее, является ли данный экземпляр координатой Y. |
| [JogPoint](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/jogpoint/) { get; set; } | Получает или задает точку зазора. |
| [LType](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/ltype/) { get; set; } | Получает или задает значение текущего типа линии сущности. |
| [LayerName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layername/) { get; set; } | Получает или задает имя слоя, к которому принадлежит сущность. |
| [LayoutTabName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/layouttabname/) { get; set; } | Получает или задает имя вкладки макета. |
| [Length](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/length/) { get; } | Получает длину сущности. |
| [LineScale](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linescale/) { get; set; } | Получает или задает коэффициент масштаба типа линии сущности. |
| [LineTypeName](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/linetypename/) { get; set; } | Получает или задает имя типа линии на основе значения [`LType`](../cadentitybase/ltype/). |
| [LineWeight](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/lineweight/) { get; set; } | Получает или задает толщину линии для сущности. |
| [Material](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/material/) { get; set; } | Получает или задает материал. |
| [MiddleTextLocation](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/middletextlocation/) { get; set; } | Получает или задает расположение среднего текста. |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | Получает или задает дескриптор объекта. |
| [OverrideCenter](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/overridecenter/) { get; set; } | Получает или задает переопределённый центр. |
| [PlotStyle](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyle/) { get; set; } | Получает или задает стиль печати. Получает или задает дескриптор стиля печати. |
| [PlotStyleFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/plotstyleflag/) { get; set; } | Получает или задает значение текущего стиля печати сущности |
| [ProxyBytesCount](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxybytescount/) { get; set; } | Получает или задает количество байтов прокси. |
| [ProxyData](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/proxydata/) { get; set; } | Получает или задает данные прокси. |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | Получает или задает дескриптор реакторов |
| [ShadowMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/shadowmode/) { get; set; } | Получает или задает режим тени. |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | Получает или задает мягкого владельца. |
| [SpaceMode](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/spacemode/) { get; set; } | Получает или задает значение, указывающее, к какому пространству принадлежит сущность. |
| override [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/storageflag/) { get; set; } | Получает или задает значение, указывающее, что у этой сущности есть связанные бинарные данные в хранилище данных. |
| [StyleName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/stylename/) { get; set; } | Получает или задает имя стиля. |
| [Text](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/text/) { get; set; } | Получает или задает текст. |
| [TextLineSpacing](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/textlinespacing/) { get; set; } | Получает или задает межстрочный интервал текста. |
| [TextRotationAngle](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/textrotationangle/) { get; set; } | Получает или задает угол textRotationAngle. |
| [Transparency](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/transparency/) { get; set; } | Получает или задает значение прозрачности для сущности. |
| override [TypeName](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/typename/) { get; } | Получает имя типа. |
| [TypeOfDimension](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/typeofdimension/) { get; set; } | Получает или задает тип размерности. |
| [Unknown](../../aspose.cad.fileformats.cad.cadobjects/cadjoggeddimension/unknown/) { get; set; } | Получает или задает неизвестное. |
| [VersionNumber](../../aspose.cad.fileformats.cad.cadobjects/caddimensionbase/versionnumber/) { get; set; } | Получает или задает номер версии. |
| virtual [Visible](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/visible/) { get; set; } | Получает или задает значение, указывающее, видим ли этот [`CadEntityBase`](../cadentitybase/). |
| [XDirMissingFlag](../../aspose.cad.fileformats.cad.cadobjects/cadentitybase/xdirmissingflag/) { get; set; } | Получает или задает значение, указывающее, что для этой сущности не хранится дескриптор XDictionary. |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | Получает или задает контейнер xdata. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | Идентификатор, используемый если дескриптор объекта не работает. Выполнено как метод, чтобы не нарушать FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | Устанавливает |

### См. также

* class [CadDimensionBase](../caddimensionbase/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects](../../aspose.cad.fileformats.cad.cadobjects/)
* assembly [Aspose.CAD](../../)

