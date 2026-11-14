---
title: "Aspose.CAD.FileFormats.GLB"
linktitle: "Aspose.CAD.FileFormats.GLB"
articleTitle: "Aspose.CAD.FileFormats.GLB"
second_title: "Aspose.CAD for .NET API 参考"
description: "该命名空间处理 GLB 文件格式。"
type: docs
weight: 10
url: "/net/aspose.cad.fileformats.glb/"
keywords: "Aspose.CAD.FileFormats.GLB, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## Overview

该命名空间处理 GLB 文件格式。

是 [Aspose.CAD for .NET](../) API 参考的一部分。

## 类

| 类 | 描述 |
| --- | --- |
| [Accessor](./accessor/) |  |
| [Animation](./animation/) | 关键帧动画。 |
| [AnimationChannel](./animationchannel/) |  |
| [Asset](./asset/) | 关于 glTF 资源的元数据。 |
| [Buffer](./buffer/) | 缓冲区指向二进制几何、动画或皮肤。 |
| [BufferView](./bufferview/) | 对缓冲区的视图，通常表示缓冲区的子集。 |
| [Camera](./camera/) | 相机的投影。节点 **MAY** 引用相机以应用变换，将相机放置在场景中。 |
| [ExtensionsFactory](./extensionsfactory/) | 全局扩展管理器。 |
| [ExtraProperties](./extraproperties/) | 表示所有 glTF 2 架构对象的基类。 |
| [GlbData](./glbdata/) | glTF 资源的根对象。 |
| [GlbImage](./glbimage/) |  |
| [GltfImage](./gltfimage/) |  |
| [GltfImageBase](./gltfimagebase/) | 表示可序列化 glTF schema2 对象的基类。被 [`ExtraProperties`](../aspose.cad.fileformats.glb/extraproperties/) 继承。 |
| [GltfLoadOptions](./gltfloadoptions/) | 表示 GLTF/GLB 图像的加载选项。 |
| [ImageGlb](./imageglb/) | 用于创建纹理的图像数据。图像 **MAY** 通过 URI（或 IRI）或缓冲区视图索引进行引用。 |
| [LogicalChildOfRoot](./logicalchildofroot/) | 存储在 ModelRoot 中的所有 gltf 元素必须继承此类。 |
| [Material](./material/) | 原语的材质外观。 |
| [Mesh](./mesh/) | 一组待渲染的原语。其全局变换由引用它的节点定义。 |
| [MeshGpuInstancing](./meshgpuinstancing/) | glTF 扩展为带有网格的节点定义实例属性。 |
| [MeshPrimitive](./meshprimitive/) | 几何体将使用给定的材质进行渲染。 |
| [MeshPrimitiveDracoMesh](./meshprimitivedracomesh/) | 几何体将使用给定的材质进行渲染。 |
| [Node](./node/) | 节点层次结构中的一个节点。当节点包含 `skin` 时，所有 `mesh.primitives` **MUST** 包含 `JOINTS_0` 和 `WEIGHTS_0` 属性。一个节点 **MAY** 拥有 `matrix` 或任意组合的 `translation`/`rotation`/`scale`（TRS）属性。TRS 属性会被转换为矩阵，并按 `T * R * S` 顺序后乘以组成变换矩阵；首先对顶点应用缩放，然后是旋转，最后是平移。如果未提供任何属性，变换为单位矩阵。当节点被用于动画（由 animation.channel.target 引用）时，`matrix` **MUST NOT** 出现。 |
| [PunctualLight](./punctuallight/) | 方向光、点光或聚光灯。 |
| [ReadSettings](./readsettings/) | `ReadContext` 的读取设置和基类。 |
| [Scene](./scene/) | 场景的根节点。 |
| [Skin](./skin/) | 定义皮肤的关节和矩阵。 |
| [Texture](./texture/) | 纹理及其采样器。 |
| [TextureSampler](./texturesampler/) | 纹理采样器属性，用于过滤和包装模式。 |
| [TextureTransform](./texturetransform/) | glTF 扩展，允许对每个纹理的 UV 坐标进行平移和缩放。 |
| [WriteSettings](./writesettings/) | `WriteContext` 的写入设置和基类。 |

