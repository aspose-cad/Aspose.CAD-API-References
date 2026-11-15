---
title: "CadAcDbAssocValueDependency Класс"
linktitle: "CadAcDbAssocValueDependency"
articleTitle: "CadAcDbAssocValueDependency"
second_title: "Aspose.CAD для .NET справка API"
description: "Aspose.CAD.FileFormats.Cad.CadObjects.Assoc.CadAcDbAssocValueDependency class. Класс, описывающий зависимость значения Assoc."
type: docs
weight: 100
url: "/net/aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocvaluedependency/"
keywords: "CadAcDbAssocValueDependency, Aspose.CAD.FileFormats.Cad.CadObjects.Assoc, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadAcDbAssocValueDependency class

Класс, описывающий зависимость значения Assoc.

```csharp
public class CadAcDbAssocValueDependency : CadAcDbAssocDependency
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadAcDbAssocValueDependency](cadacdbassocvaluedependency/)() | Инициализирует новый экземпляр класса `CadAcDbAssocValueDependency`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | Получает или задает контейнер кодов, определённых приложением. |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | Получает или задает значения attribute102. |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | Получает или задает атрибуты. |
| [ChildObjects](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/childobjects/) { get; set; } | Получает или задает дочерние объекты. |
| [DependencyBody](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/dependencybody/) { get; set; } | Получает и задает порядок зависимости. |
| [DependencyBodyId](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/dependencybodyid/) { get; set; } | Получает и задает идентификатор тела зависимости. |
| [DependentOnObject](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/dependentonobject/) { get; set; } | Получает дескриптор, к которому прикреплена эта зависимость. |
| [DependentOnObjectValue](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocvaluedependency/dependentonobjectvalue/) { get; set; } | Получает или задает значение в объекте, от которого зависит. |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | Получает или задает контейнер встроенных объектов. |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | Получает или задает жёсткого владельца. |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | Получает значение, указывающее, установлен ли мягкий владелец. |
| [Name](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/name/) { get; set; } | Получает или задает имя зависимости. |
| [NextDependencyOnObject](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/nextdependencyonobject/) { get; set; } | Получает дескриптор следующей зависимости в списке зависимостей. |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | Получает или задает дескриптор объекта. |
| [Order](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/order/) { get; set; } | Получает и задает порядок зависимости. |
| [PrevDependencyOnObject](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/prevdependencyonobject/) { get; set; } | Получает дескриптор предыдущей зависимости в списке зависимостей. |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | Получает или задает дескриптор реакторов |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | Получает или задает мягкого владельца. |
| [Status](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocdependency/status/) { get; set; } | Получает или задает текущий AssocStatus этой зависимости. |
| virtual [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/storageflag/) { get; set; } | Получает или задает значение, указывающее, что у этой сущности есть связанные бинарные данные в хранилище данных. |
| [TypeName](../../aspose.cad.fileformats.cad.cadobjects/cadbaseobject/typename/) { get; } | Получает имя типа. |
| [ValueName](../../aspose.cad.fileformats.cad.cadobjects.assoc/cadacdbassocvaluedependency/valuename/) { get; set; } | Получает или задает имя значения. |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | Получает или задает контейнер xdata. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | Идентификатор, используемый если дескриптор объекта не работает. Выполнено как метод, чтобы не нарушать FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | Устанавливает |

### См. также

* [CadAcDbAssocDependency](../cadacdbassocdependency/)
* class [CadAcDbAssocDependency](../cadacdbassocdependency/)
* namespace [Aspose.CAD.FileFormats.Cad.CadObjects.Assoc](../../aspose.cad.fileformats.cad.cadobjects.assoc/)
* assembly [Aspose.CAD](../../)

