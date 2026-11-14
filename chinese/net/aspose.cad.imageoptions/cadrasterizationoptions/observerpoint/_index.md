---
title: "CadRasterizationOptions.ObserverPoint"
linktitle: "ObserverPoint"
articleTitle: "ObserverPoint"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadRasterizationOptions 属性。获取或设置观察点。"
type: docs
weight: 40
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/observerpoint/"
product_version: "26.9"
---
## CadRasterizationOptions.ObserverPoint property

获取或设置观察点。

```csharp
public ObserverPoint ObserverPoint { get; set; }
```

### Property Value

观察点。

## 示例

设置观察点以执行绘图的自定义视图导出

```csharp
using (CadImage cadImage = (CadImage)Image.Load(GetPath(fileName)))
{
    JpegOptions options = new JpegOptions();
    var rasterizationOptions = new CadRasterizationOptions();
    rasterizationOptions.PageWidth = 1500;
    rasterizationOptions.PageHeight = 1500;
    float xAngle = 10; //Angle of rotation along the X axis
    float yAngle = 20; //Angle of rotation along the Y axis
    float zAngle = 30; //Angle of rotation along the Z axis
    rasterizationOptions.ObserverPoint = new ObserverPoint(xAngle, yAngle, zAngle);
    options.VectorRasterizationOptions = rasterizationOptions;
    cadImage.Save(outFile, options);
}
```

### 另请参阅

* class [ObserverPoint](../../../aspose.cad.fileformats/observerpoint/)
* class [CadRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

