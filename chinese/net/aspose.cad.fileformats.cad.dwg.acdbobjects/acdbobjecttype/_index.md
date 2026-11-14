---
title: "AcDbObjectType 枚举"
linktitle: "AcDbObjectType"
articleTitle: "AcDbObjectType"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.Dwg.AcDBObjects.AcDbObjectType 枚举。内部 Dwg 实体类型代码。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.cad.dwg.acdbobjects/acdbobjecttype/"
product_version: "26.9"
---
## AcDbObjectType enumeration

内部 Dwg 实体类型代码。

```csharp
public enum AcDbObjectType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| UNUSED | `0` | 未使用 |
| TEXT | `1` | 文本 |
| ATTRIB | `2` | 属性 |
| ATTDEF | `3` | 属性定义 |
| BLOCK | `4` | 块 |
| ENDBLK | `5` | 结束块 |
| SEQEND | `6` | 实体 |
| INSERT | `7` | 插入 |
| MINSERT | `8` | 实体 |
| VERTEX_2D | `10` | 2D 顶点 |
| VERTEX_3D | `11` | 3D 顶点 |
| VERTEX_MESH | `12` | 顶点网格 |
| VERTEX_PFACE | `13` | 顶点面 |
| VERTEX_PFACE_FACE | `14` | 顶点面 |
| POLYLINE_2D | `15` | 2D 多段线 |
| POLYLINE_3D | `16` | 3D 多段线 |
| ARC | `17` | 弧线 |
| CIRCLE | `18` | 圆 |
| LINE | `19` | 线条 |
| DIMENSION_ORDINATE | `20` | 该维度坐标 |
| DIMENSION_LINEAR | `21` | 该线性维度 |
| DIMENSION_ALIGNED | `22` | 该对齐维度 |
| DIMENSION_ANG_3Pt | `23` | 该三点角度维度 |
| DIMENSION_ANG_2Ln | `24` | 该角度维度 |
| DIMENSION_RADIUS | `25` | 该半径维度 |
| DIMENSION_DIAMETER | `26` | 该直径维度 |
| POINT | `27` | 该点 |
| FACE3D | `28` | 该三维面 |
| POLYLINE_PFACE | `29` | 该多段线面 |
| POLYLINE_MESH | `30` | 该多段线网格 |
| SOLID | `31` | 该实体 |
| TRACE | `32` | 该轨迹 |
| SHAPE | `33` | 该形状 |
| VIEWPORT | `34` | 该视口 |
| ELLIPSE | `35` | 该椭圆 |
| SPLINE | `36` | 该样条 |
| REGION | `37` | 该区域 |
| SOLID3D | `38` | 该三维实体 |
| BODY | `39` | 该主体 |
| RAY | `40` | 该射线 |
| XLINE | `41` | 线条 |
| DICTIONARY | `42` | 字典 |
| OLEFRAME | `43` | 该 OLE 框架 |
| MTEXT | `44` | 文本 |
| LEADER | `45` | 该引线 |
| TOLERANCE | `46` | 该公差 |
| MLINE | `47` | 线条 |
| BLOCK_CONTROL | `48` | 该块控制 |
| BLOCK_HEADER | `49` | 该块标题 |
| LAYER_CONTROL | `50` | 该图层控制 |
| LAYER | `51` | 该图层 |
| STYLE_CONTROL | `52` | 该样式控制 |
| STYLE | `53` | 该样式 |
| LTYPE_CONTROL | `56` | 该线型控制 |
| LTYPE | `57` | 该类型 |
| VIEW_CONTROL | `60` | 该视图控制 |
| VIEW | `61` | 该视图 |
| UCS_CONTROL | `62` | 该UCS控制 |
| UCS | `63` | 实体 |
| VPORT_CONTROL | `64` | 该视口控制 |
| VPORT | `65` | 该视口 |
| APPID_BLOCK | `66` | 该应用程序 ID 块 |
| APPID | `67` | 该应用程序 ID |
| DIMSTYLE_BLOCK | `68` | 该标注样式块 |
| DIMSTYLE | `69` | 该标注样式 |
| VP_ENT_HDR | `71` | 实体 |
| GROUP | `72` | 该组 |
| MLINESTYLE | `73` | 该线型样式 |
| OLE2FRAME | `74` | 该 OLE 框架 |
| DUMMY | `75` | 该虚拟 |
| LONG_TRANSACTION | `76` | 该长事务 |
| LWPOLYLINE | `77` | 该多段线 |
| HATCH | `78` | 该填充 |
| XRECORD | `79` | 该记录 |
| ACDBPLACEHOLDER | `80` | 该占位符 |
| VBA_PROJECT | `81` | 该 Visual Basic 项目 |
| LAYOUT | `82` | 布局 |
| ACAD_TABLE | `83` | 表格 |
| TABLECONTENT | `84` | 表格内容 |
| CELLSTYLEMAP | `85` | 单元格样式映射 |
| DBCOLOR | `86` | 颜色 |
| DICTIONARYVAR | `87` | 字典实体 |
| FIELD | `88` | 字段 |
| GROUP_500 | `89` | 该组 |
| HATCH_500 | `90` | 该填充 |
| IDBUFFER | `91` | ID 缓冲区 |
| IMAGE | `92` | 图像 |
| IMAGEDEF | `93` | 图像定义 |
| IMAGEDEFREACTOR | `94` | 图像反应器 |
| LAYER_INDEX | `95` | 图层索引 |
| LIGHT | `96` | 用于 3D 渲染的光照 |
| LWPLINE | `97` | 线条 |
| MATERIAL | `98` | 材质 |
| MLEADER | `99` | 该引线 |
| MLEADERSTYLE | `100` | 引导线样式 |
| MESH | `101` | 网格 |
| OLE2FRAME_500 | `102` | 该 OLE 框架 |
| PLACEHOLDER | `103` | 该占位符 |
| PLOTSETTINGS | `104` | 绘图设置 |
| RASTERVARIABLES | `105` | 光栅变量 |
| SCALE | `106` | 比例 |
| SORTENTSTABLE | `107` | 排序表 |
| SPATIAL_FILTER | `108` | 空间过滤器 |
| SPATIAL_INDEX | `109` | 空间索引 |
| SUN | `110` | 用于 3D 渲染的阳光 |
| TABLEGEOMETRY | `111` | 表格几何 |
| TABLESTYLES | `112` | 表格样式 |
| SECTIONVIEWSTYLE | `113` | 截面视图样式 |
| DETAILVIEWSTYLE | `114` | 该 详细视图样式 |
| RAPIDRTRENDERSETTINGS | `115` | 该 快速 rt 渲染 设置 |
| ACDBPERSSUBENTMANAGER | `116` | 该 pers subent 管理器 |
| ACDBASSOCPERSSUBENTMANAGER | `117` | 该 assoc pers subent 管理器 |
| ACAD_EVALUATION_GRAPH | `118` | 该 acad 评估图 |
| DIMASSOC | `119` | 该 dim 关联 |
| ARC_DIMENSION | `120` | 该 弧维度 |
| LARGE_RADIAL_DIMENSION | `121` | 该 锯齿维度 |
| FIELDLIST | `122` |  |
| SOLID_BACKGROUND | `123` | 该 实体 背景 |
| GRADIENT_BACKGROUND | `124` | 该 渐变背景 |
| SKYLIGHT_BACKGROUND | `125` | 该 skyLight 背景 |
| ACSH_BOX_CLASS | `126` | 该 Acsh Box Class |
| ACSH_CONE_CLASS | `127` | 该 Acsh Cone Class |
| ACSH_CYLINDER_CLASS | `128` | 该 Acsh Cylinder Class |
| ACSH_PYRAMID_CLASS | `129` | 该 Acsh Pyramid Class |
| ACSH_SPHERE_CLASS | `130` | 该 Acsh Sphere Class |
| ACSH_TORUS_CLASS | `131` | 该 Acsh Torus Class |
| ACSH_WEDGE_CLASS | `132` | 该 Acsh Wedge Class |
| VLO_VL | `133` | 该 VLO-VL 对象 |
| LSDEFINITION | `134` | 该 LSDEFINITION 对象 |
| LSSTROKEPATTERNCOMPONENT | `135` | 该 LSSTROKEPATTERNCOMPONENT 对象 |
| LSINTERNALCOMPONENT | `136` | 该 LSINTERNALCOMPONENT 对象 |
| LSCOMPOUNDCOMPONENT | `137` | 该 LSCOMPOUNDCOMPONENT 对象 |
| LSPOINTCOMPONENT | `138` | 该 LSPOINTCOMPONENT 对象 |
| LSSYMBOLCOMPONENT | `139` | 该 LSSYMBOLCOMPONENT 对象 |
| ACDBASSOCNETWORK | `140` | 该 ACDBASSOCNETWORK |
| ACDBASSOCVARIABLE | `141` | 该 ACDBASSOCVARIABLE |
| ACDBASSOC2DCONSTRAINTGROUP | `142` | 该 ACDBASSOC2DCONSTRAINTGROUP |
| ACDBASSOCDEPENDENCY | `143` | 该 ACDBASSOCDEPENDENCY |
| ACDBASSOCVALUEDEPENDENCY | `144` | 该 ACDBASSOCVALUEDEPENDENCY |
| ACDBASSOCGEOMDEPENDENCY | `145` | 该 ACDBASSOCGEOMDEPENDENCY |
| ACDB_BLKREFOBJECTCONTEXTDATA_CLASS | `146` | 该 块引用对象上下文数据 |
| ACDB_TEXTOBJECTCONTEXTDATA_CLASS | `147` | 该 文本对象上下文数据 |
| ACDB_MTEXTATTRIBUTEOBJECTCONTEXTDATA_CLASS | `148` | 该 多行文字属性对象上下文数据 |
| ACDB_MTEXTOBJECTCONTEXTDATA_CLASS | `149` | 该 多行文字对象上下文数据 |
| ACDB_ALDIMOBJECTCONTEXTDATA_CLASS | `150` | 该 对齐标注对象上下文数据 |
| ACDB_ANGDIMOBJECTCONTEXTDATA_CLASS | `151` | 该 角度标注对象上下文数据 |
| ACDB_LEADEROBJECTCONTEXTDATA_CLASS | `152` | 该 引线对象上下文数据 |
| ACDB_MLEADEROBJECTCONTEXTDATA_CLASS | `153` | 该 多重引线对象上下文数据 |
| ACDB_HATCHSCALECONTEXTDATA_CLASS | `154` | 该 填充比例上下文数据 |
| ACDB_RADIMOBJECTCONTEXTDATA_CLASS | `155` | 该 径向标注对象上下文数据 |
| ACDB_RADIMLRGOBJECTCONTEXTDATA_CLASS | `156` | 该 大径向标注对象上下文数据 |
| ACDB_DMDIMOBJECTCONTEXTDATA_CLASS | `157` | 该 直径标注对象上下文数据 |
| ACDB_ORDDIMOBJECTCONTEXTDATA_CLASS | `158` | 该 坐标标注对象上下文数据 |
| ACDB_FCFOBJECTCONTEXTDATA_CLASS | `159` | 该 特征控制框对象上下文数据 |
| VBA_PROJECT_500 | `160` | 该 项目 |
| VISUALSTYLE | `161` | 视觉样式 |
| WIPEOUTVARIABLE | `162` | 该 擦除变量 |
| XRECORD_500 | `163` | 该记录 |
| DGNUNDERLAY | `164` | 该 dgn底图 |
| DGNDEFINITION | `165` | 该 dgn定义 |
| DWFUNDERLAY | `166` | 该 dwf底图 |
| DWFDEFINITION | `167` | 该 dwf定义 |
| PDFUNDERLAY | `168` | 该 pdf底图 |
| PDFDEFINITION | `169` | 该 pdfdefinition |
| AECIDBIMAGEDEF | `170` | 该嵌入图像定义 |
| IMAGEDATA | `171` | 该嵌入图像数据 |
| EMBEDDEDIMAGE | `172` | 该嵌入图像 |
| ACIDBLOCKREFERENCE | `173` | 该块引用 |
| ACAD_PROXY_ENTITY | `498` | 该 ACAD_PROXY_ENTITY |
| ACAD_PROXY_OBJECT | `499` | 该 ACAD_PROXY_OBJECT |
| WIPEOUT | `509` | 该擦除 |
| HISTORY | `518` | 该历史 |
| PLANESURFACE | `522` | 该平面表面 |
| EXTRUDEDSURFACE | `527` | 该拉伸表面 |
| REVOLVEDSURFACE | `534` | 该旋转表面 |
| LOFTEDSURFACE | `536` | 放样表面 |
| SWEPTSURFACE | `538` | 该扫掠表面 |
| R11_COMMON_POLYLINE | `4097` | 任意代理代码用于 R11 polyline 实体，以创建中间读取器，该读取器为特定 polyline 类型创建读取器。若干扰任何内容，请随意更改。 |
| R11_COMMON_VERTEX | `4098` | 任意代理代码用于 R11 vertex 实体，以创建中间读取器，该读取器为特定 vertex 类型创建读取器。若干扰任何内容，请随意更改。 |
| R11_COMMON_DIMENSION | `4099` | 任意代理代码用于 R11 dimension 实体，以创建中间读取器，该读取器为特定 dimension 类型创建读取器。若干扰任何内容，请随意更改。 |
| DICTIONARYWDFLT | `70` | 该 DICTIONARYWDFLT |

### 另请参阅

* namespace [Aspose.CAD.FileFormats.Cad.Dwg.AcDBObjects](../../aspose.cad.fileformats.cad.dwg.acdbobjects/)
* assembly [Aspose.CAD](../../)

