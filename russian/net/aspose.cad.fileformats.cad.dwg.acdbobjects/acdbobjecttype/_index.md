---
title: "Перечисление AcDbObjectType"
linktitle: "AcDbObjectType"
articleTitle: "AcDbObjectType"
second_title: "Aspose.CAD для .NET справка API"
description: "Перечисление Aspose.CAD.FileFormats.Cad.Dwg.AcDBObjects.AcDbObjectType. Внутренние коды типов сущностей Dwg."
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.cad.dwg.acdbobjects/acdbobjecttype/"
product_version: "26.9"
---
## AcDbObjectType enumeration

Внутренние коды типов сущностей Dwg.

```csharp
public enum AcDbObjectType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| UNUSED | `0` | Неиспользуемый |
| TEXT | `1` | Текст |
| ATTRIB | `2` | Атрибут |
| ATTDEF | `3` | Определение атрибута |
| BLOCK | `4` | Блок |
| ENDBLK | `5` | Блок завершения |
| SEQEND | `6` | Сущность |
| INSERT | `7` | Вставка |
| MINSERT | `8` | Сущность |
| VERTEX_2D | `10` | 2D-вершина |
| VERTEX_3D | `11` | 3D-вершина |
| VERTEX_MESH | `12` | Сетка вершин |
| VERTEX_PFACE | `13` | Грань вершины |
| VERTEX_PFACE_FACE | `14` | Грань вершины |
| POLYLINE_2D | `15` | Полилиния 2D |
| POLYLINE_3D | `16` | Полилиния 3D |
| ARC | `17` | Дуга |
| CIRCLE | `18` | Круг |
| LINE | `19` | Линия |
| DIMENSION_ORDINATE | `20` | Размер ординаты |
| DIMENSION_LINEAR | `21` | Линейный размер |
| DIMENSION_ALIGNED | `22` | Выравненный размер |
| DIMENSION_ANG_3Pt | `23` | Угол измерения по трём точкам |
| DIMENSION_ANG_2Ln | `24` | Угол измерения |
| DIMENSION_RADIUS | `25` | Радиус измерения |
| DIMENSION_DIAMETER | `26` | Диаметр измерения |
| POINT | `27` | Точка |
| FACE3D | `28` | 3D‑поверхность |
| POLYLINE_PFACE | `29` | Поверхность полилинии |
| POLYLINE_MESH | `30` | Сетка полилинии |
| SOLID | `31` | Твёрдое тело |
| TRACE | `32` | Трасса |
| SHAPE | `33` | Форма |
| VIEWPORT | `34` | Окно просмотра |
| ELLIPSE | `35` | Эллипс |
| SPLINE | `36` | Сплайн |
| REGION | `37` | Область |
| SOLID3D | `38` | 3D‑твердое тело |
| BODY | `39` | Тело |
| RAY | `40` | Луч |
| XLINE | `41` | Линия |
| DICTIONARY | `42` | Словарь |
| OLEFRAME | `43` | OLE‑кадр |
| MTEXT | `44` | Текст |
| LEADER | `45` | Выноска |
| TOLERANCE | `46` | Допуск |
| MLINE | `47` | Линия |
| BLOCK_CONTROL | `48` | Этот блок управления |
| BLOCK_HEADER | `49` | Этот заголовок блока |
| LAYER_CONTROL | `50` | Этот контроль слоя |
| LAYER | `51` | Этот слой |
| STYLE_CONTROL | `52` | Этот контроль стиля |
| STYLE | `53` | Этот стиль |
| LTYPE_CONTROL | `56` | Этот контроль ltype |
| LTYPE | `57` | Этот тип |
| VIEW_CONTROL | `60` | Этот контроль просмотра |
| VIEW | `61` | Этот вид |
| UCS_CONTROL | `62` | Этот контроль UCS |
| UCS | `63` | Сущность |
| VPORT_CONTROL | `64` | Этот контроль VPORT |
| VPORT | `65` | Этот порт просмотра |
| APPID_BLOCK | `66` | Этот блок идентификатора приложения |
| APPID | `67` | Этот идентификатор приложения |
| DIMSTYLE_BLOCK | `68` | Этот блок стиля размеров |
| DIMSTYLE | `69` | Этот стиль размеров |
| VP_ENT_HDR | `71` | Сущность |
| GROUP | `72` | Эта группа |
| MLINESTYLE | `73` | Этот стиль линии |
| OLE2FRAME | `74` | OLE‑кадр |
| DUMMY | `75` | Эта заглушка |
| LONG_TRANSACTION | `76` | Эта длительная транзакция |
| LWPOLYLINE | `77` | Эта полилиния |
| HATCH | `78` | Эта штриховка |
| XRECORD | `79` | Эта запись |
| ACDBPLACEHOLDER | `80` | Этот заполнитель |
| VBA_PROJECT | `81` | Этот проект Visual Basic |
| LAYOUT | `82` | Этот макет |
| ACAD_TABLE | `83` | Эта таблица |
| TABLECONTENT | `84` | Содержание таблицы |
| CELLSTYLEMAP | `85` | Карта стилей ячеек |
| DBCOLOR | `86` | Этот цвет |
| DICTIONARYVAR | `87` | Сущность словаря |
| FIELD | `88` | Это поле |
| GROUP_500 | `89` | Эта группа |
| HATCH_500 | `90` | Эта штриховка |
| IDBUFFER | `91` | Буфер идентификаторов |
| IMAGE | `92` | Это изображение |
| IMAGEDEF | `93` | Определение изображения |
| IMAGEDEFREACTOR | `94` | Реактор изображения |
| LAYER_INDEX | `95` | Индекс слоя |
| LIGHT | `96` | Свет для 3D-рендеринга |
| LWPLINE | `97` | Линия |
| MATERIAL | `98` | Этот материал |
| MLEADER | `99` | Выноска |
| MLEADERSTYLE | `100` | Стиль лидера |
| MESH | `101` | Сетка |
| OLE2FRAME_500 | `102` | OLE‑кадр |
| PLACEHOLDER | `103` | Этот заполнитель |
| PLOTSETTINGS | `104` | Настройки построения |
| RASTERVARIABLES | `105` | Растровые переменные |
| SCALE | `106` | Масштаб |
| SORTENTSTABLE | `107` | Таблица сортировки |
| SPATIAL_FILTER | `108` | Пространственный фильтр |
| SPATIAL_INDEX | `109` | Пространственный индекс |
| SUN | `110` | Солнце для 3D-рендеринга |
| TABLEGEOMETRY | `111` | Геометрия таблицы |
| TABLESTYLES | `112` | Стили таблицы |
| SECTIONVIEWSTYLE | `113` | Стиль представления секции |
| DETAILVIEWSTYLE | `114` | Стиль детального представления |
| RAPIDRTRENDERSETTINGS | `115` | Настройка быстрого rt-рендеринга |
| ACDBPERSSUBENTMANAGER | `116` | Менеджер pers subent |
| ACDBASSOCPERSSUBENTMANAGER | `117` | Менеджер assoc pers subent |
| ACAD_EVALUATION_GRAPH | `118` | Граф оценки acad |
| DIMASSOC | `119` | dim assoc |
| ARC_DIMENSION | `120` | Размер дуги |
| LARGE_RADIAL_DIMENSION | `121` | Размер с зазубринами |
| FIELDLIST | `122` |  |
| SOLID_BACKGROUND | `123` | Сплошной фон |
| GRADIENT_BACKGROUND | `124` | Градиентный фон |
| SKYLIGHT_BACKGROUND | `125` | Фон skyLight |
| ACSH_BOX_CLASS | `126` | Класс Acsh Box |
| ACSH_CONE_CLASS | `127` | Класс Acsh Cone |
| ACSH_CYLINDER_CLASS | `128` | Класс Acsh Cylinder |
| ACSH_PYRAMID_CLASS | `129` | Класс Acsh Pyramid |
| ACSH_SPHERE_CLASS | `130` | Класс Acsh Sphere |
| ACSH_TORUS_CLASS | `131` | Класс Acsh Torus |
| ACSH_WEDGE_CLASS | `132` | Класс Acsh Wedge |
| VLO_VL | `133` | Объект VLO-VL |
| LSDEFINITION | `134` | Объект LSDEFINITION |
| LSSTROKEPATTERNCOMPONENT | `135` | Объект LSSTROKEPATTERNCOMPONENT |
| LSINTERNALCOMPONENT | `136` | Объект LSINTERNALCOMPONENT |
| LSCOMPOUNDCOMPONENT | `137` | Объект LSCOMPOUNDCOMPONENT |
| LSPOINTCOMPONENT | `138` | Объект LSPOINTCOMPONENT |
| LSSYMBOLCOMPONENT | `139` | Объект LSSYMBOLCOMPONENT |
| ACDBASSOCNETWORK | `140` | Элемент ACDBASSOCNETWORK |
| ACDBASSOCVARIABLE | `141` | Эта ACDBASSOCVARIABLE |
| ACDBASSOC2DCONSTRAINTGROUP | `142` | Элемент ACDBASSOC2DCONSTRAINTGROUP |
| ACDBASSOCDEPENDENCY | `143` | Элемент ACDBASSOCDEPENDENCY |
| ACDBASSOCVALUEDEPENDENCY | `144` | Элемент ACDBASSOCVALUEDEPENDENCY |
| ACDBASSOCGEOMDEPENDENCY | `145` | Элемент ACDBASSOCGEOMDEPENDENCY |
| ACDB_BLKREFOBJECTCONTEXTDATA_CLASS | `146` | Элемент данных контекста объекта блочной ссылки |
| ACDB_TEXTOBJECTCONTEXTDATA_CLASS | `147` | Элемент данных контекста текстового объекта |
| ACDB_MTEXTATTRIBUTEOBJECTCONTEXTDATA_CLASS | `148` | Элемент данных контекста объекта атрибута mtext |
| ACDB_MTEXTOBJECTCONTEXTDATA_CLASS | `149` | Элемент данных контекста объекта mtext |
| ACDB_ALDIMOBJECTCONTEXTDATA_CLASS | `150` | Элемент данных контекста выравненного объекта размерного измерения |
| ACDB_ANGDIMOBJECTCONTEXTDATA_CLASS | `151` | Элемент данных контекста углового объекта размерного измерения |
| ACDB_LEADEROBJECTCONTEXTDATA_CLASS | `152` | Элемент данных контекста объекта выноски |
| ACDB_MLEADEROBJECTCONTEXTDATA_CLASS | `153` | Элемент данных контекста объекта многократной выноски |
| ACDB_HATCHSCALECONTEXTDATA_CLASS | `154` | Элемент данных контекста масштаба штриховки |
| ACDB_RADIMOBJECTCONTEXTDATA_CLASS | `155` | Элемент данных контекста радиального объекта размерного измерения |
| ACDB_RADIMLRGOBJECTCONTEXTDATA_CLASS | `156` | Элемент данных контекста большого радиального объекта размерного измерения |
| ACDB_DMDIMOBJECTCONTEXTDATA_CLASS | `157` | Элемент данных контекста диаметрального объекта размерного измерения |
| ACDB_ORDDIMOBJECTCONTEXTDATA_CLASS | `158` | Элемент данных контекста ординатного объекта размерного измерения |
| ACDB_FCFOBJECTCONTEXTDATA_CLASS | `159` | Элемент данных контекста объекта рамки контроля функции |
| VBA_PROJECT_500 | `160` | Элемент проекта |
| VISUALSTYLE | `161` | Визуальный стиль |
| WIPEOUTVARIABLE | `162` | Элемент переменной стирания |
| XRECORD_500 | `163` | Эта запись |
| DGNUNDERLAY | `164` | Элемент dgnunderlay |
| DGNDEFINITION | `165` | Элемент dgndefinition |
| DWFUNDERLAY | `166` | Элемент dwfunderlay |
| DWFDEFINITION | `167` | Элемент dwfdefinition |
| PDFUNDERLAY | `168` | pdfunderlay |
| PDFDEFINITION | `169` | pdfdefinition |
| AECIDBIMAGEDEF | `170` | Определение встроенного изображения |
| IMAGEDATA | `171` | Данные встроенного изображения |
| EMBEDDEDIMAGE | `172` | Встроенное изображение |
| ACIDBLOCKREFERENCE | `173` | Ссылка на блок |
| ACAD_PROXY_ENTITY | `498` | ACAD_PROXY_ENTITY |
| ACAD_PROXY_OBJECT | `499` | ACAD_PROXY_OBJECT |
| WIPEOUT | `509` | Удаление |
| HISTORY | `518` | История |
| PLANESURFACE | `522` | Плоская поверхность |
| EXTRUDEDSURFACE | `527` | Выдавленная поверхность |
| REVOLVEDSURFACE | `534` | Вращаемая поверхность |
| LOFTEDSURFACE | `536` | Лофтированная поверхность |
| SWEPTSURFACE | `538` | Поверхность выдавливания |
| R11_COMMON_POLYLINE | `4097` | Произвольный прокси‑код для сущности полилинии R11, создающий промежуточный считыватель, который создает считыватель для конкретного типа полилинии. Не стесняйтесь изменять, если это мешает чему‑либо. |
| R11_COMMON_VERTEX | `4098` | Произвольный прокси‑код для сущности вершины R11, создающий промежуточный считыватель, который создает считыватель для конкретного типа вершины. Не стесняйтесь изменять, если это мешает чему‑либо. |
| R11_COMMON_DIMENSION | `4099` | Произвольный прокси‑код для сущности размер R11, создающий промежуточный считыватель, который создает считыватель для конкретного типа размера. Не стесняйтесь изменять, если это мешает чему‑либо. |
| DICTIONARYWDFLT | `70` | DICTIONARYWDFLT |

### См. также

* namespace [Aspose.CAD.FileFormats.Cad.Dwg.AcDBObjects](../../aspose.cad.fileformats.cad.dwg.acdbobjects/)
* assembly [Aspose.CAD](../../)

