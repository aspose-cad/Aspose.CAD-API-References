---
title: "DwfImage 类"
linktitle: "DwfImage"
articleTitle: "DwfImage"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Dwf.DwfImage 类。DWF 图像类。提供对 DWF/DWFX 格式文件的读取、处理以及导出为其他格式的功能。"
type: docs
weight: 20
url: "/net/aspose.cad.fileformats.dwf/dwfimage/"
keywords: "DwfImage, Aspose.CAD.FileFormats.Dwf, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## DwfImage class

DWF 图像类。
提供对 DWF/DWFX 格式文件的读取、处理以及导出为其他格式的功能。

```csharp
public sealed class DwfImage : Image
```

## 示例

读取 DWG 格式的图像文件，修改其内容并以 PNG 格式保存图像。

```csharp
string fileName = "exampleFile";
string file = string.Format("{0}.dwf", fileName);
string outFile = string.Format("{0}.png", fileName);
using (FileStream inStream = new FileStream(file, FileMode.Open))
using (DwfImage image = (DwfImage) Image.Load(inStream))
using (FileStream stream = new FileStream(outFile, FileMode.Create))
{
    DwfWhipDrawable[] entities = image.Pages[0].Entities;
    foreach(DwfWhipDrawable drawable in entities)
    {
        if(drawable is DwfWhipPolyline)
        {
            ((DwfWhipPolyline) drawable).Points[0].X = -50;
            ((DwfWhipPolyline) drawable).Points[0].Y = -50;
            break;
        }
    }  

    image.UpdateSize();

    foreach (DwfWhipDrawable drawable in entities)
    {
        if (drawable is DwfWhipText)
        {
            ((DwfWhipText)drawable).Font.Name.Value.AsciiString = "Arial";
        }
    }

    ImageOptionsBase options = new PngOptions();
    options.VectorRasterizationOptions = new CadRasterizationOptions
    {
        PageWidth = (float)image.Pages[0].PaperWidth,
        PageHeight = (float)image.Pages[0].PaperHeight,
        DrawType = CadDrawTypeMode.UseObjectColor,
    };

    image.Save(stream, options);
}
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AnnotationService](../../aspose.cad/image/annotationservice/) { get; } | 获取注释服务。 |
| [Bounds](../../aspose.cad/image/bounds/) { get; } | 获取图像边界。 |
| [Container](../../aspose.cad/image/container/) { get; } | 获取 [`Image`](../../aspose.cad/image/) 容器。 |
| virtual [CustomProperties](../../aspose.cad/image/customproperties/) { get; } | 获取或设置自定义属性。 |
| [DataStreamContainer](../../aspose.cad/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| override [Depth](../../aspose.cad.fileformats.dwf/dwfimage/depth/) { get; } | 获取图像深度。 |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [Height](../../aspose.cad.fileformats.dwf/dwfimage/height/) { get; } | 获取图像高度。定义图像中所有图形对象的最低点与最高点之间的 Y 轴距离。该距离以对应属性 [`UnitType`](../../aspose.cad/image/unittype/) 的值的单位来衡量。 |
| override [IsCached](../../aspose.cad.fileformats.dwf/dwfimage/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。根据加载选项，仅必要的数据部分可以从图像数据加载到缓存中。在这种情况下，可使用此属性来判断仅有部分图像数据已加载到缓存。 |
| [Layers](../../aspose.cad.fileformats.dwf/dwfimage/layers/) { get; } | 获取 DWF 页面图层。返回 DWF 图层的可枚举集合。DWF 数据可以分配给特定的 DWF 图层，该图层是绘图对象的分组。 |
| [Metadata](../../aspose.cad.fileformats.dwf/dwfimage/metadata/) { get; set; } | 获取或设置元数据信息。返回来自 Dwf/Dwfx 包的清单和描述符资源的元数据记录数组。 |
| [Pages](../../aspose.cad.fileformats.dwf/dwfimage/pages/) { get; } | 获取 DWF 页面。返回 DWF 图像中包含的所有 DWF 页面数组。每个 DWF 页面定义其所有可用的图形参数以及绘制在其上的所有对象。 |
| [Palette](../../aspose.cad/image/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Size](../../aspose.cad/image/size/) { get; } | 获取图像尺寸。 |
| override [UnitType](../../aspose.cad.fileformats.dwf/dwfimage/unittype/) { get; } | 获取当前单位类型。 |
| virtual [UnitlessDefaultUnitType](../../aspose.cad/image/unitlessdefaultunittype/) { get; } | 当 UnitType 设置为 Unitless 时假定的单位类型 |
| virtual [WatermarkGuardService](../../aspose.cad/image/watermarkguardservice/) { get; } |  |
| override [Width](../../aspose.cad.fileformats.dwf/dwfimage/width/) { get; } | 获取图像宽度。定义图像中所有图形对象的最左点与最右点之间的 X 轴距离。该距离以对应属性 [`UnitType`](../../aspose.cad/image/unittype/) 的值的单位来衡量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddElement](../../aspose.cad.fileformats.dwf/dwfimage/addelement/)(int, DwfWhipDrawable) | 向指定页面添加图形元素。提供向图像中现有图形元素添加新图形元素的机会。要添加它，需要创建一个新图形元素并在 [`Pages`](./pages/) 数组中指定应添加该元素的页面索引。 |
| override [CacheData](../../aspose.cad.fileformats.dwf/dwfimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.cad/datastreamsupporter/datastreamcontainer/) 再次加载数据。根据加载选项，只会将必要的数据部分从图像数据加载到缓存中。在这种情况下，我们可以使用此方法将所有图像数据加载到缓存中。 |
| [CanSave](../../aspose.cad/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为由传入的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | 释放当前实例。 |
| [GetElementCount](../../aspose.cad.fileformats.dwf/dwfimage/getelementcount/)(int) | 获取指定页面的图形元素计数。提供确定特定图像页面上图形元素数量的能力。要获取此值，需要在数组 [`Pages`](./pages/) 中指定页面索引，以及想要获取的元素数量。 |
| override [GetStrings](../../aspose.cad.fileformats.dwf/dwfimage/getstrings/)() | 获取图像中的所有字符串值。提供以字符串数组形式获取图像中所有文本图形元素值的机会。 |
| [RemoveElement](../../aspose.cad.fileformats.dwf/dwfimage/removeelement/)(int, int) | 从指定页面移除图形元素。提供从图像中移除图形元素的能力。要移除它，需要在 [`Pages`](./pages/) 数组中指定要移除元素的页面索引，并在 [`Entities`](../dwfpage/entities/) 数组中指定元素的索引。 |
| override [Save](../../aspose.cad/image/save/)() | 将图像数据保存到底层流中。 |
| [Save](../../aspose.cad/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.cad/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [Save](../../aspose.cad/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.cad/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [SaveAsync](../../aspose.cad/image/saveasync/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据保存到指定流的指定文件格式中。 |
| virtual [SaveAsync](../../aspose.cad/image/saveasync/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [UpdateSize](../../aspose.cad.fileformats.dwf/dwfimage/updatesize/)() | 更新图像尺寸。提供对图像尺寸参数的强制计算。更改影响图像尺寸参数的图形内容后，必须在使用图像尺寸参数之前执行此计算。 |

### 另请参阅

* class [Image](../../aspose.cad/image/)
* namespace [Aspose.CAD.FileFormats.Dwf](../../aspose.cad.fileformats.dwf/)
* assembly [Aspose.CAD](../../)

