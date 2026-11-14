---
title: "CadDimensionStyleTable 类"
linktitle: "CadDimensionStyleTable"
articleTitle: "CadDimensionStyleTable"
second_title: "Aspose.CAD for .NET API 参考"
description: "Aspose.CAD.FileFormats.Cad.CadTables.CadDimensionStyleTable 类。Cad 尺寸样式表。"
type: docs
weight: 40
url: "/net/aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/"
keywords: "CadDimensionStyleTable, Aspose.CAD.FileFormats.Cad.CadTables, Aspose.CAD for .NET, Aspose.CAD API Reference"
product_version: "26.9"
---
## CadDimensionStyleTable class

该 Cad 标注样式表。

```csharp
public class CadDimensionStyleTable : CadOwnedObjectBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadDimensionStyleTable](caddimensionstyletable/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplicationCodesContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/applicationcodescontainer/) { get; set; } | 获取或设置应用程序定义的代码容器。 |
| [Attribute102Values](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attribute102values/) { get; set; } | 获取或设置 attribute102 值。 |
| [Attributes](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/attributes/) { get; set; } | 获取或设置属性。 |
| [DimAltMzf](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltmzf/) { get; set; } | 获取或设置尺寸的备用次零因子。 |
| [DimAltMzs](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltmzs/) { get; set; } | 获取或设置尺寸的备用次零后缀。 |
| [DimMzf](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimmzf/) { get; set; } | 获取或设置尺寸的次零因子。 |
| [DimMzs](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimmzs/) { get; set; } | 获取或设置尺寸的次零后缀。 |
| [DimTxtDirection](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtxtdirection/) { get; set; } | 获取或设置尺寸中文本的阅读方向。0（false）值对应从左到右，1（true）对应从右到左。 |
| [Dimadec](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimadec/) { get; set; } | 获取或设置角度尺寸中显示的精度位数。 |
| [Dimalt](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimalt/) { get; set; } | 获取或设置尺寸中显示备用单位的模式。如果值为 0，备用单位关闭；如果值为 1，备用单位开启。 |
| [Dimaltd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltd/) { get; set; } | 获取或设置备用单位的小数位数。如果 Dimalt 已开启，此值设置小数点后的位数。 |
| [Dimaltf](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltf/) { get; set; } | 获取或设置备用单位的乘数。如果 Dimalt 已开启，此值设置线性尺寸的乘算因子。表示一英寸中的毫米数。 |
| [Dimaltrnd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltrnd/) { get; set; } | 获取或设置备用单位的舍入值，例如 0.0000。 |
| [Dimalttd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimalttd/) { get; set; } | 获取或设置尺寸的备用单位中公差值的小数位数。 |
| [Dimalttz](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimalttz/) { get; set; } | 获取或设置备用公差零抑制模式。 |
| [Dimaltu](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltu/) { get; set; } | 获取或设置所有尺寸样式（角度除外）的备用单位格式。 |
| [Dimaltz](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaltz/) { get; set; } | 获取或设置备用单位尺寸值的零抑制。 |
| [Dimapost](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimapost/) { get; set; } | 获取或设置所有尺寸样式（角度除外）的备用尺寸测试的文本前缀和/或后缀。 |
| [Dimarcsym](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimarcsym/) { get; set; } | 获取或设置弧长尺寸的弧符号显示模式。可能的取值为：0（弧长符号位于尺寸文本之前），1（弧长符号位于尺寸文本上方），2（不显示弧长符号）。 |
| [Dimasz](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimasz/) { get; set; } | 获取或设置尺寸箭头的大小。仅在 Dimtsz 为 0 时适用。 |
| [Dimatfit](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimatfit/) { get; set; } | 获取或设置空间不足时排列尺寸文本和箭头的模式。可能的取值为：0（文本和箭头位于延伸线之外），1（先移动箭头），2（先移动文本），3（采用最佳的箭头或文本移动方式）。 |
| [Dimaunit](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimaunit/) { get; set; } | 获取或设置角度尺寸的单位。可能的取值为：0（十进制度），1（度/分/秒），2（梯度），3（弧度）。 |
| [Dimazin](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimazin/) { get; set; } | 获取或设置角度尺寸的零抑制模式。可能的取值为：0（显示所有零），1（抑制前导零），2（抑制尾随零），3（同时抑制前导零和尾随零）。 |
| [Dimblk](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblk/) { get; set; } | 获取或设置用于尺寸线端点的箭头块名称。有效的标准名称包括 ".", "_DOT", "_DOTSMALL", "_DOTBLANK", "_ORIGIN", "_ORIGIN2", "_OPEN", "_OPEN90", "_OPEN30", "_CLOSED", "_SMALL", "_NONE", "_OBLIQUE", "_BOXFILLED", "_BOXBLANK", "_CLOSEDBLANK", "_DATUMFILLED", "_DATUMBLANK", "_INTEGRAL", "_ARCHTICK"。 |
| [Dimblk1](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblk1/) { get; set; } | 获取或设置当 Dimsah 为 1 时第一条尺寸线的箭头。 |
| [Dimblk1Handle](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblk1handle/) { get; set; } | 获取或设置 Dimblk1 引用的块的句柄。 |
| [Dimblk2](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblk2/) { get; set; } | 获取或设置当 Dimsah 为 1 时第二条尺寸线的箭头。 |
| [Dimblk2Handle](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblk2handle/) { get; set; } | 获取或设置 Dimblk2 引用的块的句柄。 |
| [DimblkHandle](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimblkhandle/) { get; set; } | 获取或设置 Dimblk 引用的块的句柄。 |
| [Dimcen](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimcen/) { get; set; } | 获取或设置绘制弧/圆中心标记和中心线的模式。如果值为 0，则不绘制中心标记；如果为负，则绘制中心线；如果为正，则绘制中心标记。 |
| [Dimclrd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimclrd/) { get; set; } | 获取或设置尺寸线、箭头和尺寸引线的颜色。可能的取值为 1-225（颜色索引），0 - 按块，256 - 按图层。 |
| [Dimclre](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimclre/) { get; set; } | 获取或设置尺寸延伸线的颜色。可能的取值为 1-225（颜色索引），0 - 按块，256 - 按图层。 |
| [Dimclrt](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimclrt/) { get; set; } | 获取或设置尺寸文本的颜色。可能的取值为 1-225（颜色索引），0 - 按块，256 - 按图层。 |
| [Dimdec](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimdec/) { get; set; } | 获取或设置尺寸主单位显示的小数位数。 |
| [Dimdle](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimdle/) { get; set; } | 获取或设置尺寸线超出延伸线的距离。用于绘制倾斜线（非箭头）时。 |
| [Dimdli](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimdli/) { get; set; } | 获取或设置基线尺寸中尺寸线的间距。每条尺寸线根据此值相对于前一条进行偏移（如有必要），以避免相互覆盖。 |
| [Dimdsep](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimdsep/) { get; set; } | 获取或设置小数分隔符。默认使用小数点。 |
| [Dimexe](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimexe/) { get; set; } | 获取或设置延伸线与尺寸线之间的距离。 |
| [Dimexo](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimexo/) { get; set; } | 获取或设置延伸线与原点之间的距离。 |
| [Dimfit](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimfit/) { get; set; } | 获取或设置 Dimatfit 与 Dimtmove 的组合。如果此值在 0‑3 范围内，则 Dimatfit 也设置为 0‑3，Dimtmove 设置为 0。如果此值为 4 或 5，则 Dimatfit 为 3，Dimtmove 为 1 或 2。 |
| [Dimfrac](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimfrac/) { get; set; } | 获取或设置建筑或分数单位（Dimlunit）的分数模式。可能的取值为 0（水平堆叠），1（对角堆叠），2（不堆叠）。 |
| [Dimfxl](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimfxl/) { get; set; } |  |
| [Dimfxlon](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimfxlon/) { get; set; } | 获取或设置延伸线的长度是否固定。如果值为 true (1)，则在 DIMFXL 中设置延伸线的长度。 |
| [Dimgap](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimgap/) { get; set; } | 获取或设置尺寸线断开时围绕尺寸文字的距离。 |
| [Dimjogang](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimjogang/) { get; set; } | 获取或设置折线半径尺寸中尺寸线横向段的角度。 |
| [Dimjust](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimjust/) { get; set; } | 获取或设置文字水平定位模式。可能的取值为：0（文字位于尺寸线之上并居中于延伸线之间），1（文字位于第一延伸线旁边），2（文字位于第二延伸线旁边），3（文字位于上方并与第一延伸线对齐），4（文字位于上方并与第二延伸线对齐）。 |
| [Dimldrblk](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimldrblk/) { get; set; } | 获取或设置引线的箭头类型。可用取值列表与 Dimblk 相同。 |
| [Dimlfac](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimlfac/) { get; set; } | 获取或设置线性尺寸测量的比例因子。 |
| [Dimlim](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimlim/) { get; set; } | 获取或设置尺寸极限为默认文字。可能的取值为：0（不生成默认文字的极限），1（生成默认文字的极限）。如果该值为 1，则 Dimtol 值视为关闭。 |
| [Dimlunit](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimlunit/) { get; set; } | 获取或设置单位模式（不适用于角度尺寸）。可能的取值为：1（科学计数），2（十进制），3（工程），4（建筑堆叠），5（分数堆叠），6（Microsoft Windows 桌面）。 |
| [Dimlwd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimlwd/) { get; set; } | 获取或设置尺寸线的线宽。可能的取值为：-3（默认 LWDEFAULT 值），-2（按块），-1（按图层）。 |
| [Dimlwe](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimlwe/) { get; set; } | 获取或设置延伸线的线宽。可能的取值为：-3（默认 LWDEFAULT 值），-2（按块），-1（按图层）。 |
| [Dimpost](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimpost/) { get; set; } |  |
| [Dimrnd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimrnd/) { get; set; } | 获取或设置尺寸距离的四舍五入精度（角度尺寸除外）。 |
| [Dimsah](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimsah/) { get; set; } | 获取或设置应使用的箭头块。如果值为 0，则使用 Dimblk 设置的箭头；如果值为 1，则使用 Dimblk1 和 Dimblk2 的箭头。 |
| [Dimscale](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimscale/) { get; set; } | 获取或设置尺寸的比例。适用于尺寸、距离和偏移，但不适用于测量长度、坐标和角度。 |
| [Dimsd1](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimsd1/) { get; set; } | 获取或设置第一条尺寸线及其箭头的抑制。可能的取值为：0（不抑制），1（抑制）。 |
| [Dimsd2](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimsd2/) { get; set; } | 获取或设置第二条尺寸线及其箭头的抑制。可能的取值为：0（不抑制），1（抑制）。 |
| [Dimse1](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimse1/) { get; set; } | 获取或设置第一条延伸线的抑制。可能的取值为：0（不抑制），1（抑制）。 |
| [Dimse2](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimse2/) { get; set; } | 获取或设置第二条延伸线的抑制。可能的取值为：0（不抑制），1（抑制）。 |
| [Dimsoxd](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimsoxd/) { get; set; } | 获取或设置当延伸线内部空间不足时箭头的抑制。可能的取值为：0（不抑制），1（抑制）。 |
| [Dimtad](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtad/) { get; set; } | 获取或设置文字相对于尺寸线的垂直位置模式。可能的取值为：0（居中于延伸线之间），1（位于尺寸线之上），2（位于距离定义点最远的一侧），3（位置符合日本工业标准（JIS）），4（位于尺寸线之下）。 |
| [Dimtdec](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtdec/) { get; set; } | 获取或设置在尺寸的主单位容差值中显示的小数位数。仅在 Dimtol 开启时适用。 |
| [Dimtfac](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtfac/) { get; set; } | 获取或设置分数和容差值的文字高度相对于尺寸文字高度的比例因子。 |
| [Dimtfill](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtfill/) { get; set; } | 获取或设置尺寸文字的填充背景。可能的取值为：0（无背景），1（图形的背景颜色），2（由 Dimtfillclr 指定的颜色）。 |
| [Dimtfillclr](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtfillclr/) { get; set; } | 获取或设置尺寸文字的填充背景。可能的取值为：0（无背景），1（图形的背景颜色），2（由 Dimtfillclr 指定的颜色）。 |
| [Dimtih](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtih/) { get; set; } | 获取或设置尺寸文字在延伸线内部的位置（坐标尺寸除外）。可能的取值为：0（文字与尺寸线对齐），1（水平文字）。 |
| [Dimtix](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtix/) { get; set; } | 获取或设置文字是否应绘制在延伸线之间。可能的取值为：0（文字位于延伸线内部），1（即使通常会放在延伸线外部，文字仍位于延伸线之间）。 |
| [Dimtm](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtm/) { get; set; } | 获取或设置尺寸文字的最小容差限值。Dimtol 或 Dimlim 开启时适用。 |
| [Dimtmove](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtmove/) { get; set; } | 获取或设置尺寸文本移动的模式。可能的取值为：0（随尺寸文本移动尺寸线），1（当尺寸文本移动时添加引线），2（自由移动文本）。 |
| [Dimtofl](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtofl/) { get; set; } | 获取或设置在文本放置在外部时仍在延伸线上绘制尺寸线的模式。可能的取值为：0（不在测量点之间绘制尺寸线），1（在测量点之间绘制尺寸线）。 |
| [Dimtoh](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtoh/) { get; set; } | 获取或设置延伸线外部的尺寸文本位置。可能的取值为：0（文本与尺寸线对齐），1（文本水平）。 |
| [Dimtol](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtol/) { get; set; } | 获取或设置是否应在尺寸文本中添加公差。可能的取值为：0（关闭），1（开启，Dimlim 被视为关闭）。 |
| [Dimtolj](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtolj/) { get; set; } | 获取或设置相对于文本的公差值的垂直对齐方式。可能的取值为：0（底部），1（中部），2（顶部）。 |
| [Dimtp](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtp/) { get; set; } | 获取或设置尺寸文本的最大公差限制。仅在 Dimtol 或 Dimlim 开启时适用。 |
| [Dimtsz](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtsz/) { get; set; } | 获取或设置线性、半径和直径标注的笔画和箭头的绘制模式。如果值为 0，则绘制箭头，正值则定义斜线笔画的大小而非箭头。该值会乘以 Dimscale。 |
| [Dimtvp](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtvp/) { get; set; } | 获取或设置尺寸文本相对于尺寸线的垂直位置（在线上方或下方）。 |
| [Dimtxsty](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtxsty/) { get; set; } | 获取或设置尺寸的文字样式名称。 |
| [Dimtxt](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtxt/) { get; set; } | 获取或设置尺寸文本的高度。 |
| [Dimtzin](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimtzin/) { get; set; } | 获取或设置在公差值中对零的抑制方式。可能的取值为：0（抑制零英尺和精确为零的英寸），1（包含零英尺和精确为零的英寸），2（包含零英尺并抑制零英寸），3（包含零英寸并抑制零英尺），4（抑制前导零），8（抑制尾随零），12（同时抑制前导零和尾随零）。 |
| [Dimunit](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimunit/) { get; set; } | 获取或设置先前用于设置单位的值，但现在已被 Dimlunit 和 Dimfrac 替代。 |
| [Dimupt](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimupt/) { get; set; } | 获取或设置用户定位文本的模式。可能的取值为：0（光标仅控制尺寸线位置），1（光标同时控制文本位置和尺寸线位置）。 |
| [Dimzin](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/dimzin/) { get; set; } | 获取或设置主单位值中零的抑制方式。可能的取值为：0（抑制零英尺和精确为零的英寸），1（包含零英尺和精确为零的英寸），2（包含零英尺并抑制零英寸），3（包含零英寸并抑制零英尺），4（位 3，抑制前导零），8（位 4，抑制尾随零），12（位 3 和位 4，抑制前导零和尾随零）。 |
| [EmbeddedObjectsContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/embeddedobjectscontainer/) { get; set; } | 获取或设置嵌入对象容器。 |
| [HandleDimstyle](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/handledimstyle/) { get; set; } | 获取或设置句柄 dimstyle。 |
| [HardOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/hardowner/) { get; set; } | 获取或设置硬所有者。 |
| [IsSoftOwnerSet](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/issoftownerset/) { get; } | 获取一个值，指示是否已设置软所有者。 |
| [Numreactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/numreactors/) { get; set; } | 该 Numreactors |
| [ObjectHandle](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/objecthandle/) { get; set; } | 获取或设置对象句柄。 |
| [Reactors](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/reactors/) { get; set; } | 获取或设置反应器句柄 |
| [SoftOwner](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/softowner/) { get; set; } | 获取或设置软所有者。 |
| [StandardFlag](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/standardflag/) { get; set; } | 获取或设置标准标志位编码值。可能的取值为：16（表项外部依赖于 Xref），32 和 16（外部依赖的 Xref 已成功解析），64（上次编辑图形时，表项至少被图形中的一个实体引用）。 |
| virtual [StorageFlag](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/storageflag/) { get; set; } | 获取或设置一个值，指示此实体在数据存储中具有关联的二进制数据。 |
| [StyleName](../../aspose.cad.fileformats.cad.cadtables/caddimensionstyletable/stylename/) { get; set; } | 获取或设置尺寸样式名称。 |
| [XdataContainer](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/xdatacontainer/) { get; set; } | 获取或设置 xdata 容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/getuid/)() | 如果对象句柄不起作用时使用的标识符。作为方法实现，以免干扰 FileComparer's property comparer |
| [SetUID](../../aspose.cad.fileformats.cad.cadobjects/cadobjectbase/setuid/)(string) | 设置 |

### 另请参阅

* class [CadOwnedObjectBase](../../aspose.cad.fileformats.cad.cadobjects/cadownedobjectbase/)
* namespace [Aspose.CAD.FileFormats.Cad.CadTables](../../aspose.cad.fileformats.cad.cadtables/)
* assembly [Aspose.CAD](../../)

