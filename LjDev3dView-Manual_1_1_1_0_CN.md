[软件使用许可协议条款](#软件使用许可协议条款)[前言](#前言)[运行环境](#运行环境)[基本运行环境](#基本运行环境)[Microsoft C/C++ Runtime Library](#microsoft-cc++-runtime-library)[Microsoft .NET Framework](#microsoft-net-framework)[CodeMeterRuntime](#codemeterruntime)[文件构成](#文件构成)[嵌入方法](#嵌入方法)[Winform使用时的实施步骤](#winform使用时的实施步骤)[显示・属性・命令概要](#显示属性命令概要)[１）显示](#１显示)[２）属性](#２属性)[３）命令](#３命令)[详细说明](#详细说明)[１）显示设定](#１显示设定)[显示图像数据](#显示图像数据)[清除图像数据](#清除图像数据)[显示检测结果](#显示检测结果)[清除检测结果](#清除检测结果)[获取高度数据范围](#获取高度数据范围)[将屏幕坐标 (px) 转换为 3D 坐标 (mm)](#将屏幕坐标-px-转换为-3d-坐标-mm)[标记显示](#标记显示)[标记清除](#标记清除)[２）属性设置](#２属性设置)[获取或设置相机的位置](#获取或设置相机的位置)[点云/网格/线框显示切换](#点云网格线框显示切换)[线框尺寸](#线框尺寸)[自动细化设置](#自动细化设置)[细化比例](#细化比例)[实际细化比例](#实际细化比例)[混合比例](#混合比例)[调色板](#调色板)[颜色范围](#颜色范围)[侧壁透明度](#侧壁透明度)[网格范围](#网格范围)[网格位置](#网格位置)[Z缩放](#z缩放)[平面颜色和透明度](#平面颜色和透明度)[截面显示模式](#截面显示模式)[工具截面编号](#工具截面编号)[截面显示编号](#截面显示编号)[截面透明度](#截面透明度)[瑕疵高亮显示](#瑕疵高亮显示)[区域显示](#区域显示)[平面显示](#平面显示)[结果面板显示](#结果面板显示)[坐标轴显示](#坐标轴显示)[网格显示](#网格显示)[颜色条显示](#颜色条显示)[鼠标点坐标显示](#鼠标点坐标显示)[显示视角切换按钮](#显示视角切换按钮)[３）命令设置方法](#３命令设置方法)[初始化](#初始化)[放大](#放大)[缩小](#缩小)[自适应缩放](#自适应缩放)[视角自适应缩放](#视角自适应缩放)[颜色范围贴合](#颜色范围贴合)[彩色范围区域贴合](#彩色范围区域贴合)[彩色范围复位](#彩色范围复位)


# 软件使用许可协议条款

对LJ Developer(以下简称“本软件”)的使用，以用户接受下列软件使用许可协议（以下称“本协议”）为前提条件。若用户将本软件的全部或部分安装或复制到设备和计算机，或使用安装于设备和计算机上的本软件，则视同用户已接受本协议的所有条款，本协议成立生效。

第1条 (使用权的承诺)
以用户遵守本协议为条件，KEYENCE CORPORATION(以下简称“本公司”)承诺用户的非独占性使用权。

第2条 (复制限制)
仅在用户需要备份本软件或需要向前条所规定的第三者进行转让时，可对本软件进行复制。

第3条 (禁止事项)
禁止用户对本软件进行以下行为。
a. 变更或增加本软件的部分或全部功能的修改行为。但是，有本公司提供更新程序或安装添加功能等，本公司明确授权的行为除外。
b. 反向编译或反向装配等，解读本软件的所有逆向工程行为。
c. 将本软件对第三者进行转卖、转让、重新分发、使用授权、租赁、出租等行为。但事先得到本公司认可的情况除外。

第4条（版权等）
本软件及本软件手册相关的版权等知识产权归本公司所有。

第5条（免责）
对于因使用本软件而对用户或第三者造成的损害，本公司概不负责。

第6条（终止合同）


- 用户通过废弃本软件及其复制物等手段停止使用本软件之时起，本协议自动终止。

- 若用户违反本协议任一条款，本公司可单方面解除本协议。此时，应立即废弃本软件及其复制物或将其返还至本公司。

- 若因用户违反本协议而对本公司造成损害，用户须赔偿本公司损失。


第7条（准据法和管辖权）
本协议基于日本国法律而生效。此外，关于本合同的一切纠纷将交由作为专属协议管辖法院的大阪地方法院予以裁决。


# 前言

本3D显示库（Lj3DView）用于将LJ-X8000A通过通讯库(LjDevCommunication.dll)取得的图像，在Windows平台上以3D图形进行绘制并显示的控件。


# 运行环境


项目 | 必要的环境

OS | Microsoft Windows 11 Pro (64bit)、Microsoft Windows 10 Pro (64bit)

CPU | 基于intel®CoreTM i5 处理器或更高

内存 | 16GB以上剩余内存

开发环境 | Microsoft Visual Studio 2017 C#7.3 或更高版本


・必要的硬件环境很大程度取决于作为处理对象的图像尺寸和所使用的处理功能。
・Windows是美国Microsoft Corporation在美国及其他国家的注册商标或商标。


## 基本运行环境

为了确保3D显示库的正确运行，必须准备如下环境：

### Microsoft C/C++ Runtime Library

Microsoft C Runtime Library。
请运行并安装vcredist_x64.exe。

### Microsoft .NET Framework

LjDevMeasure.dll基于.NET Framework 4.7.2开发。
请运行并安装ndp472-kb4054530-x86-x64-allos-enu.exe。

### CodeMeterRuntime

请运行并安装CodeMeterRuntime.exe。
此外，请将cpsevents-6002427文件夹放置在与执行文件相同的文件夹中。
cpsevents-6002427文件夹存储在C:\Program Files\KEYENCE \LJ Developer\lib\x64中。


# 文件构成

运行3D显示库必需的文件（LjDev3dView.dll、LjDev3dView.Core.dll、LjDevMeasure.dll、LjDevMeasure.Core.dll、LjDevCommon.dll、LjDevCommon.Core.dll、cpsevents-6002427文件夹）存储在如下位置
C:\Program Files\KEYENCE\LJ Developer\lib\x64


# 嵌入方法

请将下述文件/文件夹复制到与可执行程序所在的文件夹中（输出文件夹中）：


- LjDev3dView.dll

- LjDev3dView.Core.dll

- LjDevMeasure.dll

- LjDevMeasure.Core.dll

- LjDevCommon.dll

- LjDevCommon.Core.dll

- cpsevents-6002427文件夹


# Winform使用时的实施步骤

①通过项目的“引用”→“添加引用”打开引用管理器，从lib文件夹中添加下述DLL的引用。
LjDev3dView.dll（必需）、LjDevMeasure.dll、LjDevCommon.dll
②通过VisualStudio工具箱将WPF互操作性→ElementHost控件添加到窗体中。
③在namespace中添加“Keyence.LjDev3dView“。
④使用默认构造函数创建Lj3dView实例，并添加到_elementHost的Child属性。

```


​x


using Keyence.LjDev3dView;
```

```
using System;
```

```
using System.Windows.Forms;
```

```


```

```
namespace SampleApp
```

```
{
```

```
    public partial class MainForm : Form
```

```
    {
```

```
        private Lj3DView _viewport;
```

```


```

```
        public MainForm()
```

```
        {
```

```
            InitializeComponent();
```

```
            _viewport = new Lj3DView();
```

```
            _elementHost.Child = _viewport;
```

```
        }
```

```
    }
```

```
}
```
⑤调用SetImage函数设置高度数据和浓淡数据。


# 显示・属性・命令概要

## １）显示


项目 | 说明

数据 | 设定图像数据后，数据将在视图以3D形式显示。

检测结果 | 在3D视图上显示检测结果（结果面板・检测区域）


## ２）属性


项目 | 属性名称 | 说明

相机位置 | CameraPosition | 获取或设置相机的位置

点云/网格/线框显示切换 | GeometryType | 在点云/网格（Mesh）/线框三种显示形式间切换

线框尺寸 | WireFrameSpacing | 设置线框显示的尺寸

自动细化设置 | AutoThinning | 设定为True时，自动选择适当的显示细化比例

细化比例 | Thinning | 设置关闭自动细化设置时使用的点云数据细化比例

实际细化比例 | ActualThinning | 获取实际使用的细化比例

混合比例 | BlendWeight | 设置高度数据/浓淡数据的混合比例

调色板 | ColorPalette | 设置调色板的颜色

颜色范围 | ColorRange | 设置调色板对应的高度范围

侧壁透明度 | SideWallTransparent | 设置以网格（Mesh）显示时侧壁的透明度（在0到1的范围内设置）

网格范围 | GridRange | 获取可设置的网格位置的范围

网格位置 | GridPosition | 设置参照网格(Grid)的显示高度位置

Z缩放 | ZScale | 设置Z方向的缩放比例（在1到10的范围内设置）

平面颜色及透明度 | PlaneColor | 以ARGB形式设置平面的颜色和透明度

截面显示模式 | ProfileMode | 切换截面的显示方法

截面工具编号 | ProfileToolIndex | 设置截面工具的工具ID和要显示的截面轮廓编号

截面显示编号 | ProfileIndex | 设置要显示的截面轮廓的编号

截面透明度 | ProfileTransparent | 设置截面显示时的截面透明度，范围为 0-1。

瑕疵高亮显示 | DefectHighlight | 切换瑕疵、细微瑕疵的高亮显示ON/OFF

区域显示 | DisplayArea | 设置显示或隐藏检测区域

平面显示 | DisplayPlane | 设置显示或隐藏平面

结果面板显示 | DisplayBillboard | 设置显示或隐藏结果面板

坐标轴显示 | DisplayAxis | 设置显示或隐藏坐标轴

网格显示 | DisplayGrid | 设置显示或隐藏参照网格(Grid)

颜色条显示 | DisplayColorBar | 设置显示或隐藏颜色指示条

显示鼠标点坐标 | DisplayMouseHitPoint | 设置显示或隐藏鼠标指向点坐标

显示视角切换按钮 | DisplayViewpointOperation | 设置显示或隐藏视角切换按钮


## ３）命令


项目 | 命令名称 | 说明

放大/缩小 | ZoomInCommand, ZoomOutCommand | 操作显示视图放大/缩小

视野变更 | ZoomFitCommand, ZoomExtentsCommand | 操作显示视图的观察视野

变更颜色范围 | ColorRangeFitCommand, ColorRangeAreaFitCommand, ColorRangeResetCommand | 调整调色板对应的高度范围


# 详细说明


## １）显示设定

### 显示图像数据

> 执行SetImage设定高度/浓淡的图像数据，3D视图控件将以3D形式显示图像数据。

```


xxxxxxxxxx
```

```
public void SetImage(LHeightImage heightImage, LGrayImage grayImage)
```
参数名说明LHeightImage heightImage高度图像数据LGrayImage grayImage浓淡图像数据
```
xxxxxxxxxx
```

```
public void SetImage(LHeightImage heightImage)
```
参数名说明LHeightImage heightImage高度图像数据

### 清除图像数据

> 通过执行ClearImage，可清除3D视图控件当前显示的图像数据。

```


xxxxxxxxxx
```

```
public void ClearImage()
```

### 显示检测结果

> 执行SetToolInfo设置ILToolInfo后，将在3D视图控件上显示检测结果（结果数据面板和检测区域）。

```


xxxxxxxxxx
```

```
public void SetToolInfo(IListILToolInfo> toolInfo)
```

### 清除检测结果

> 通过执行ClearToolInfo后、可清除3D视图控件当前显示的检测结果（结果数据面板和检测区域）。

```


xxxxxxxxxx
```

```
public void ClearToolInfo()
```

### 获取高度数据范围

> 通过执行GetHeightRange，可以获取3D图像数据的高度范围。

```


xxxxxxxxxx
```

```
public void GetHeightRange(LHeightImage heightImage, out ushort min, out ushort max)
```
参数名说明LHeightImage heightImage高度图像数据out ushort min最小高度像素值out ushort max最大高度像素值

### 将屏幕坐标 (px) 转换为 3D 坐标 (mm)

> 将屏幕坐标（px）转换为对应的3D坐标。如果成功获取到3D坐标时，返回True，否则返回False。

```


xxxxxxxxxx
```

```
public bool TryGetPoint3D(Point screenPoint, out Point3D worldPoint)
```

### 标记显示

> 使用此函数，在指定3D坐标处显示标记。

```


xxxxxxxxxx
```

```
public void AddMark(Point point)
```

### 标记清除

> 执行ClearMark功能将清除显示的所有标记。

```


xxxxxxxxxx
```

```
public void ClearMark()
```

## ２）属性设置

### 获取或设置相机的位置

> 获取或设置相机的位置。

```


xxxxxxxxxx
```

```
public LCameraPosition CameraPosition { get; set; }
```

### 点云/网格/线框显示切换

> 在点云/网格（Mesh）/线框三种显示形式间切换。默认值为点云。

```


xxxxxxxxxx
```

```
public LGeometryType GeometryType { get; set; }
```

```


```

```
public enum LGeometryType
```

```
{
```

```
    Point,
```

```
    Mesh,
```

```
    WireFrame
```

```
}
```
成员名说明Point以点云方式显示Mesh以网格方式显示（Mesh）WireFrame以线框方式显示

### 线框尺寸

> 设置线框显示的尺寸。默认值为Eight (8)。

```


xxxxxxxxxx
```

```
public LWireFrameSpacing WireFrameSpacing { get; set; }
```

```


```

```
public enum LWireFrameSpacing
```

```
{
```

```
    Four,
```

```
    Eight,
```

```
    Twelve,
```

```
    SixteenD
```

```
}
```
成员名说明Four4Eight8Twelve12Sixteen16

### 自动细化设置

> 设定为True时，自动选择适当的显示细化比例。默认值为 True（自动）。

```


xxxxxxxxxx
```

```
public bool AutoThinning { get; set; }
```

### 细化比例

> 设置当自动细化设置为False时的显示细化比例。仅点云显示时有效。默认值为Quarter(1/4)。

```


xxxxxxxxxx
```

```
public LThinning Thinning { get; set; }
```

```


```

```
public enum LThinning
```

```
{
```

```
    Half,
```

```
    Quarter,
```

```
    OneEighth,
```

```
    OneSixteenth,
```

```
    OneThirtySecond
```

```
}
```
成员名说明Half1/2Quarter1/4OneEighth1/8OneSixteenth1/16OneThirtySecond1/32

### 实际细化比例

> 获取实际使用的细化比例。当自动细化设置为开时，以100万点为目标自动选择恰当的细化比例；当自动细化设置为关时，使用指定的细化比例。

```


xxxxxxxxxx
```

```
public LThinning ActualThinning { get; }
```

### 混合比例

> 设置高度数据/浓淡数据的混合比例，在0到1的范围内设定。混合图像的颜色计算方式:“R/G/B = 高度图像R/G/B×（1-混合比例）+浓淡图像R/G/B×混合比例”。
> 默认值为0.7。

```


xxxxxxxxxx
```

```
 public float BlendWeight { get; set; }
```

### 调色板

> 设置调色板的颜色。指定用于显示渐变颜色的颜色序列，序列开头对应颜色范围的Low，序列最后对应颜色范围的High。默认值为Rainbow。

```


xxxxxxxxxx
```

```
public LColorPalette ColorPalette { get; set; }
```

### 颜色范围

> 以mm为单位指定调色板对应的高度范围。通过指定Z系数生成颜色范围。
> 生成的颜色范围根据Z系数自动计算下限值(LowerLimit)和上限值(HigherLimit),可在上下限值之间指定Low和High。

```


xxxxxxxxxx
```

```
public LColorRange ColorRange { get; set; }
```

### 侧壁透明度

> 设置网格(Mesh)显示时侧壁的透明度，在0到1的范围内设置。默认值为0.6。

```


xxxxxxxxxx
```

```
public float SideWallTransparent { get; set; }
```

### 网格范围

> 获取可设置的网格高度位置的范围。

```


xxxxxxxxxx
```

```
public LGridRange GridRange { get; }
```

### 网格位置

> 设置参考网格(Grid)的显示高度位置，单位：mm。初始位置为接近工件高度最低处的mm单位整数值。默认值为0。

```


xxxxxxxxxx
```

```
public int GridPosition { get; set; }
```

### Z缩放

> 设置Z方向的缩放比例，在1~5的范围内设置。默认值为1。

```


xxxxxxxxxx
```

```
public double ZScale { get; set; }
```

### 平面颜色和透明度

> 以ARGB形式设置平面的颜色和透明度。默认值为#26FFFFFF。

```


xxxxxxxxxx
```

```
public Color PlaneColor { get; set; }
```

### 截面显示模式

> 切换截面显示方法。

```


xxxxxxxxxx
```

```
public LProfileMode ProfileMode { get; set; }
```

```


```

```
public enum LProfileMode
```

```
{
```

```
    None,
```

```
    CrossSection,
```

```
    Domino
```

```
}
```

```


```
成员名说明None无截面显示CrossSection3D截面显示Domino仅截面显示

### 工具截面编号

> 设置截面工具的工具ID和要显示的截面轮廓编号

```


xxxxxxxxxx
```

```
public LProfileToolIndex ProfileToolIndex { get; set; }
```
成员名说明ToolId工具 IDProfileIndex截面的编号

### 截面显示编号

> 设置要显示的截面轮廓的编号

```


xxxxxxxxxx
```

```
public int ProfileIndex { get; set; }
```

### 截面透明度

> 设置3D截面显示或仅截面显示时的截面透明度，范围为 0-1。默认值为 0.9。

```


xxxxxxxxxx
```

```
public float ProfileTransparent { get; set; }
```

### 瑕疵高亮显示

> 切换瑕疵、细微瑕疵的高亮显示ON/OFF。

```


xxxxxxxxxx
```

```
public bool DefectHighlight { get; set; }
```

### 区域显示

> 设置显示或隐藏检测区域。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayArea { get; set; }
```

### 平面显示

> 设置显示或隐藏平面。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayPlane { get; set; }
```

### 结果面板显示

> 设置显示或隐藏结果面板。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayBillboard { get; set; }
```

### 坐标轴显示

> 设置显示或隐藏坐标轴。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayAxis { get; set; }
```

### 网格显示

> 设置显示或隐藏参照网格(Grid)。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayGrid { get; set; }
```

### 颜色条显示

> 设置显示或隐藏颜色指示条。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayColorBar { get; set; }
```

### 鼠标点坐标显示

> 设置显示或隐藏鼠标指向点坐标。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayMouseHitPoint { get; set; }
```

### 显示视角切换按钮

> 设置显示或隐藏视角切换按钮。（true：显示 / false：隐藏，默认值为true）

```


xxxxxxxxxx
```

```
public bool DisplayViewpointOperation { get; set; }
```

## ３）命令设置方法

### 初始化

> 执行InitializeCommand函数，执行初始化处理。

```


xxxxxxxxxx
```

```
public void InitializeCommand()
```

### 放大

> 执行ZoomInCommand函数，可放大3D视图。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ZoomInCommand()
```

### 缩小

> 执行ZoomOutCommand函数，可缩小3D视图。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ZoomOutCommand()
```

### 自适应缩放

> 执行ZoomFitCommand函数，可在视角方向上自适应3D视图视野。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ZoomFitCommand()
```

### 视角自适应缩放

> 执行ZoomExtentsCommand函数，将在Z方向上对3D视图进行视野贴合。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ZoomExtentsCommand()
```

### 颜色范围贴合

> 执行ColerRangeFitCommand函数，可将彩色范围适配到图像数据的实际高度范围。
> 执行命令后的颜色范围可以从Lj3DView的属性中获取。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ColorRangeFitCommand()
```

### 彩色范围区域贴合

> 执行ColerRangeAreaFitCommand函数，可将彩色范围贴合到区域的最小值~最大值范围。
> 执行命令后的颜色范围可以从Lj3DView的属性中获取。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ColorRangeAreaFitCommand()
```

### 彩色范围复位

> 执行ColerRangeResetCommand函数，可重置彩色范围。
> 执行重置后的颜色范围可以从Lj3DView的属性中获取。

```
xxxxxxxxxx
```

```
public Lj3DViewCommand ColorRangeResetCommand()
```
