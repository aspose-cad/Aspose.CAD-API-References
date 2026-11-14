---
title: "CadRasterizationOptions.RenderResult"
linktitle: "RenderResult"
articleTitle: "RenderResult"
second_title: "Aspose.CAD for .NET API 参考"
description: "CadRasterizationOptions 字段。渲染结果处理程序。"
type: docs
weight: 240
url: "/net/aspose.cad.imageoptions/cadrasterizationoptions/renderresult/"
product_version: "26.9"
---
## CadRasterizationOptions.RenderResult field

渲染结果处理程序。

```csharp
public CadRenderHandler RenderResult;
```

## 示例

设置错误处理程序以捕获所有导出错误并将其打印到 STDOUT

```csharp
using (var image = Aspose.CAD.Image.Load("fileName.dwg"))
{
    image.Save("targetFile.bmp", new BmpOptions()
    {
        VectorRasterizationOptions = new CadRasterizationOptions()
        {
            RenderResult = result =>
            {
                if (!result.IsRenderComplete)
                {
                    foreach (var resultFailure in result.Failures)
                    {
                        Console.WriteLine($"Error: {resultFailure.Message} (error code {resultFailure.RenderCode})");
                    }
                }
            }
        }
    });
}
```

### 另请参阅

* delegate [CadRenderHandler](../../cadrasterizationoptions.cadrenderhandler/)
* class [CadRasterizationOptions](../)
* namespace [Aspose.CAD.ImageOptions](../../../aspose.cad.imageoptions/)
* assembly [Aspose.CAD](../../../)

