---
title: "Aspose.CAD.FileFormats.Collada.FileParser.Elements"
linktitle: "Aspose.CAD.FileFormats.Collada.FileParser.Elements"
articleTitle: "Aspose.CAD.FileFormats.Collada.FileParser.Elements"
second_title: "Aspose.CAD for .NET API 参考"
description: "用于处理 Collada 文件元素的解析器。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.collada.fileparser.elements/"
keywords: "Aspose.CAD.FileFormats.Collada.FileParser.Elements, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Overview

用于处理 [Collada](./collada/) 文件元素的解析器。

是 [Aspose.CAD for .NET](../) API 参考的一部分。

## 类

| 类 | 描述 |
| --- | --- |
| [Accessor](./accessor/) | 访问器。accessor 元素声明对数组元素之一的访问模式：FLOAT_ARRAY、INT_ARRAY、NAME_ARRAY、BOOL_ARRAY、TOKEN_ARRAY 和 IDREF_ARRAY。accessor 元素描述对数组的访问方式，这些数组可以根据 offset 和 stride 属性以交错或非交错方式组织。 |
| [Altitude](./altitude/) | 海拔。海拔始终以米为单位。如果模式为 "absolute"，则该值解释为相对于平均海平面的米数。如果模式为 "relativeToGround"，则该值解释为该位置实际地面海拔以上的米数。 |
| [Asset](./asset/) | COLLADA 资产。asset 元素定义了关于其父元素的资产管理信息。 |
| [AssetUnit](./assetunit/) | 资产单位。unit 元素包含有关计量单位的描述信息。它具有单位名称和相对于米的测量属性。unit 元素可能出现零次或一次。 |
| [Bind](./bind/) | 绑定。bind 元素在实例化时将值绑定到 effect 参数。 |
| [BindMaterial](./bindmaterial/) | 绑定材质。将特定材质绑定到几何体的某个部分，同时绑定 varying 和 uniform 参数。 |
| [BindVertexInput](./bindvertexinput/) | 绑定顶点输入。bind_vertex_input 元素在实例化时将顶点输入绑定到 effect 参数。 |
| [BoolArray](./boolarray/) | 布尔数组。BOOL_ARRAY 元素声明用于存储布尔值同质数组的存储空间。 |
| [Brep](./brep/) | BREP。描述边界表示 (BREP) 结构。 |
| [Camera](./camera/) | 相机。声明视觉场景层次结构或场景图的视图。 |
| [CameraOptics](./cameraoptics/) | 相机光学。表示相机上将图像投射到图像传感器的装置。 |
| [CameraOpticsTechniqueCommon](./cameraopticstechniquecommon/) | 相机光学通用技术。 |
| [CameraOpticsTechniqueCommonOrthographic](./cameraopticstechniquecommonorthographic/) | 相机光学通用正交技术。描述正交相机的视场。 |
| [CameraOpticsTechniqueCommonPerspective](./cameraopticstechniquecommonperspective/) | 相机光学通用透视技术。描述透视相机的视场。 |
| [Circle](./circle/) | 圆形。 |
| [Collada](./collada/) | COLLADA 元素声明文档的根，该文档包含 COLLADA 架构中的部分内容。 |
| [ColladaElement](./colladaelement/) | 基础 COLLADA 元素。 |
| [Cone](./cone/) | 圆锥。描述圆锥形表面。 |
| [Contributor](./contributor/) | 贡献者。贡献者元素定义了资产管理的创作信息。 |
| [ControlVertices](./controlvertices/) | 控制顶点。它用于描述样条曲线的 CV。 |
| [ConvexMesh](./convexmesh/) | 凸面网格。convex_mesh 元素的定义与 mesh 元素相同，唯一的例外是它可以不提供完整的描述（来源、顶点、多边形等），而是简单地指向另一个几何体以获取其形状。后一种情况意味着应计算该几何体的凸包，并通过可选的 "convex_hull_of" 属性指示。 |
| [Coverage](./coverage/) | 覆盖范围。使用 WGS84 坐标系指定资产的位置。 |
| [Curve](./curve/) | 曲线。 |
| [Curves](./curves/) | 曲线。此元素包含所有用于拓扑实体边的几何描述所需的曲线。 |
| [Cylinder](./cylinder/) | 圆柱体。描述一个无限的圆柱面。 |
| [Edges](./edges/) | 边。边由两个顶点限定，并具有用于几何表示的曲线。该曲线的段也受其起始和结束参数的限制。 |
| [Effect](./effect/) | 效果。对 SHADER 效果的自包含描述。 |
| [Ellipse](./ellipse/) | 椭圆。 |
| [EvaluateScene](./evaluatescene/) | 评估场景。evaluate_scene 元素声明了指定如何评估此 visual_scene 的信息。可以存在任意数量的 evaluate_scene 元素。它们按顺序进行评估，特定的元素可以通过设置 enabled=false 来禁用。 |
| [Extra](./extra/) | COLLADA 资产额外信息。extra 元素声明了关于其父元素的附加信息。 |
| [Faces](./faces/) | 面。面由一个或多个线框限定。 |
| [FloatArray](./floatarray/) | 浮点数组。float_array 元素声明了用于存储同质浮点值数组的存储空间。 |
| [FxCommonColorOrTexture](./fxcommoncolorortexture/) | FX 通用颜色或纹理。描述固定功能 SHADER 元素颜色属性的类型。 |
| [FxCommonColorOrTextureColor](./fxcommoncolorortexturecolor/) | FX 通用颜色或纹理颜色。包含四个描述 RGBA 颜色的浮点值。 |
| [FxCommonColorOrTextureParam](./fxcommoncolorortextureparam/) | FX 通用颜色或纹理参数。引用预定义的参数。 |
| [FxCommonColorOrTextureTexture](./fxcommoncolorortexturetexture/) | FX 通用颜色或纹理纹理。 |
| [FxCommonFloatOrParameter](./fxcommonfloatorparameter/) | FX 通用浮点或参数。描述固定功能 SHADER 元素的标量属性。 |
| [FxCommonFloatOrParameterFloat](./fxcommonfloatorparameterfloat/) | FX 通用浮点或参数浮点。该值由文字浮点标量表示。 |
| [FxCommonFloatOrParameterParameter](./fxcommonfloatorparameterparameter/) | FX 通用浮点或参数参数。该值通过引用先前定义的参数表示，该参数可以直接转换为浮点标量。 |
| [FxCommonTransparent](./fxcommontransparent/) | FX 通用透明。 |
| [GeographicLocation](./geographiclocation/) | 地理位置。使用 WGS84 坐标系指定资产的位置。 |
| [Geometry](./geometry/) | 几何体。几何体描述场景中对象的视觉形状和外观。geometry 元素对几何信息的声明进行分类。几何学是数学的一个分支，研究点、线、角、曲面和立体的测量、属性和关系。 |
| [Hyperbola](./hyperbola/) | 双曲线。 |
| [IdRefArray](./idrefarray/) | ID ref 数组。IDREF_array 元素声明用于存储同构 ID 引用值的数组。 |
| [InputLocal](./inputlocal/) | 本地输入。input_local_type 元素用于表示只能引用同一文档中声明的资源的输入。 |
| [InputLocalOffset](./inputlocaloffset/) | 本地输入偏移。input_local_offset_type 元素用于表示只能引用同一文档中声明的资源的索引输入。 |
| [InstanceCamera](./instancecamera/) | 实例摄像机。Instance Camera 元素实例化由 camera 元素描述的对象，以在可视场景中激活它。 |
| [InstanceEffect](./instanceeffect/) | 实例效果。 |
| [InstanceGeometry](./instancegeometry/) | 实例几何体。instance_geometry 元素声明 COLLADA 几何资源的实例化。 |
| [InstanceImage](./instanceimage/) | 实例图像。 |
| [InstanceJoint](./instancejoint/) | 实例关节。 |
| [InstanceLight](./instancelight/) | 实例灯光。instance_light 元素声明 COLLADA 灯光资源的实例化。 |
| [InstanceMaterialGeometry](./instancematerialgeometry/) | 实例材质。instance_material 元素声明 COLLADA 材质资源的实例化。 |
| [InstanceMaterialRendering](./instancematerialrendering/) | 实例材质渲染。实例化用于屏幕效果的 COLLADA 材质资源。 |
| [InstanceNode](./instancenode/) | 实例节点。instance_node 元素声明 COLLADA 节点资源的实例化。 |
| [InstancePhysicsMaterial](./instancephysicsmaterial/) | 实例物理材质。 |
| [InstanceVisualScene](./instancevisualscene/) | 实例可视场景。 |
| [InstanceWithExtra](./instancewithextra/) | 带额外信息的实例。instance_with_extra_type 元素用于所有通用实例元素。通用实例元素是指没有声明任何特定子元素的实例元素。 |
| [IntArray](./intarray/) | 整数数组。INT_ARRAY 元素声明用于存储同构整数值的数组。 |
| [LibraryCameras](./librarycameras/) | 摄像机库。提供用于放置 camera 元素的库。 |
| [LibraryEffects](./libraryeffects/) | 效果库。library_effects 元素声明一个效果元素模块。 |
| [LibraryGeometries](./librarygeometries/) | 几何体库。library_geometries 元素声明一个几何元素模块。 |
| [LibraryMaterials](./librarymaterials/) | 材质库。library_materials 元素声明一个材质元素模块。 |
| [LibraryNodes](./librarynodes/) | 节点库。提供用于放置 node 元素的库。 |
| [LibraryVisualScenes](./libraryvisualscenes/) | 可视场景库。library_visual_scenes 元素声明一个 visual_scene 元素模块。 |
| [Line](./line/) | 线段。 |
| [Lines](./lines/) | 线段集合。lines 元素提供将顶点属性绑定在一起并将这些顶点组织成单独线段所需的信息。网格描述的每条线都有两个顶点。第一条线由第一和第二顶点组成。第二条线由第三和第四顶点组成，依此类推。 |
| [Linestrips](./linestrips/) | 线条带。linEStrips 元素提供将顶点属性绑定在一起并将这些顶点组织成相连线条带所需的信息。网格描述的每个线条带具有任意数量的顶点。线条带内的每个线段由当前顶点和前一个顶点组成。 |
| [Lookat](./lookat/) | 视点。视点元素包含适用于对准摄像机的位置和方向变换。视点元素内部包含三个数学向量，描述：1. 对象的位置；2. 关注点的位置；3. 向上的方向。 |
| [Material](./material/) | 材质。材质描述几何对象的视觉外观。 |
| [Matrix](./matrix/) | 矩阵。矩阵变换体现对坐标系内点或坐标系本身的数学变化。矩阵元素包含一个 4×4 的浮点值矩阵。 |
| [Mesh](./mesh/) | 网格。网格元素包含足以描述基本几何网格的顶点和基元信息。 |
| [NameArray](./namearray/) | 名称数组。Name_array 元素声明用于存储同质名称字符串值数组的存储空间。 |
| [Node](./node/) | 节点。节点体现场景中元素的层次关系。 |
| [Nurbs](./nurbs/) | NURBS。描述三维空间中的 NURBS 曲线。 |
| [NurbsSurface](./nurbssurface/) | NURBS 表面。描述三维空间中的 NURBS 表面。 |
| [Orient](./orient/) | 方向。描述对象坐标系的方向。方向由任意轴和角度给出。 |
| [Origin](./origin/) | 原点。描述对象坐标系的原点。原点由三维空间中的位置给出。 |
| [Parabola](./parabola/) | 抛物线。 |
| [Parameter](./parameter/) | 参数。parameter 元素声明其父元素的参数信息。 |
| [ParametricCurves](./parametriccurves/) | 参数曲线。指定在面参数空间中如何表示一条边。 |
| [Plane](./plane/) | 平面。定义一个无限平面。 |
| [Polygons](./polygons/) | 多边形。polygons 元素提供将顶点属性绑定在一起并将这些顶点组织成单个多边形所需的信息。所描述的多边形可以包含任意数量的顶点。这些多边形可能自相交，也可能包含孔洞。 |
| [Polylist](./polylist/) | POLYLIST。POLYLIST 元素提供将顶点属性绑定在一起并将这些顶点组织成单个多边形所需的信息。POLYLIST 中描述的多边形可以包含任意数量的顶点。与 polygons 元素不同，POLYLIST 元素不能包含带孔的多边形。 |
| [Primitives](./primitives/) | 基元。primitives 元素表示针对基元类型的基元数据。primitives 元素包含索引，这些索引引用输入元素所指向的父级源元素。 |
| [PrimitivesWithHoles](./primitiveswithholes/) | 带孔基元。描述包含一个或多个孔洞的基元。 |
| [ProfileBridge](./profilebridge/) | profile bridge。将 COLLADA FX 桥接到外部 FX 框架，例如 NVIDIA 的 CgFX 或 Microsoft 的 Direct3D FX。 |
| [ProfileCommon](./profilecommon/) | profile common。打开一段 COMMON 平台特定的数据类型和技术声明块。 |
| [ProfileCommonTechnique](./profilecommontechnique/) | profile common technique。包含使用一种方法渲染此效果所需的纹理、采样器、SHADERS、参数和通道的描述。 |
| [Render](./render/) | evaluate scene render。描述用于评估场景的一个效果通道。 |
| [Rotate](./rotate/) | 旋转。rotate 元素包含一个角度和一个表示旋转轴的数学向量。 |
| [Scale](./scale/) | 缩放。scale 元素包含一个表示坐标系 X、Y、Z 轴相对比例的数学向量。 |
| [Scene](./scene/) | 场景。scene 包含可以从 COLLADA 资源内容中可视化的全部信息。scene 元素声明场景层次结构或场景图的基础。scene 包含由创作工具生成的大量视觉和变换信息内容的元素。 |
| [Shells](./shells/) | 该 shells。描述 B-rep 结构的 shells。一个 shell 是一个或多个 faces 的并集。闭合的 shell 可以限制一个 solid。 |
| [SidRefArray](./sidrefarray/) | 该 sid ref array。SIDREF_array 元素声明用于存储同质 SID 引用值数组的存储空间。 |
| [Skew](./skew/) | 该 skew。skew 元素包含一个角度和两个数学向量，分别表示旋转轴和位移轴。 |
| [Solids](./solids/) | 该 solids。此元素定义在 BREP 结构中使用的所有 solids。 |
| [Source](./source/) | 该 source。source 元素声明一个数据仓库，根据引用它的输入元素的语义提供值。 |
| [Sphere](./sphere/) | 该 sphere。描述一个以其局部原点为中心的 sphere。 |
| [Spline](./spline/) | 该 spline。spline 元素包含足以描述基本 splines 的控制顶点信息。 |
| [Surface](./surface/) | 该 surface。surface 定义 surface 元素的属性。通过 rotate 和 translate，surface 可以定位到正确的位置。 |
| [SurfaceCurves](./surfacecurves/) | 该 surface curves。曲线位于 surface 的参数空间中。 |
| [Surfaces](./surfaces/) | 该 surfaces。包含在 B-rep 结构中使用的所有 surfaces。 |
| [SweptSurface](./sweptsurface/) | 该 swept surface。通过拉伸或旋转曲线来描述一个 surface。 |
| [TargetableFloat](./targetablefloat/) | 该 targetable float。targetable_float_type 元素用于表示包含可用于动画的单个 float 值的元素。 |
| [TargetableFloat3](./targetablefloat3/) | 该 target able float 3。 |
| [TargetableFloat4](./targetablefloat4/) | 该 target able float 4。 |
| [Technique](./technique/) | 该 technique。technique 元素声明用于处理内容某部分的信息。每个 technique 符合关联的 profile。technique 通常充当“开关”。如果对特定内容部分存在多个 technique，在导入时会选择其一，通常不会同时使用两个。选择应基于导入应用程序能够支持的 profile。technique 包含应用数据和程序，使其成为可以作为整体管理的资产。 |
| [TechniqueBlinn](./techniqueblinn/) | 该 technique BLINN。使用 BLINN BRDF 近似生成带阴影的 surface。 |
| [TechniqueCommon](./techniquecommon/) | 该 technique common。technique common 指定访问此 source 元素数据的通用方法。 |
| [TechniqueConstant](./techniqueconstant/) | 该 technique constant。生成一个不受光照影响的持续阴影 surface。 |
| [TechniqueHint](./techniquehint/) | 该 technique hint。为平台添加使用哪种 technique 的提示。 |
| [TechniqueLambert](./techniquelambert/) | 该 technique lambert。生成一个不受光照影响的漫反射阴影 surface。 |
| [TechniqueOverride](./techniqueoverride/) | 该 technique override。针对材质内部的特定 technique 和 pass，而不是将 effects 的 technique 和 pass 拆分为多个 effects。 |
| [TechniquePhong](./techniquephong/) | 该 technique PHONG。生成一个根据 PHONG BRDF 近似进行高光反射阴影的 surface。 |
| [TokenArray](./tokenarray/) | 该 token array。token_array_type 元素声明用于存储同质 token 字符串值数组的存储空间。 |
| [Torus](./torus/) | 该 torus。描述三维空间中的 torus。 |
| [Translate](./translate/) | 该 translate。translate 元素包含一个数学向量，表示沿 X、Y、Z 轴的距离。 |
| [Triangles](./triangles/) | 三角形。三角形元素提供绑定顶点属性所需的信息，然后将这些顶点组织成单独的三角形。网格描述的每个三角形有三个顶点。第一个三角形由第一、第二和第三个顶点组成。第二个三角形由第四、第五和第六个顶点组成，依此类推。 |
| [Trifans](./trifans/) | TRIFANS。TRIFANS 元素提供绑定顶点属性所需的信息，然后将这些顶点组织成相连的三角形。网格描述的每个三角形有三个顶点。第一个三角形由第一、第二和第三个顶点组成。每个后续三角形由当前顶点形成，重复使用第一个和前一个顶点。 |
| [Tristrips](./tristrips/) | TRISTRIPS。TRISTRIPS 元素提供绑定顶点属性所需的信息，然后将这些顶点组织成相连的三角形。网格描述的每个三角形有三个顶点。第一个三角形由第一、第二和第三个顶点组成。每个后续三角形由当前顶点形成，重复使用前两个顶点。 |
| [Vertices](./vertices/) | 顶点。顶点元素声明网格顶点的属性和标识。顶点元素描述网格几何中的网格顶点。网格顶点表示组成网格的顶点的位置（标识）以及对细分保持不变的其他顶点属性。 |
| [VisualScene](./visualscene/) | 可视场景。visual_scene 元素声明 visual_scene 层次结构或场景图的基础。场景包含由创作工具创建的、构成大量可视和变换信息内容的元素。 |
| [Wires](./wires/) | 线。线是一个或多个边的组合。闭合的线可以限制一个面。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [EnumAltitudeMode](./enumaltitudemode/) | 海拔模式。geographic_location 元素中 altitude 元素的 mode 属性的合法取值。 |
| [EnumChoiceSweptType](./enumchoiceswepttype/) | choice swept 类型的枚举。 |
| [EnumFxOpaque](./enumfxopaque/) | FX opaque 枚举成员。 |
| [EnumFxSamplerMagFilter](./enumfxsamplermagfilter/) | FX sampler mag filter 枚举。 |
| [EnumFxSamplerMinFilter](./enumfxsamplerminfilter/) | FX sampler min filter 枚举。 |
| [EnumFxSamplerMipFilter](./enumfxsamplermipfilter/) | FX sampler MIP filter 枚举。 |
| [EnumFxSamplerWrap](./enumfxsamplerwrap/) | FX sampler wrap 枚举。 |
| [EnumNode](./enumnode/) | 节点类型枚举。 |
| [EnumOrthograthicItems](./enumorthograthicitems/) | ORTHOGRATHIC 项目枚举。 |
| [EnumPerspectiveItems](./enumperspectiveitems/) | Perspective 项目枚举。 |
| [EnumUpAxis](./enumupaxis/) | 上轴枚举。指定可接受上轴取值的枚举类型。 |

