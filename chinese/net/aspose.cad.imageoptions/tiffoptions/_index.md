---
title: "TiffOptions 类"
linktitle: "TiffOptions"
articleTitle: "TiffOptions"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ImageOptions.TiffOptions 类。tiff 文件格式选项。请注意，宽度和高度标签将在图像创建时被宽度和 ..."
type: docs
weight: 540
url: "/net/aspose.cad.imageoptions/tiffoptions/"
keywords: "TiffOptions, Aspose.CAD.ImageOptions, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## TiffOptions class

tiff 文件格式选项。
请注意，宽度和高度标签将在图像创建时被宽度和高度参数覆盖，因此无需直接指定它们。
请注意，许多选项返回默认值，但这并不意味着该选项已显式设置为标签值。要验证标签是否存在，请使用 Tags 属性或相应的 IsTagPresent 方法。

```csharp
public class TiffOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor)() | 初始化 `TiffOptions` 类的新实例。默认使用小端字节序。无压缩。RGB 配置文件。 |
| [TiffOptions](tiffoptions/#constructor_1)(TiffDataType[]) | 初始化 `TiffOptions` 类的新实例。 |
| [TiffOptions](tiffoptions/#constructor_2)(TiffExpectedFormat) | 初始化 `TiffOptions` 类的新实例。默认使用小端序约定。 |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | 初始化 `TiffOptions` 类的新实例。 |
| [TiffOptions](tiffoptions/#constructor_4)(TiffExpectedFormat, TiffByteOrder) | 初始化 `TiffOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlphaStorage](../../aspose.cad.imageoptions/tiffoptions/alphastorage/) { get; set; } | 获取或设置 alpha 存储选项。当定义的 [`SamplesPerPixel`](./samplesperpixel/) 超过 3 个时，使用除 Unspecified 之外的选项。 |
| [Artist](../../aspose.cad.imageoptions/tiffoptions/artist/) { get; set; } | 获取或设置艺术家。 |
| [BitsPerPixel](../../aspose.cad.imageoptions/tiffoptions/bitsperpixel/) { get; } | 获取每像素位数。 |
| [BitsPerSample](../../aspose.cad.imageoptions/tiffoptions/bitspersample/) { get; set; } | 获取或设置每样本位数。 |
| [ByteOrder](../../aspose.cad.imageoptions/tiffoptions/byteorder/) { get; set; } | 获取或设置指示 TIFF 字节顺序的值。 |
| [CancellationToken](../../aspose.cad.imageoptions/imageoptionsbase/cancellationtoken/) { get; set; } | 可用于中断导出操作的令牌 |
| [ColorMap](../../aspose.cad.imageoptions/tiffoptions/colormap/) { get; set; } | 获取或设置颜色映射表。 |
| [Compression](../../aspose.cad.imageoptions/tiffoptions/compression/) { get; set; } | 获取或设置压缩。 |
| [Copyright](../../aspose.cad.imageoptions/tiffoptions/copyright/) { get; set; } | 获取或设置版权信息。 |
| [DateTime](../../aspose.cad.imageoptions/tiffoptions/datetime/) { get; set; } | 获取或设置日期和时间。 |
| [DocumentName](../../aspose.cad.imageoptions/tiffoptions/documentname/) { get; set; } | 获取或设置文档名称。 |
| [FaxT4Options](../../aspose.cad.imageoptions/tiffoptions/faxt4options/) { get; set; } | 获取或设置传真 t4 选项。 |
| [FillOrder](../../aspose.cad.imageoptions/tiffoptions/fillorder/) { get; set; } | 获取或设置字节位填充顺序。 |
| [HalfToneHints](../../aspose.cad.imageoptions/tiffoptions/halftonehints/) { get; set; } | 获取或设置半色调提示。 |
| [IccProfile](../../aspose.cad.imageoptions/tiffoptions/iccprofile/) { get; } | 获取 ICC 配置文件流。 |
| [ImageDescription](../../aspose.cad.imageoptions/tiffoptions/imagedescription/) { get; set; } | 获取或设置图像描述。 |
| [ImageLength](../../aspose.cad.imageoptions/tiffoptions/imagelength/) { get; set; } | 获取或设置图像长度。 |
| [ImageWidth](../../aspose.cad.imageoptions/tiffoptions/imagewidth/) { get; set; } | 获取或设置图像宽度。 |
| [InkNames](../../aspose.cad.imageoptions/tiffoptions/inknames/) { get; set; } | 获取或设置墨水名称。 |
| [IsExtraSamplesPresent](../../aspose.cad.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | 获取指示是否存在额外样本的值。 |
| [IsValid](../../aspose.cad.imageoptions/tiffoptions/isvalid/) { get; } | 获取指示 `TiffOptions` 是否已正确配置的值。使用 Validate 方法查找失败原因。 |
| [Layers](../../aspose.cad.imageoptions/imageoptionsbase/layers/) { get; set; } | 获取或设置必须导出的图层名称列表。如果未设置名称，则所有数据将在没有图层的情况下导出。 |
| [MaxSampleValue](../../aspose.cad.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | 获取或设置最大样本值。 |
| [MinSampleValue](../../aspose.cad.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | 获取或设置最小样本值。 |
| [Orientation](../../aspose.cad.imageoptions/tiffoptions/orientation/) { get; set; } | 获取或设置方向。 |
| [OutputMode](../../aspose.cad.imageoptions/imageoptionsbase/outputmode/) { get; set; } | 是否将内容直接转换为目标格式，或先渲染为线条再保存。转换模式适用于 DWG\\DXF、DWF 源格式。 |
| [PageName](../../aspose.cad.imageoptions/tiffoptions/pagename/) { get; set; } | 获取或设置页面名称。 |
| [PageNumber](../../aspose.cad.imageoptions/tiffoptions/pagenumber/) { get; set; } | 获取或设置页码标签。 |
| override [Palette](../../aspose.cad.imageoptions/tiffoptions/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Pc3File](../../aspose.cad.imageoptions/imageoptionsbase/pc3file/) { get; set; } | 获取或设置 PC3 文件的完整名称。 |
| [Photometric](../../aspose.cad.imageoptions/tiffoptions/photometric/) { get; set; } | 获取或设置光度。 |
| [PlanarConfiguration](../../aspose.cad.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | 获取或设置平面配置。 |
| [Predictor](../../aspose.cad.imageoptions/tiffoptions/predictor/) { get; set; } | 获取或设置 LZW 压缩的预测器。 |
| [RenderToGraphicsBound](../../aspose.cad.imageoptions/imageoptionsbase/rendertographicsbound/) { get; set; } | 获取或设置一个值，以指示渲染时使用哪种图像尺寸：图形尺寸（true，默认）或元数据中设置的尺寸（false）。 |
| override [ResolutionSettings](../../aspose.cad.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.cad.imageoptions/tiffoptions/resolutionunit/) { get; set; } | 获取或设置分辨率单位。 |
| [Rotation](../../aspose.cad.imageoptions/imageoptionsbase/rotation/) { get; set; } | 获取或设置图像旋转、翻转或旋转并翻转的参数。 |
| [RowsPerStrip](../../aspose.cad.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | 获取或设置每条带的行数。 |
| [SampleFormat](../../aspose.cad.imageoptions/tiffoptions/sampleformat/) { get; set; } | 获取或设置样本格式。 |
| [SamplesPerPixel](../../aspose.cad.imageoptions/tiffoptions/samplesperpixel/) { get; } | 获取每像素的样本数。要更改此属性值，请使用 [`BitsPerSample`](./bitspersample/) 属性设置器。 |
| [ScannerManufacturer](../../aspose.cad.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | 获取或设置扫描仪制造商。 |
| [ScannerModel](../../aspose.cad.imageoptions/tiffoptions/scannermodel/) { get; set; } | 获取或设置扫描仪型号。 |
| [SmaxSampleValue](../../aspose.cad.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | 获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| [SminSampleValue](../../aspose.cad.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | 获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| [SoftwareType](../../aspose.cad.imageoptions/tiffoptions/softwaretype/) { get; set; } | 获取或设置软件类型。 |
| [Source](../../aspose.cad.imageoptions/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [StripByteCounts](../../aspose.cad.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | 获取或设置条带字节计数。 |
| [StripOffsets](../../aspose.cad.imageoptions/tiffoptions/stripoffsets/) { get; set; } | 获取或设置条带偏移。 |
| [SubFileType](../../aspose.cad.imageoptions/tiffoptions/subfiletype/) { get; set; } | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [Tags](../../aspose.cad.imageoptions/tiffoptions/tags/) { get; set; } | 获取或设置标签。 |
| override [TargetFormat](../../aspose.cad.imageoptions/tiffoptions/targetformat/) { get; } |  |
| [TargetPrinter](../../aspose.cad.imageoptions/tiffoptions/targetprinter/) { get; set; } | 获取或设置目标打印机。 |
| [Threshholding](../../aspose.cad.imageoptions/tiffoptions/threshholding/) { get; set; } | 获取或设置阈值化。 |
| [Timeout](../../aspose.cad.imageoptions/imageoptionsbase/timeout/) { get; set; } | 导出操作的超时时间值（毫秒） |
| [TotalPages](../../aspose.cad.imageoptions/tiffoptions/totalpages/) { get; } | 获取总页数。 |
| [UserWatermarkColor](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarkcolor/) { get; set; } | 用户生成水印的颜色 |
| [UserWatermarkText](../../aspose.cad.imageoptions/imageoptionsbase/userwatermarktext/) { get; set; } | 用户生成水印的文本 |
| [ValidTagCount](../../aspose.cad.imageoptions/tiffoptions/validtagcount/) { get; } | 获取有效标签计数。这不是标签的总计数，而是可能被保留的标签数量。 |
| [VectorRasterizationOptions](../../aspose.cad.imageoptions/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.cad.imageoptions/tiffoptions/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |
| [Xposition](../../aspose.cad.imageoptions/tiffoptions/xposition/) { get; set; } | 获取或设置 X 位置。 |
| [Xresolution](../../aspose.cad.imageoptions/tiffoptions/xresolution/) { get; set; } | 获取或设置 X 分辨率。 |
| [Yposition](../../aspose.cad.imageoptions/tiffoptions/yposition/) { get; set; } | 获取或设置 Y 位置。 |
| [Yresolution](../../aspose.cad.imageoptions/tiffoptions/yresolution/) { get; set; } | 获取或设置 Y 分辨率。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddTag](../../aspose.cad.imageoptions/tiffoptions/addtag/)(TiffDataType) | 添加新标签。 |
| [AddTags](../../aspose.cad.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | 添加标签。 |
| [GetTagByType](../../aspose.cad.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | 根据类型获取标签的实例。 |
| static [GetValidTagsCount](../../aspose.cad.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | 获取有效标签的数量。 |
| [IsTagPresent](../../aspose.cad.imageoptions/tiffoptions/istagpresent/)(TiffTags) | 确定标签是否存在于选项中。 |
| [RemoveTag](../../aspose.cad.imageoptions/tiffoptions/removetag/)(TiffTags) | 移除标签。 |
| [Validate](../../aspose.cad.imageoptions/tiffoptions/validate/)() | 验证选项是否具有有效的标签组合。 |

### 另请参阅

* class [ImageOptionsBase](../imageoptionsbase/)
* namespace [Aspose.CAD.ImageOptions](../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../)

