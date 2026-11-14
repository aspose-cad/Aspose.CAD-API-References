---
title: "ResizeType 枚举"
linktitle: "ResizeType"
articleTitle: "ResizeType"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.ResizeType 枚举。指定调整大小的类型。"
type: docs
weight: 780
url: "/net/aspose.cad/resizetype/"
product_version: "26.9"
---
## ResizeType enumeration

指定调整大小的类型。

```csharp
public enum ResizeType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 在调整大小操作期间，像素不会被保留。 |
| LeftTopToLeftTop | `1` | 新图像的左上点将与原始图像的左上点重合。如有必要，将进行裁剪。 |
| RightTopToRightTop | `2` | 新图像的右上点将与原始图像的右上点重合。如有必要，将进行裁剪。 |
| RightBottomToRightBottom | `3` | 新图像的右下点将与原始图像的右下点重合。如有必要，将进行裁剪。 |
| LeftBottomToLeftBottom | `4` | 新图像的左下点将与原始图像的左下点重合。如有必要，将进行裁剪。 |
| CenterToCenter | `5` | 新图像的中心将与原始图像的中心重合。如有必要，将进行裁剪。 |
| LanczosResample | `6` | 使用 a=3 的 lanczos 算法进行重采样。 |
| NearestNeighbourResample | `7` | 使用最近邻算法进行重采样。 |
| AdaptiveResample | `8` | 使用基于加权和混合有理函数以及 lanczos3 插值算法的自适应算法进行重采样。 |
| BilinearResample | `9` | 使用双线性插值进行重采样。需要时，可进行图像预过滤以在重采样前去除噪声。 |

### 另请参阅

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

