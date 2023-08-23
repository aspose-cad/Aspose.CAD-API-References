---
title: Enum ResizeType
second_title: Aspose.CAD for .NET API Reference
description: Aspose.CAD.ResizeType enum. Specifies the resize type
type: docs
weight: 36860
url: /net/aspose.cad/resizetype/
---
## ResizeType enumeration

Specifies the resize type.

```csharp
public enum ResizeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | The pixels are not preserved during resize operation. |
| LeftTopToLeftTop | `1` | Left top point of the new image will coincide with the left top point of the original image. Crop will occur if required. |
| RightTopToRightTop | `2` | Right top point of the new image will coincide with the right top point of the original image. Crop will occur if required. |
| RightBottomToRightBottom | `3` | Right bottom point of the new image will coincide with the right bottom point of the original image. Crop will occur if required. |
| LeftBottomToLeftBottom | `4` | Left bottom point of the new image will coincide with the left bottom point of the original image. Crop will occur if required. |
| CenterToCenter | `5` | Center of the new image will coincide with the center of the original image. Crop will occur if required. |
| LanczosResample | `6` | Resample using lanczos algorithm with a=3. |
| NearestNeighbourResample | `7` | Resample using nearest neighbour algorithm. |
| AdaptiveResample | `8` | Resample using adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation algorithms. |
| BilinearResample | `9` | Resample using bilinear interpolation. Image pre-filtering is allowed to remove the noice before resample, when needed |

### See Also

* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

