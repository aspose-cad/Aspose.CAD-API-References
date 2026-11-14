---
title: "Image.Save"
linktitle: "保存"
articleTitle: "保存"
second_title: "Aspose.CAD for .NET API 参考"
description: "Image 方法。将图像数据保存到底层流。"
type: docs
weight: 140
url: "/net/aspose.cad/image/save/"
product_version: "26.9"
---
## Save() {#save}

将图像数据保存到底层流中。

```csharp
public sealed override void Save()
```

## 示例

保存对绘图所做的所有更改。注意：当前仅支持 DXF。

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    image.Save();
}
```

### 另请参阅

* class [Image](../)
* namespace [Aspose.CAD](../../../aspose.cad/)
* assembly [Aspose.CAD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_1}

根据保存选项，将图像的数据保存到指定流的指定文件格式中。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
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
        image.Save(ms, new JpegOptions()
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

## Save(string, ImageOptionsBase) {#save_2}

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
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
    image.Save("targetFile.bmp", new BmpOptions()
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

