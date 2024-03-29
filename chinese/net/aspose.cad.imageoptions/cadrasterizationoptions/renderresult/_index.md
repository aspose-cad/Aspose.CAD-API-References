---
title: RenderResult
second_title: Aspose.CAD for .NET API 参考
description: 渲染结果处理程序
type: docs
weight: 160
url: /zh/net/aspose.cad.imageoptions/cadrasterizationoptions/renderresult/
---
## CadRasterizationOptions.RenderResult field

渲染结果处理程序。

```csharp
public CadRenderHandler RenderResult;
```

### 例子

设置错误处理程序以捕获所有导出错误并将它们打印到 STDOUT

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

### 也可以看看

* delegate [CadRenderHandler](../../cadrasterizationoptions.cadrenderhandler)
* class [CadRasterizationOptions](../../cadrasterizationoptions)
* 命名空间 [Aspose.CAD.ImageOptions](../../cadrasterizationoptions)
* 部件 [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
