---
title: "Image.SaveAsync"
linktitle: "SaveAsync"
articleTitle: "SaveAsync"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。根据保存选项，将对象的数据保存到指定文件位置的指定文件格式。"
type: docs
weight: 150
url: "/net/aspose.cad/image/saveasync/"
product_version: "26.9"
---
## SaveAsync(Stream, ImageOptionsBase) {#saveasync}

根据保存选项，将图像的数据保存到指定流的指定文件格式中。

```csharp
public Task SaveAsync(Stream stream, ImageOptionsBase optionsBase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 当前不支持保存为指定的格式。;optionsBase |
| [ImageSaveException](../../../aspose.cad.cadexceptions/imagesaveexception/) | 图像导出失败。 |

## 示例

将绘图导出为 JPEG 格式并旋转 90 度，然后写入内存流。

```csharp
using (var ms = new MemoryStream())
{
    using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
    {
        await image.Save(ms, new JpegOptions()
        {
            Rotation = RotateFlipType.Rotate90FlipNone
        });
    }
}
```

### 另请参阅

* class [ImageOptionsBase](../../../aspose.cad.imageoptions/imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## SaveAsync(string, ImageOptionsBase) {#saveasync_1}

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

```csharp
public virtual Task SaveAsync(string filePath, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |

## 示例

将绘图导出为指定尺寸的 BMP。

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    await image.Save("targetFile.bmp", new BmpOptions()
    {
        VectorRasterizationOptions = new CadRasterizationOptions()
        {
            PageWidth = 640,
            PageHeight = 480
        }
    });
}
```

### 另请参阅

* class [ImageOptionsBase](../../../aspose.cad.imageoptions/imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

