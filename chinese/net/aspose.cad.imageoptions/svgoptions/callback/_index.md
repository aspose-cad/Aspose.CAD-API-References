---
title: "SvgOptions.Callback"
linktitle: "Callback"
articleTitle: "Callback"
second_title: "Aspose.CAD for .NET API 参考"
description: "SvgOptions 属性。获取或设置可用于根据用户需求存储图像和字体二进制数据的回调"
type: docs
weight: 30
url: "/net/aspose.cad.imageoptions/svgoptions/callback/"
product_version: "26.9"
---
## SvgOptions.Callback property

获取或设置回调，可用于根据用户需求存储图像和字体的二进制数据

```csharp
public ISvgResourceKeeperCallback Callback { get; set; }
```

### Property Value

该回调

## 示例

// 一个只能保存一个字体和一个图像的简单回调示例

```csharp
 internal class SvgCallback : ISvgResourceKeeperCallback
 {
     bool fontStoreExternal;
     Stream streamForFont;
     string fontFileName;
     string imageFileName;
     Stream streamForImage;
     bool imageStoreExternal;
     Stream streamForSvg;
     string nameForSvg;

     public SvgCallback(bool fontStoreExternal, Stream streamForFont, string fontFileName, string imageFileName, Stream streamForImage, bool imageStoreExternal, Stream streamForSvg, string nameForSvg)
     {
        this.fontFileName = fontFileName;
        this.fontStoreExternal = fontStoreExternal;
        this.streamForFont = streamForFont;
        this.streamForImage = streamForImage;
        this.imageFileName = imageFileName;
        this.imageStoreExternal = imageStoreExternal;
        this.streamForSvg = streamForSvg;
        this.nameForSvg = nameForSvg;
     }

     public void OnFontResourceReady(FontStoringArgs args)
     {
          if (!fontStoreExternal)
              args.FontStoreType = FontStoreType.Embedded;
          else
          {
              args.FontStoreType = FontStoreType.Stream;
              args.FontFileUri = fontFileName;
              args.DestFontStream = streamForFont;
              args.DisposeStream = true;
          }
     }

    public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, string suggestedFileName, ref bool useEmbeddedImage)
    {
         if (!imageStoreExternal)
         {
           useEmbeddedImage = true;
           return suggestedFileName;
         }
         else
         {
              useEmbeddedImage = false;
              if (streamForImage != null)
              {
                   streamForImage.Write(imageData, 0, imageData.Length);
                   streamForImage.Dispose();
              }

              return imageFileName;
          }
    }

     public string OnSvgDocumentReady(byte[] htmlData, string suggestedFileName)
     {
          if (streamForSvg != null)
          {
              streamForSvg.Write(htmlData, 0, htmlData.Length);
              streamForSvg.Dispose();
          }

          return nameForSvg;
     }
}
```

// 使用回调存储渲染的 SVG

```csharp
using (Stream content = File.Open(outCallback, FileMode.Create))
{
    SvgCallback callback = new SvgCallback(false, null, "font.ttf", "", null, false, content, outCallback);
    using (var img = Image.Load(file))
    {
        CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
        SvgOptions opt = new SvgOptions() { TextAsShapes = false };
        opt.VectorRasterizationOptions = cadRasterizationOptions;
        cadRasterizationOptions.DrawType = CadDrawTypeMode.UseObjectColor;
        opt.Callback = callback;
        img.Save(outFile, opt);
    }
}
```

// 使用回调存储字体

```csharp
using (Stream font = File.Open(outFont, FileMode.Create))
{
     SvgCallback callback = new SvgCallback(true, font, "font.ttf", "", null, false, content, outCallback);
     using (var img = Image.Load(file))
     {
            CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
            SvgOptions opt = new SvgOptions() { TextAsShapes = false };
            opt.VectorRasterizationOptions = cadRasterizationOptions;
            cadRasterizationOptions.DrawType = CadDrawTypeMode.UseObjectColor;
            opt.Callback = callback;
            img.Save(outFile, opt);
     }
 }
```

// 使用回调存储光栅内容

```csharp
using (Stream image = File.Open(outRaster, FileMode.Create))
{
  SvgCallback callback = new SvgCallback(false, null, "", "raster.png", image, true, content, outCallback);
  using (var img = Image.Load(file))
  {
      CadRasterizationOptions cadRasterizationOptions = new CadRasterizationOptions();
      SvgOptions opt = new SvgOptions();
      opt.VectorRasterizationOptions = cadRasterizationOptions;
      cadRasterizationOptions.DrawType = CadDrawTypeMode.UseObjectColor;
      opt.Callback = callback;
      img.Save(outFile, opt);
  }
}
```

### 另请参阅

* interface [ISvgResourceKeeperCallback](../../../aspose.cad.imageoptions.svgoptionsparameters/isvgresourcekeepercallback/)
* class [SvgOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

