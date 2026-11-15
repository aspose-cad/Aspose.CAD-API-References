---
title: "Aspose.CAD.FileFormats.GLB"
linktitle: "Aspose.CAD.FileFormats.GLB"
articleTitle: "Aspose.CAD.FileFormats.GLB"
second_title: "Aspose.CAD для .NET справка API"
description: "Пространство имён обрабатывает обработку формата файлов GLB."
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb/"
keywords: "Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Overview

Пространство имён обрабатывает обработку формата файлов GLB.

Часть [Aspose.CAD for .NET](../) справки API.

## Классы

| Класс | Описание |
| --- | --- |
| [Accessor](./accessor/) |  |
| [Animation](./animation/) | Анимация ключевых кадров. |
| [AnimationChannel](./animationchannel/) |  |
| [Asset](./asset/) | Метаданные о ресурсе glTF. |
| [Buffer](./buffer/) | Буфер указывает на бинарную геометрию, анимацию или скины. |
| [BufferView](./bufferview/) | Представление буфера, обычно представляющее подмножество буфера. |
| [Camera](./camera/) | Проекция камеры. Узел **MAY** может ссылаться на камеру, чтобы применить преобразование и разместить камеру в сцене. |
| [ExtensionsFactory](./extensionsfactory/) | Менеджер глобальных расширений. |
| [ExtraProperties](./extraproperties/) | Представляет базовый класс для всех объектов схемы glTF 2. |
| [GlbData](./glbdata/) | Корневой объект ресурса glTF. |
| [GlbImage](./glbimage/) |  |
| [GltfImage](./gltfimage/) |  |
| [GltfImageBase](./gltfimagebase/) | Представляет базовый класс сериализуемого объекта glTF schema2. Наследуется от [`ExtraProperties`](../aspose.cad.fileformats.glb/extraproperties/). |
| [GltfLoadOptions](./gltfloadoptions/) | Представляет параметры загрузки изображения GLTF/GLB. |
| [ImageGlb](./imageglb/) | Данные изображения, используемые для создания текстуры. Изображение **MAY** быть указано через URI (или IRI) или индекс представления буфера. |
| [LogicalChildOfRoot](./logicalchildofroot/) | Все элементы gltf, хранящиеся в ModelRoot, должны наследоваться от этого класса. |
| [Material](./material/) | Внешний вид материала примитива. |
| [Mesh](./mesh/) | Набор примитивов для рендеринга. Его глобальное преобразование определяется узлом, который ссылается на него. |
| [MeshGpuInstancing](./meshgpuinstancing/) | Расширение glTF определяет атрибуты экземпляра для узла с сеткой. |
| [MeshPrimitive](./meshprimitive/) | Геометрия, которая будет отрисована с указанным материалом. |
| [MeshPrimitiveDracoMesh](./meshprimitivedracomesh/) | Геометрия, которая будет отрисована с указанным материалом. |
| [Node](./node/) | Узел в иерархии узлов. Когда узел содержит `skin`, все `mesh.primitives` **MUST** содержать атрибуты `JOINTS_0` и `WEIGHTS_0`. Узел **MAY** иметь либо `matrix`, либо любую комбинацию свойств `translation`/`rotation`/`scale` (TRS). Свойства TRS преобразуются в матрицы и постмножаются в порядке `T * R * S` для составления матрицы преобразования; сначала к вершинам применяется масштаб, затем вращение, затем перемещение. Если ни одно из них не указано, преобразование является единичным. Когда узел используется в анимации (ссылка через animation.channel.target), `matrix` **MUST NOT** присутствовать. |
| [PunctualLight](./punctuallight/) | Направленный, точечный или прожекторный свет. |
| [ReadSettings](./readsettings/) | Настройки чтения и базовый класс `ReadContext` |
| [Scene](./scene/) | Корневые узлы сцены. |
| [Skin](./skin/) | Суставы и матрицы, определяющие скин. |
| [Texture](./texture/) | Текстура и её сэмплер. |
| [TextureSampler](./texturesampler/) | Свойства сэмплера текстуры для режимов фильтрации и обтекания. |
| [TextureTransform](./texturetransform/) | Расширение glTF, позволяющее сдвигать и масштабировать UV‑координаты для каждой текстуры отдельно |
| [WriteSettings](./writesettings/) | Настройки записи и базовый класс `WriteContext` |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [ICamera](./icamera/) | Общий интерфейс для `CameraOrthographic` и `CameraPerspective`. |
| [IMaterialParameter](./imaterialparameter/) |  |
| [IVisualNodeContainer](./ivisualnodecontainer/) | Представляет абстрактный интерфейс визуальной иерархии. Реализовано в [`Node`](../aspose.cad.fileformats.glb/node/) и [`Scene`](../aspose.cad.fileformats.glb/scene/). |