## 接口

| 接口 | 描述 |
| --- | --- |
| [ICamera](./icamera/) | `CameraOrthographic` 和 `CameraPerspective` 的通用接口。 |
| [IMaterialParameter](./imaterialparameter/) |  |
| [IVisualNodeContainer](./ivisualnodecontainer/) | 表示视觉层次结构的抽象接口。由 [`Node`](../aspose.cad.fileformats.glb/node/) 和 [`Scene`](../aspose.cad.fileformats.glb/scene/) 实现。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AgiArticulationTransformType](./agiarticulationtransformtype/) | 此关节阶段所应用的运动类型。 |
| [AlphaMode](./alphamode/) | 材质的 Alpha 渲染模式。 |
| [AnimationInterpolationMode](./animationinterpolationmode/) | 插值算法。 |
| [BufferMode](./buffermode/) | 表示此缓冲视图应使用的 GPU 缓冲区类型的提示。 |
| [CameraType](./cameratype/) | 指定相机使用透视投影还是正交投影。 |
| [DimensionType](./dimensiontype/) | 指定访问器的元素是标量、向量还是矩阵。 |
| [EncodingType](./encodingtype/) | 访问器组件的数据类型。 |
| [IndexEncodingType](./indexencodingtype/) | 索引的数据类型。 |
| [PrimitiveType](./primitivetype/) | 要渲染的基元的拓扑类型。 |
| [PropertyPath](./propertypath/) | 要动画的节点的 TRS 属性名称，或其实例化的形变目标的权重。对于平移属性，采样器提供的值是沿 X、Y、Z 轴的平移。对于旋转属性，值是顺序为 (x, y, z, w) 的四元数，其中 w 为标量。对于缩放属性，值是沿 X、Y、Z 轴的缩放因子。 |
| [PunctualLightType](./punctuallighttype/) | 定义所有 [`PunctualLight`](../aspose.cad.fileformats.glb/punctuallight/) 类型。 |
| [ResourceWriteMode](./resourcewritemode/) | 确定资源的写入方式。 |
| [TextureInterpolationFilter](./textureinterpolationfilter/) | 放大过滤器。 |
| [TextureMipMapFilter](./texturemipmapfilter/) | 缩小过滤器。 |
| [TextureWrapMode](./texturewrapmode/) | T (V) 包装模式。 |

## Structures

| 结构 | 描述 |
| --- | --- |
| [AttributeFormatTuple](./attributeformattuple/) |  |
| [MaterialChannel](./materialchannel/) | 表示一个材质子通道，通常包含纹理。 |
| [NodeCurveSamplers](./nodecurvesamplers/) | 表示一个代理，以访问[`Node`](../aspose.cad.fileformats.glb/node/)的动画曲线。使用[`GetCurveSamplers`](../aspose.cad.fileformats.glb/node/getcurvesamplers/)进行访问。 |
| [ValueLocationTuple](./valuelocationtuple/) |  |
| [VertexBuilderTuple&lt;TvG, TvM, TvS&gt;](./vertexbuildertuple-3/) |  |
| [VertexColor2Texture2Tuple](./vertexcolor2texture2tuple/) |  |
| [VertexColor2TextureTuple](./vertexcolor2texturetuple/) |  |
| [VertexColorTexture2Tuple](./vertexcolortexture2tuple/) |  |
| [VertexColorTextureTuple](./vertexcolortexturetuple/) |  |
| [VertexGeometryTuple](./vertexgeometrytuple/) |  |
| [VertexTextureTuple](./vertextexturetuple/) |  |

## 委托

| 委托 | 描述 |
| --- | --- |
| [FileReaderCallback](./filereadercallback/) | 用于加载当前模型关联文件的回调。 |
| [ImageDecodeCallback](./imagedecodecallback/) | 用于拦截纹理加载的回调，以便客户端引擎对其进行解码并在必要时上传到 GPU。 |
| [JsonFilterCallback](./jsonfiltercallback/) | 用于在读取前和写入后对 JSON 进行预处理和后处理的回调。 |
| [UriResolver](./uriresolver/) |  |