## Перечисление

| Перечисление | Описание |
| --- | --- |
| [AgiArticulationTransformType](./agiarticulationtransformtype/) | Тип движения, применяемый на этом этапе артикуляции. |
| [AlphaMode](./alphamode/) | Режим альфа-рендеринга материала. |
| [AnimationInterpolationMode](./animationinterpolationmode/) | Алгоритм интерполяции. |
| [BufferMode](./buffermode/) | Подсказка, указывающая предполагаемый тип GPU‑буфера для использования с этим представлением буфера. |
| [CameraType](./cameratype/) | Указывает, использует ли камера перспективную или ортографическую проекцию. |
| [DimensionType](./dimensiontype/) | Указывает, являются ли элементы аксессора скалярами, векторами или матрицами. |
| [EncodingType](./encodingtype/) | Тип данных компонентов аксессора. |
| [IndexEncodingType](./indexencodingtype/) | Тип данных индексов. |
| [PrimitiveType](./primitivetype/) | Тип топологии примитивов для рендеринга. |
| [PropertyPath](./propertypath/) | Имя свойства TRS узла для анимации или веса морф‑целей, которые он инстанцирует. Для свойства translation значения, предоставляемые сэмплером, представляют собой перемещение вдоль осей X, Y и Z. Для свойства rotation значения — кватернион в порядке (x, y, z, w), где w является скаляром. Для свойства scale значения — коэффициенты масштабирования вдоль осей X, Y и Z. |
| [PunctualLightType](./punctuallighttype/) | Определяет все типы [`PunctualLight`](../aspose.cad.fileformats.glb/punctuallight/). |
| [ResourceWriteMode](./resourcewritemode/) | Определяет, как записываются ресурсы. |
| [TextureInterpolationFilter](./textureinterpolationfilter/) | Фильтр увеличения. |
| [TextureMipMapFilter](./texturemipmapfilter/) | Фильтр уменьшения. |
| [TextureWrapMode](./texturewrapmode/) | Режим обертки T (V). |

## Structures

| Структура | Описание |
| --- | --- |
| [AttributeFormatTuple](./attributeformattuple/) |  |
| [MaterialChannel](./materialchannel/) | Представляет субканал материала, который обычно содержит текстуру. |
| [NodeCurveSamplers](./nodecurvesamplers/) | Представляет прокси для доступа к кривым анимации [`Node`](../aspose.cad.fileformats.glb/node/). Используйте [`GetCurveSamplers`](../aspose.cad.fileformats.glb/node/getcurvesamplers/) для доступа. |
| [ValueLocationTuple](./valuelocationtuple/) |  |
| [VertexBuilderTuple&lt;TvG, TvM, TvS&gt;](./vertexbuildertuple-3/) |  |
| [VertexColor2Texture2Tuple](./vertexcolor2texture2tuple/) |  |
| [VertexColor2TextureTuple](./vertexcolor2texturetuple/) |  |
| [VertexColorTexture2Tuple](./vertexcolortexture2tuple/) |  |
| [VertexColorTextureTuple](./vertexcolortexturetuple/) |  |
| [VertexGeometryTuple](./vertexgeometrytuple/) |  |
| [VertexTextureTuple](./vertextexturetuple/) |  |

## Делегаты

| Делегат | Описание |
| --- | --- |
| [FileReaderCallback](./filereadercallback/) | Обратный вызов, используемый для загрузки связанных файлов текущей модели. |
| [ImageDecodeCallback](./imagedecodecallback/) | Обратный вызов, используемый для перехвата загрузки текстур, чтобы их мог декодировать клиентский движок и загрузить на GPU при необходимости. |
| [JsonFilterCallback](./jsonfiltercallback/) | Обратный вызов, используемый для предварительной обработки и постобработки JSON перед чтением и после записи. |
| [UriResolver](./uriresolver/) |  |

