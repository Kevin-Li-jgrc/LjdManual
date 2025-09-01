[软件使用许可协议条款](#软件使用许可协议条款)[前言](#前言)[运行环境](#运行环境)[基本运行环境](#基本运行环境)[Microsoft C/C++ Runtime Library](#microsoft-cc++-runtime-library)[Microsoft .NET Framework](#microsoft-net-framework)[CodeMeterRuntime](#codemeterruntime)[文件构成](#文件构成)[嵌入方法](#嵌入方法)[数据结构](#数据结构)[坐标系](#坐标系)[基准平面(Z=0)上的坐标系](#基准平面z=0上的坐标系)[角度](#角度)[图像](#图像)[高度图像](#高度图像)[浓淡图像](#浓淡图像)[区域设定](#区域设定)[接口](#接口)[参照区域](#参照区域)[矩形](#矩形)[旋转矩形](#旋转矩形)[圆](#圆)[椭圆](#椭圆)[圆环](#圆环)[圆弧](#圆弧)[直线](#直线)[形状范围](#形状范围)[形状](#形状)[2D点](#2d点)[3D点](#3d点)[平面](#平面)[位置偏移信息](#位置偏移信息)[检出形状](#检出形状)[检出线](#检出线)[检出点](#检出点)[检出圆](#检出圆)[测量结果信息](#测量结果信息)[测量距离](#测量距离)[测量角度](#测量角度)[截面测量相关数据](#截面测量相关数据)[截面数据](#截面数据)[截面坐标系中的区域](#截面坐标系中的区域)[截面坐标系中的形状](#截面坐标系中的形状)[点](#点)[线](#线)[截面坐标系中的检测形状](#截面坐标系中的检测形状)[接口](#接口-2)[线](#线-2)[圆](#圆-2)[测量功能](#测量功能)[图像过滤器](#图像过滤器)[平滑化](#平滑化)[方法定义](#方法定义)[处理参数](#处理参数)[高斯](#高斯)[方法定义](#方法定义-2)[处理参数](#处理参数-2)[中间值](#中间值)[方法定义](#方法定义-3)[处理参数](#处理参数-3)[无效像素控制](#无效像素控制)[方法定义](#方法定义-4)[处理参数](#处理参数-4)[去除突起状干扰](#去除突起状干扰)[方法定义](#方法定义-5)[处理参数](#处理参数-5)[XY等比例补正](#xy等比例补正)[方法定义](#方法定义-6)[处理参数](#处理参数-6)[倾斜补正](#倾斜补正)[方法定义](#方法定义-7)[参数](#参数)[自由曲面补正](#自由曲面补正)[方法定义](#方法定义-8)[参数](#参数-2)[膨胀(扩大白色)](#膨胀扩大白色)[方法定义](#方法定义-9)[参数](#参数-3)[收缩(扩大黑色)](#收缩扩大黑色)[方法定义](#方法定义-10)[参数](#参数-4)[开运算(去除白像素干扰)](#开运算去除白像素干扰)[方法定义](#方法定义-11)[参数](#参数-5)[闭运算(去除黑像素干扰)](#闭运算去除黑像素干扰)[方法定义](#方法定义-12)[参数](#参数-6)[二值化](#二值化)[方法定义](#方法定义-13)[参数](#参数-7)[斑点过滤器](#斑点过滤器)[方法定义](#方法定义-14)[参数](#参数-8)[模糊处理](#模糊处理)[方法定义](#方法定义-15)[参数](#参数-9)[对比度转换](#对比度转换)[方法定义](#方法定义-16)[参数](#参数-10)[实时浓淡补正](#实时浓淡补正)[方法定义](#方法定义-17)[参数](#参数-11)[黑白反转](#黑白反转)[方法定义](#方法定义-18)[振动补正](#振动补正)[参数](#参数-12)[补正基准设定](#补正基准设定)[接口](#接口-3)[边缘设定](#边缘设定)[平均化设定](#平均化设定)[峰值设定](#峰值设定)[谷值设定](#谷值设定)[直线设定](#直线设定)[交点设定](#交点设定)[X补正](#x补正)[方法定义](#方法定义-19)[参数](#参数-13)[Z补正](#z补正)[方法定义](#方法定义-20)[参数](#参数-14)[XZ补正](#xz补正)[方法定义](#方法定义-21)[参数](#参数-15)[θ补正](#θ补正)[方法定义](#方法定义-22)[参数](#参数-16)[图像合成](#图像合成)[图像合成](#图像合成-2)[方法定义](#方法定义-23)[处理参数](#处理参数-7)[检测工具](#检测工具)[检测工具类](#检测工具类)[访问检测结果](#访问检测结果)[执行检测(Execute)](#执行检测execute)[更新主控基准(UpdateReference)](#更新主控基准updatereference)[高度测量](#高度测量)[类定义](#类定义)[方法定义](#方法定义-24)[检测参数／结果](#检测参数结果)[平面度测量](#平面度测量)[类定义](#类定义-2)[方法定义](#方法定义-25)[检测参数／结果](#检测参数结果-2)[图形搜索](#图形搜索)[类定义](#类定义-3)[方法定义](#方法定义-26)[检测参数／结果](#检测参数结果-3)[形状范围](#形状范围-2)[类定义](#类定义-4)[方法定义](#方法定义-27)[检测参数／结果](#检测参数结果-4)[瑕疵](#瑕疵)[类定义](#类定义-5)[方法定义](#方法定义-28)[检测参数／结果](#检测参数结果-5)[细微瑕疵](#细微瑕疵)[类定义](#类定义-6)[方法定义](#方法定义-29)[检测参数／结果](#检测参数结果-6)[平面检测](#平面检测)[类定义](#类定义-7)[方法定义](#方法定义-30)[检测参数／结果](#检测参数结果-7)[点检测](#点检测)[类定义](#类定义-8)[方法定义](#方法定义-31)[检测参数／结果](#检测参数结果-8)[直线检测](#直线检测)[类定义](#类定义-9)[方法定义](#方法定义-32)[检测参数／结果](#检测参数结果-9)[圆检测](#圆检测)[类定义](#类定义-10)[方法定义](#方法定义-33)[检测参数／结果](#检测参数结果-10)[直线间的中心线](#直线间的中心线)[类定义](#类定义-11)[方法定义](#方法定义-34)[检测参数／结果](#检测参数结果-11)[经过两点的直线](#经过两点的直线)[类定义](#类定义-12)[方法定义](#方法定义-35)[检测参数／结果](#检测参数结果-12)[直线间的交点](#直线间的交点)[类定义](#类定义-13)[方法定义](#方法定义-36)[检测参数／结果](#检测参数结果-13)[点和点的中点](#点和点的中点)[类定义](#类定义-14)[方法定义](#方法定义-37)[检测参数／结果](#检测参数结果-14)[线与线的距离测量](#线与线的距离测量)[类定义](#类定义-15)[方法定义](#方法定义-38)[检测参数／结果](#检测参数结果-15)[线与点的距离测量](#线与点的距离测量)[类定义](#类定义-16)[方法定义](#方法定义-39)[检测参数／结果](#检测参数结果-16)[线与圆的距离测量](#线与圆的距离测量)[类定义](#类定义-17)[方法定义](#方法定义-40)[检测参数／结果](#检测参数结果-17)[点与点的距离测量](#点与点的距离测量)[类定义](#类定义-18)[方法定义](#方法定义-41)[检测参数／结果](#检测参数结果-18)[点与圆的距离测量](#点与圆的距离测量)[类定义](#类定义-19)[方法定义](#方法定义-42)[检测参数／结果](#检测参数结果-19)[圆与圆的距离测量](#圆与圆的距离测量)[类定义](#类定义-20)[方法定义](#方法定义-43)[检测参数／结果](#检测参数结果-20)[线与线的角度测量](#线与线的角度测量)[类定义](#类定义-21)[方法定义](#方法定义-44)[检测参数／结果](#检测参数结果-21)[截面测量相关工具](#截面测量相关工具)[截面提取](#截面提取)[接口](#接口-4)[平滑过滤器参数](#平滑过滤器参数)[中间值过滤器参数](#中间值过滤器参数)[截面提取](#截面提取-2)[方法定义](#方法定义-45)[检测参数／结果](#检测参数结果-22)[连续截面提取](#连续截面提取)[方法定义](#方法定义-46)[检测参数／结果](#检测参数结果-23)[连续截面提取(自由)](#连续截面提取自由)[方法定义](#方法定义-47)[检测参数／结果](#检测参数结果-24)[截面测量](#截面测量)[参数](#参数-17)[直线/圆检测设定](#直线圆检测设定)[测量对象设定](#测量对象设定)[接口](#接口-5)[峰值设定](#峰值设定-2)[谷值设定](#谷值设定-2)[平均设定](#平均设定)[边缘设定](#边缘设定-2)[拐点设定](#拐点设定)[交点设置](#交点设置)[截面高度测量](#截面高度测量)[方法定义](#方法定义-48)[检测参数／结果](#检测参数结果-25)[截面段差测量](#截面段差测量)[方法定义](#方法定义-49)[检测参数／结果](#检测参数结果-26)[截面位置测量](#截面位置测量)[方法定义](#方法定义-50)[检测参数／结果](#检测参数结果-27)[截面宽度测量](#截面宽度测量)[方法定义](#方法定义-51)[检测参数／结果](#检测参数结果-28)[专用应用工具](#专用应用工具)[Pin针检测](#pin针检测)[类定义](#类定义-22)[方法定义](#方法定义-52)[检测参数／结果](#检测参数结果-29)[涂胶检测](#涂胶检测)[类定义](#类定义-23)[方法定义](#方法定义-53)[检测参数／结果](#检测参数结果-30)[实用程序](#实用程序)[测量结果访问扩展方法](#测量结果访问扩展方法)[方法定义](#方法定义-54)[获取测量值](#获取测量值)[获取测量值单位](#获取测量值单位)[获取显示用文字](#获取显示用文字)[获取各区域结果的测量值](#获取各区域结果的测量值)[获取各区域结果的测量值单位](#获取各区域结果的测量值单位)[获取各区域结果的显示用文字](#获取各区域结果的显示用文字)[定义](#定义)[工具公用](#工具公用)[测量值单位（LUnitType）](#测量值单位lunittype)[特定工具](#特定工具)[高度测量](#高度测量-2)[平面度测量](#平面度测量-2)[图形搜索](#图形搜索-2)[瑕疵](#瑕疵-2)[细微瑕疵](#细微瑕疵-2)[平面检测](#平面检测-2)[点检测](#点检测-2)[直线检测](#直线检测-2)[圆检测](#圆检测-2)[直线间的中心线](#直线间的中心线-2)[经过两点的直线](#经过两点的直线-2)[直线间的交点](#直线间的交点-2)[点与点的中点](#点与点的中点)[线与线的距离测量](#线与线的距离测量-2)[线与点的距离测量](#线与点的距离测量-2)[线与圆的距离测量](#线与圆的距离测量-2)[点与点的距离测量](#点与点的距离测量-2)[点与圆的距离测量](#点与圆的距离测量-2)[圆与圆的距离测量](#圆与圆的距离测量-2)[线与线的角度测量](#线与线的角度测量-2)[截面高度测量](#截面高度测量-2)[截面段差测量](#截面段差测量-2)[截面位置测量](#截面位置测量-2)[截面宽度测量](#截面宽度测量-2)[Pin针检测](#pin针检测-2)[涂胶检测](#涂胶检测-2)[错误代码](#错误代码)


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

在本测量库中，只能处理通过LJ Developer通信库（LjDevCommunication.dll）取得的图像。
另外，以XY等比例（无失真）图像的处理为前提。
在XY间距不相等时，请先使用图像过滤器中的XY等比例补正((EqualizePixelDensity))处理后再执行其他处理。

# 运行环境


项目 | 必要条件

OS | Microsoft Windows 11 Pro (64bit)、Microsoft Windows 10 Pro (64bit)

CPU | 基于intel®CoreTM i5 处理器或更高

内存 | 16GB以上剩余内存

开发环境 | Microsoft Visual Studio 2017 C#7.3 或更高版本


・必要的硬件环境很大程度取决于作为处理对象的图像尺寸和所使用的处理功能。
・Windows是美国Microsoft Corporation在美国及其他国家的注册商标或商标。

## 基本运行环境

为了确保测量库的正确运行，必须准备如下环境：

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

运行测量库所需的文件（LjDevMeasure.dll、LjDevMeasure.Core.dll、LjDevCommon.dll、LjDevCommon.Core.dll）存储在如下位置C:\Program Files\KEYENCE\LJ Developer\lib\x64

# 嵌入方法

请将以下文件放置在与可执行应用程序相同的文件夹中：


- LjDevMeasure.dll

- LjDevMeasure.Core.dll

- LjDevCommon.dll

- LjDevCommon.Core.dll


# 数据结构

## 坐标系

### 基准平面(Z=0)上的坐标系

图像的左上角定义为原点（X，Y）=（0,0），沿右方向/下方向X/Y增加。

### 角度

(X,Y)=(1,0)方向为0°、沿顺时针方向增加。

## 图像

### 高度图像

LJ Developer处理的高度图像数据。
可以通过通信库(LjDevCommunication.dll)或测量库(LjDevMeasure.dll)取得。

```


struct LHeightImage{
```

```
    public ushort[] Source;
```

```
    public int XSize;
```

```
    public int YSize;
```

```
    public double CoefficientX;
```

```
    public double CoefficientY;
```

```
    public double CoefficientZ;
```

```
}
```
成员名称说明Source各像素的高度信息。使用无符号16位数据表示。
像素值到实际尺寸(mm)变换：(像素值－32768) ∗ CoefficientZXSize／YSizeX方向／Y方向的像素个数CoefficientX／CoefficientYX／Y各像素间的间距(mm)CoefficientZ高度信息的1阶对应多少毫米的值
### 浓淡图像
LJ Developer处理的灰度图像数据。
可以通过通信库(LjDevCommunication.dll)或测量库(LjDevMeasure.dll)取得。

```


xxxxxxxxxx
```

```
struct LGrayImage{
```

```
    public byte[] Source;
```

```
    public int XSize;
```

```
    public int YSize;
```

```
    public double CoefficientX;
```

```
    public double CoefficientY;
```

```
}
```
成员名称说明Source各像素的亮度信息。使用无符号8位数据表示XSize／YSizeX方向／Y方向的像素个数CoefficientX／CoefficientYX／Y各像素间的间距(mm)
## 区域设定

### 接口
用于抽象处理区域的接口定义

```


xxxxxxxxxx
```

```
public interface ILRegion
```

```
{
```

```
}
```

### 参照区域
这是工具生成的区域。
可与瑕疵/细微瑕疵工具一起使用。

```


xxxxxxxxxx
```

```
public struct LReferableRegion
```

```
{
```

```
    public bool Enable;
```

```
    public ILRegion Region;
```

```
}
```
成员名称说明Enable指示生成的区域是否有效。Region区域信息。
### 矩形

```
xxxxxxxxxx
```

```
public struct LRectangle : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double Width;
```

```
    public double Height;
```

```
}
```
成员名称说明Center中心坐标(mm)Width矩形宽度(mm)Height矩形高度(mm)
### 旋转矩形

```
xxxxxxxxxx
```

```
public struct LRotatedRectangle : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double Width;
```

```
    public double Height;
```

```
    public double Angle;
```

```
}
```
成员名称说明Center中心坐标(mm)Width矩形宽度(mm)Height矩形高度(mm)Angle旋转角度(°)　0≦设定值＜360°
### 圆

```
xxxxxxxxxx
```

```
public struct LCircle : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double Radius;
```

```
}
```
成员名称说明Center中心坐标(mm)Radius半径(mm)
### 椭圆

```
xxxxxxxxxx
```

```
public struct LOval : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double RadiusX;
```

```
    public double RadiusY;
```

```
    public double Angle;
```

```
}
```
成员名称说明Center中心坐标(mm)RadiusX“旋转角度”＝0°时的X方向半径(mm)RadiusY“旋转角度”＝0°时的Y方向半径(mm)Angle旋转角度(°)　0≦设定值＜360°
### 圆环
以“半径”为中心的”宽度“部分的范围为测量区域。

```


xxxxxxxxxx
```

```
public struct LRing : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double Radius;
```

```
    public double Width;
```

```
}
```
成员名称说明Center中心坐标(mm)Radius半径(mm)Width宽度(mm)
### 圆弧
在以“半径”为中心的”宽度“部分的范围中，开始角度~结束角度的部分为测量范围。

```


xxxxxxxxxx
```

```
public struct LArc : ILRegion
```

```
{
```

```
    public LDPoint2D Center;
```

```
    public double Radius;
```

```
    public double Width;
```

```
    public double StartAngle;
```

```
    public double EndAngle;
```

```
}
```
成员名称说明Center中心坐标(mm)Radius半径(mm)Width宽度(mm)StartAngle开始角度(°) 0≦设定值＜360°EndAngle结束角度(°) 0≦设定值＜360°
### 直线

```
xxxxxxxxxx
```

```
public struct LLine : ILRegion
```

```
{
```

```
    public LDPoint2D Start;
```

```
    public LDPoint2D End;
```

```
}
```
成员名称说明Start起点坐标(mm)。End终点坐标(mm)。
### 形状范围

```
​xpublic struct LShapeRegion : ILRegion
```

```
{
```

```
    public int SourceImageXSize;
```

```
    public int SourceImageYSize;
```

```
    public double SourceImageCoefficientX;
```

```
    public double SourceImageCoefficientY;
```

```


```

```
    public LGrayImage ToBinaryImage();
```

```
}
```
成员名称说明SourceImageXSize形状范围生成源图像的 X 方向像素数。SourceImageYSize形状范围生成源图像的 Y 方向像素数。SourceImageCoefficientX形状范围生成源图像在 X 方向的间距。SourceImageCoefficientY形状范围生成源图像在 Y 方向的间距。ToBinaryImage 方法可用于获取形状范围的二值图像。白色像素部分即为形状范围。
形状范围只能用于与生成形状范围的原始图像大小/间距相同的图像。
可在 瑕疵 / 细微瑕疵工具和中间值 / 高斯 / 平滑化 / 去除突起状干扰 / 无效像素控制 / 自由曲面补正 / 膨胀 / 收缩 / 模糊 / 对比度转换 / 实时浓淡补正过滤器中使用。
形状范围只能用作单个测量区域。不能用作屏蔽区域。
此外，当使用形状范围作为测量对象区域时，无法使用位置补正和屏蔽区域。

## 形状

### 2D点

```


xxxxxxxxxx
```

```
public struct LDPoint2D
```

```
{
```

```
    public double X;
```

```
    public double Y;
```

```
}
```
成员名称说明XX坐标(mm)YY坐标(mm)
### 3D点

```
xxxxxxxxxx
```

```
public struct LDPoint3D
```

```
{
```

```
    public double X;
```

```
    public double Y;
```

```
    public double Z;
```

```
}
```
成员名称说明XX坐标(mm)YY坐标(mm)ZZ坐标(mm)
### 平面

```
xxxxxxxxxx
```

```
public struct LPlane
```

```
{
```

```
    public bool Enable;
```

```
    public double A;
```

```
    public double B;
```

```
    public double C;
```

```
    public static LPlane headZeroZ => new LPlane(0, 0, 0);
```

```
}
```
成员名称说明Enable表示是否作为平面信息有效A以z=ax+by+c平面公式表示时的平面系数aB以z=ax+by+c平面公式表示时的平面系数bC以z=ax+by+c平面公式表示时的平面系数cheadZeroZLJ的感测头基准面（Z=0的平面）对应的常数对象
## 位置偏移信息
表示X/Y方向的偏移量及旋转方向的偏移量和旋转中心。

```


xxxxxxxxxx
```

```
struct LDeltaPosition
```

```
{
```

```
    public bool Enable;
```

```
    public LDPoint2D Center;
```

```
    public double X;
```

```
    public double Y;
```

```
    public double Theta;
```

```
}
```
成员名称说明Enable表示作为位置偏移信息是否有效。Center旋转中心的坐标(mm)XX方向的偏移量(mm)YY方向的偏移量(mm)Theta旋转角度(°) 0≦设定值＜360°
## 检出形状

### 检出线

```
xxxxxxxxxx
```

```
public struct LDetectLine2D
```

```
{
```

```
    public bool Enable;
```

```
    public LLine Line;
```

```
}
```
成员名称说明Enable表示检测结果是否有效。Line检测出的直线的信息。
### 检出点

```
xxxxxxxxxx
```

```
public struct LDetectPoint2D
```

```
{
```

```
    public bool Enable;
```

```
    public LDPoint2D Point;
```

```
}
```
成员名称说明Enable表示检测结果是否有效。Point检测出的点的信息(mm)。
### 检出圆

```
xxxxxxxxxx
```

```
public struct LDetectCircle2D
```

```
{
```

```
    public bool Enable;
```

```
    public LCircle Circle;
```

```
}
```
成员名称说明Enable表示检测结果是否有效。Circle检测出的圆的信息。
## 测量结果信息

### 测量距离

```
xxxxxxxxxx
```

```
public struct LMeasuredDistance
```

```
{
```

```
    public double Distance;
```

```
    public LDPoint2D StartPoint;
```

```
    public LDPoint2D EndPoint;
```

```
}
```
成员名称说明Distance测量出的距离(mm)。StartPoint测量距离时的起点(mm)。EndPoint测量距离时的终点(mm)。
### 测量角度

```
xxxxxxxxxx
```

```
public struct LMeasuredAngle
```

```
{
```

```
    public double Angle;
```

```
    public LDPoint2D Center;
```

```
    public double StartAngle;
```

```
    public double EndAngle;
```

```
}
```
成员名称说明Angle测量出的角度(°)。Center角度测量时的中点坐标(mm)。StartAngle角度测量时的起始角度(°)。EndAngle角度测量时的终止角度(°)。
## 截面测量相关数据

### 截面数据

```
xxxxxxxxxx
```

```
struct LProfile{
```

```
    public int Count;
```

```
    public double[] Height;
```

```
    public byte[] Luminance;
```

```
    public double Pitch;
```

```
    public LDPoint2D Origin;
```

```
    public double Angle;
```

```
    public LPlane Plane;
```

```
}
```
成员名称说明Count数据的数量(Height／Luminance)。Height高度值数组(mm単位)。Luminance亮度值数组。没有亮度数据时为NULL。Pitch高度值数据的间距。Origin截面轮廓数据第一点在高度图像上的X/Y坐标。Angle截面轮廓的延伸方向(0≦Angle＜360)。Plane提取截面时参照的基准平面。
### 截面坐标系中的区域

```
xxxxxxxxxx
```

```
struct LProfileRange{
```

```
    public double Start;
```

```
    public double End;
```

```
}
```
成员名称说明Start测量起始位置X坐标（mm）End测量结束位置X坐标（mm）
### 截面坐标系中的形状

#### 点

```
xxxxxxxxxx
```

```
struct LProfileDPoint{
```

```
    public double X;
```

```
    public double Z;
```

```
}
```
成员名称说明XX坐标(mm)。ZZ坐标(mm)。
### 线

```
xxxxxxxxxx
```

```
struct LProfileLine{
```

```
    public double A;
```

```
    public double B;
```

```
}
```
成员名称说明A以z=ax+b公式表示时的之后直线系数a。B以z=ax+b公式表示时的之后直线系数b。
### 截面坐标系中的检测形状

#### 接口
这是用于抽象处理截面坐标系中检测到的形状的接口定义。

```


xxxxxxxxxx
```

```
public interface ILDetectProfileShape
```

```
{
```

```
}
```

#### 线

```
xxxxxxxxxx
```

```
struct LDetectProfileLine : ILDetectProfileShape
```

```
{
```

```
    public double A;
```

```
    public double B;
```

```
}
```
成员名称说明A以z=ax+b公式表示时的之后直线系数a。B以z=ax+b公式表示时的之后直线系数b。
#### 圆

```
xxxxxxxxxx
```

```
public struct LDetectProfileCircle : ILDetectProfileShape
```

```
{
```

```
    public LProfileDPoint Center;
```

```
    public double Radius;
```

```
}
```
成员名称说明Center中心坐标(mm)。Radius半径(mm)。
# 测量功能

## 图像过滤器
图像过滤器通过静态类LImageFilter的静态方法提供、可以用LImageFilter.Average(...)这样的方式进行调用。
此外、同时以扩展方法方法提供，因此，还可以使用image.Average(...)这样的方式进行调用。

### 平滑化

#### 方法定义

```


xxxxxxxxxx
```

```
LErrorCode Smoothing(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LSmoothingParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据filterImage输出处理后的高度图像数据regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Smoothing(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LSmoothingParam param)
```

#### 处理参数

```
xxxxxxxxxx
```

```
struct LSmoothingParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    int Size;
```

```
    bool SuppressingExpansion;
```

```
    bool UsingOutsideRegionPixels;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Size设定预处理的参照范围大小(3~127间的奇数)（单位：像素）SuppressingExpansion由于过滤处理导致高度图像的轮廓比实际更粗时，设定为True可以抑制变化UsingOutsideRegionPixels指定在处理区域边界处的数据时，是否将区域外的数据作为参考值也添加到处理中（设定True时，参考区域外数据）
### 高斯

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Gaussian(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LGaussianParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据filterImage输出处理后的高度图像数据regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Gaussian(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LGaussianParam param)
```

#### 处理参数

```
xxxxxxxxxx
```

```
struct LGaussianParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LGaussianSize Size;
```

```
    bool SuppressingExpansion;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Size指定预处理的参照范围大小（3×3或5×5）（单位：像素）SuppressingExpansion由于过滤处理导致高度图像的轮廓比实际更粗时，设定为True可以抑制变化
### 中间值

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Median(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LMedianParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据filterImage输出处理后的高度图像数据regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Median(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LMedianParam param)
```

#### 处理参数

```
xxxxxxxxxx
```

```
struct LMedianParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LMedianSize Size;
```

```
    bool SuppressingExpansion;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Size指定预处理的参照范围大小（3×3或5×5）（单位：像素）SuppressingExpansion由于过滤处理导致高度图像的轮廓比实际更粗时，设定为True可以抑制变化
### 无效像素控制
对于无效像素，参照其附近的有效像素推测高度数据来抑制无效数据。对于有效数据，不做任何处理。

#### 方法定义

```


xxxxxxxxxx
```

```
public static LErrorCode InvalidPixelSuppression(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LInvalidPixelSuppressionParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据filterImage输出处理后的高度图像数据regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode InvalidPixelSuppression(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LInvalidPixelSuppressionParam param)
```

#### 处理参数

```
xxxxxxxxxx
```

```
struct LInvalidPixelSuppressionParam
```

```
{
```

```
    int SuppressionLevel;
```

```
    LInvalidPixelSuppressionAdjustmentWidth AdjustmentWidth;
```

```
    bool SuppressingOutlineExpansion;
```

```
}
```
成员名称说明SuppressionLevel在1~9之间指定抑制强度。数值越大，能对越大范围的无效数据进行抑制。AdjustmentWidth抑制时的调整幅度，通常指定为"粗"。
选择“粗”可提高抑制效果，但剩余的无效像素和有效像素的分界线将以中间值进行插补。SuppressingOutlineExpansion由于过滤处理导致高度图像的轮廓比实际更粗时，设定为True可以抑制变化
仅调节宽度（AdjustmentWidth）指定为正常时有效。
### 去除突起状干扰
可去除由于干扰造成的高出周围高度的像素，去除的凸起点将被处理为无效像素。

#### 方法定义

```


xxxxxxxxxx
```

```
LErrorCode SpikeNoiseCut(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LSpikeNoiseCutParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据filterImage输出处理后的高度图像数据regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode SpikeNoiseCut(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LSpikeNoiseCutParam param)
```

#### 处理参数

```
xxxxxxxxxx
```

```
struct LSpikeNoiseCutParam
```

```
{
```

```
    LSpikeNoiseCutCutTarget CutTarget;
```

```
    LSpikeNoiseCutProcessingDirection ProcessingDirection;
```

```
    int CutSizeX;
```

```
    int CutSizeY;
```

```
    double CutThreshold;
```

```
}
```
成员名称说明CutTarget从“高/低/两者”中选择要去除的凸起干扰类型ProcessingDirection从"X/Y/XY"中选择处理方向，目标方向上的干扰将被消除
例如，选择X方向时，则去除图像上纵向连续的干扰，保留横向连续的干扰CutSizeX去除横向尺寸小于或等于此大小（单位:像素）的干扰。此参数仅在“处理方向“指定为X或XY时有效CutSizeY去除纵向尺寸小于或等于此大小（单位:像素）的干扰。此参数仅在“处理方向“指定为Y或XY时有效CutThreshold去除凸起高度大于或等于此大小的干扰（相对于周围的像素的高度差，单位：mm）
### XY等比例补正
将要处理的目标图像的XY像素间间距（CoefficientX/CoefficientY）对齐，将图像的X/Y比例修正为1：1。

#### 方法定义

```


xxxxxxxxxx
```

```
LErrorCode EqualizePixelDensity(
```

```
    this LHeightImage heightImage, out LHeightImage filterImage, LEqualizePixelDensityParam param)
```

```
LErrorCode EqualizePixelDensity(
```

```
    this LGrayImage grayImage, out LGrayImage filterImage, LEqualizePixelDensityParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据grayImage输入作为处理对象的浓淡图像数据filterImage输出处理后的高度图像/浓淡图像数据param输入指定过滤器的具体处理参数
#### 处理参数
本处理没有处理参数(保留)。

```


xxxxxxxxxx
```

```
struct LEqualizePixelDensityParam
```

```
{
```

```
}
```

### 倾斜补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode TransformBasedOnPlane(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LPlane referencePlane,
```

```
    LTransformBasedOnPlaneParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。filterImage输出处理后的高度图像数据。referencePlane输入其他工具检出的平面（作为参考）。param输入指定过滤器的具体处理参数。可选输入
#### 参数

```
xxxxxxxxxx
```

```
struct LTransformBasedOnPlaneParam
```

```
{
```

```
    double Offset;
```

```
    double Gain;
```

```
}
```
成员名称说明Offset将输入的平面偏移指定量（mm），然后进行差分。Gain指定补正时的高度倍率，指定为1时，等倍输出。
### 自由曲面补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode TransformBasedOnFreeFormedPlane(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LTransformBasedOnFreeFormedPlaneParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。filterImage输出处理后的高度图像数据。regions输入在heightImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入。maskRegions输入在heightImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数。以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode TransformBasedOnFreeFormedPlane(this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LTransformBasedOnFreeFormedPlaneParam param)
```
/Todo LTransformBasedOnFreeFormedPlaneParam、LFreeFormedPlaneParam参数名称不一致

#### 参数

```


xxxxxxxxxx
```

```
struct LTransformBasedOnFreeFormedPlaneParam
```

```
{
```

```
    LTransformBasedOnFreeFormedPlaneProcessingDirection ProcessingDirection;
```

```
    int ExtractSize;
```

```
    bool ReferOutside;
```

```
    double Offset;
```

```
    double Gain;
```

```
}
```
成员名称说明ProcessingDirection指定处理方向（X/Y/XY）。ExtractSize指定提取大小。ReferOutside指定为True时，在处理区域边界的数据时，将区域外的数据也添加到处理中。Offset将检出的自由曲面偏移指定量（mm），然后进行差分。Gain指定补正时的高度倍率，指定为1时，等倍输出。
### 膨胀(扩大白色)

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Dilation(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LDilationParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Dilation(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LDilationParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LDilationParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LProcessingShape Shape;
```

```
    int Size;
```

```
    LProcessingDirection Direction;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Shape指定处理形状。Size指定过滤器大小。尺寸越大，作用越强。Direction指定膨胀方向。
### 收缩(扩大黑色)

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Erosion(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LErosionParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Erosion(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LErosionParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LErosionParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LProcessingShape Shape;
```

```
    int Size;
```

```
    LProcessingDirection Direction;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Shape指定处理形状。Size指定过滤器大小。尺寸越大，作用越强。Direction指定收缩方向。
### 开运算(去除白像素干扰)

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Opening(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LOpeningParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Opening(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LOpeningParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LOpeningParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LProcessingShape Shape;
```

```
    int Size;
```

```
    LProcessingDirection Direction;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Shape指定处理形状。Size指定过滤器大小。尺寸越大，作用越强。Direction指定收缩方向。
### 闭运算(去除黑像素干扰)

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Closing(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LClosingParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Closing(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LClosingParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LClosingParam
```

```
{
```

```
    int ProcessingTimes;
```

```
    LProcessingShape Shape;
```

```
    int Size;
```

```
    LProcessingDirection Direction;
```

```
}
```
成员名称说明ProcessingTimes指定过滤器的处理次数Shape指定处理形状。Size指定过滤器大小。尺寸越大，作用越强。Direction指定膨胀方向。
### 二值化

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Binarization(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LBinarizationGrayParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Binarization(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LBinarizationGrayParam param)
```


```
xxxxxxxxxx
```

```
LErrorCode Binarization(
```

```
    this LHeightImage heightImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LBinarizationHeightParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Binarization(this LHeightImage heightImage,
```

```
    out LGrayImage filterImage,
```

```
    LBinarizationHeightParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LBinarizationGrayParam
```

```
{
```

```
    int LowerThreshold;
```

```
    int UpperThreshold;
```

```
}
```
成员名称说明LowerThreshold二值化下限值。下限值和上限值内的像素变白，其他像素变黑。UpperThreshold二值化上限值。
```
xxxxxxxxxx
```

```
struct LBinarizationHeightParam
```

```
{
```

```
    double LowerThreshold;
```

```
    double UpperThreshold;
```

```
}
```
成员名称说明LowerThreshold二值化下限值。下限值和上限值内的像素变白，其他像素变黑。UpperThreshold二值化上限值。
### 斑点过滤器

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode BlobFilter(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LBlobFilterParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode BlobFilter(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LBlobFilterParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LBlobFilterParam
```

```
{
```

```
    LBlobDetectionColor Color;
```

```
    int DetectionCount;
```

```
    bool FillHoles
```

```
    LBlobDetectFilter[] Filters;
```

```
}
```
成员名称说明Color指定是否处理白色或黑色斑点。DetectionCount指定要检测的最大斑点数。FillHoles是否使用检测颜色填充斑点内部（true：填充、false:不填充）。Filters指定斑点过滤条件。可以根据面积/圆形度/主轴长度/针状度进行排除。
```
xxxxxxxxxx
```

```
struct LBlobDefectFilter
```

```
{
```

```
    LBlobDefectFeature Feature;
```

```
    double LowerLimit;
```

```
    double UpperLimit;
```

```
}
```
成员名称说明Feature指定用于排除斑点的特征。可以指定面积/圆形度/主轴长度/针状度。LowerLimit排除指定特征值小于或等于 LowerLimit 的斑点。UpperLimit排除指定特征值大于或等于 UpperLimit 的斑点。
### 模糊处理

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode Blur(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LBlurParam param)
```
参数名输入/输入说明grayImage输入作为处理对象的亮度图像数据。filterImage输入处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode Blur(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LBlurParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LBlurParam
```

```
{
```

```
    int BlurIntensity;
```

```
    LProcessingDirection Direction;
```

```
}
```
成员名称说明BlurIntensity指定模糊程度。值越大，模糊越强Direction指定处理方向。
### 对比度转换

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode ContrastConversion(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LContrastConversionParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode ContrastConversion(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LContrastConversionParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LContrastConversionParam
```

```
{
```

```
    int Offset;
```

```
    double Span;
```

```
}
```
成员名称说明Offset增大该值将使图像整体变亮，减小该值将使图像整体变暗。Span增大该值将使对比度更强，减小该值将使对比度减弱。
### 实时浓淡补正
通过计算输入图像和根据输入图像创建的内部处理图像之间的差异，消除背景中阴影的平缓变化。
删除平缓的背景阴影，仅提取对比度变化剧烈的区域。
还可以使用区域内的平均或中值密度来均匀校正整个图像的对比度。

#### 方法定义

```


xxxxxxxxxx
```

```
LErrorCode ShadingCorrection(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition,
```

```
    LShadingCorrectionParam param)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入param输入指定过滤器的具体处理参数以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode ShadingCorrection(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    LShadingCorrectionParam param)
```

#### 参数

```
xxxxxxxxxx
```

```
struct LShadingCorrectionParam
```

```
{
```

```
    LShadingCorrectionMethod Method;
```

```
    int ExtractSize;
```

```
    LProcessingDirection Direction;
```

```
    LShadingCorrectionTone Tone;
```

```
    double BrightGain;
```

```
    double DarkGain;
```

```
    int BrightNoiseCut;
```

```
    int DarkNoiseCut;
```

```
    bool UniformContrast;
```

```
    bool UsingOutsideRegionPixels;
```

```
}
```
成员名称说明Method指定补正方法。ExtractSize指定补正方法选择阴影补正或高速阴影补正时的提取大小。
值越小，追随精细阴影变化的能力越好，但处理时间也会越长。Direction指定补正方法选择阴影补正或高速阴影补正时的处理方向。Tone选择要提取的颜色。BrightGain／DarkGain设置补正后的增益。如果想增加处理后图像的对比度，请增加此数值。BrightNoiseCut／DarkNoiseCut指定排除干扰的等级。UniformContrast如果背景中的密度变化很大并且您希望使其更加均匀，请指定 true。
还具有即使背景亮度波动也能保持滤波后图像对比度恒定的效果。UsingOutsideRegionPixels在处理区域边缘的数据时，是否参考区域外的数据进行处理（true：参考，false：不参考）。
### 黑白反转

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode BlackWhiteInversion(
```

```
    this LGrayImage grayImage,
```

```
    out LGrayImage filterImage,
```

```
    ILRegion[] regions,
```

```
    ILRegion[] maskRegions,
```

```
    LDeltaPosition deltaPosition)
```
参数名输入/输出说明grayImage输入作为处理对象的亮度图像数据。filterImage输出处理后的亮度图像数据。regions输入在grayImage中要处理的区域
如果只指定一个处理区域，也可以直接以ILRegion类型输入maskRegions输入在grayImage中，指定要从处理范围中屏蔽的区域。deltaPosition输入位置偏移信息。可选输入以如下形式调用时，整个图像均作为处理对象。

```


xxxxxxxxxx
```

```
public static LErrorCode BlackWhiteInversion(this LGrayImage grayImage,
```

```
    out LGrayImage filterImage)
```

## 振动补正
振动校正作为LVibrationCorrection类的静态方法提供，以VibrationCorrection.VibrationCorrectionX（…）形式调用时修改相应参数的值。
另外，由于作为扩展方法实现，也可以以image.VibrationCorrectionX（…）形式调用并修改相应参数的值。

### 参数

#### 补正基准设定

##### 接口

用于抽象处理振动修正中每个修正基准设定的接口定义。

```


xxxxxxxxxx
```

```
public interface ILVibrationCorrectionParam
```

```
{
```

```
}
```

##### 边缘设定

```
xxxxxxxxxx
```

```
public struct LVibrationCorrectionEdgeParam : ILVibrationCorrectionParam
```

```
{
```

```
    ILRegion Region;
```

```
    double EdgeLevel;
```

```
    LEdgeDirection EdgeDirection;
```

```
    LDetectDirection DetectDirection;
```

```
}
```
成员名称说明Region指定目标区域。只能指定矩形。EdgeLevel指定边缘的检出级别。EdgeDirection指定要检测的边缘类型（两者/高到低/低到高）。DetectDirection指定边缘的检测方向(正向／逆向)。
##### 平均化设定

```
xxxxxxxxxx
```

```
public struct LVibrationCorrectionAverageParam : ILVibrationCorrectionParam
```

```
{
```

```
    ILRegion Region;
```

```
}
```
成员名称说明Region指定目标区域。只能指定矩形。
##### 峰值设定

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionPeakParam : ILVibrationCorrectionParam
```

```
{
```

```
    ILRegion Region;
```

```
    int MovingAverageCount;
```

```
}
```
成员名称说明Region指定目标区域。只能指定矩形。MovingAverageCount指定移动平均处理次数。
##### 谷值设定

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionBottomParam : ILVibrationCorrectionParam
```

```
{
```

```
    ILRegion Region;
```

```
    int MovingAverageCount;
```

```
}
```
成员名称说明Region指定目标区域。只能指定矩形。MovingAverageCount指定移动平均处理次数。
##### 直线设定

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionLineParam : ILVibrationCorrectionParam
```

```
{
```

```
    ILRegion Region1;
```

```
    bool UseRegion2;
```

```
    ILRegion Region2;
```

```
}
```
成员名称说明Region1指定目标区域1。只能指定矩形。UseRegion1指定是否使用区域2。Region2指定目标区域2。只能指定矩形。
##### 交点设定

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionIntersectionPointParam : ILVibrationCorrectionParam
```

```
{
```

```
    LVibrationCorrectionLineParam Line1;
```

```
    LVibrationCorrectionLineParam Line2;
```

```
}
```
成员名称说明Line1指定直线1。直线设置只能指定一个区域。Line2指定直线2。直线设置只能指定一个区域。
直线设置2的区域必须与直线设置1的区域具有相同的y坐标。
### X补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode VibrationCorrectionX(
```

```
    this LHeightImage heightImage,
```

```
    LGrayImage grayImage,
```

```
    out LHeightImage filterHeightImage,
```

```
    out LGrayImage filterGrayImage,
```

```
    LVibrationCorrectionXParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。可选输入filterHeightImage输出处理后的高度图像数据。filterGrayImage输出处理后的亮度图像数据。可选输入param输入指定补正设定。
#### 参数

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionXParam
```

```
{
```

```
    ILVibrationCorrectionParam ReferenceParam1;
```

```
    bool UseReference2;
```

```
    ILVibrationCorrectionParam ReferenceParam2;
```

```
    bool XAlignment;
```

```
}
```
成员名称说明ReferenceParam1指定补正基准设定1。（边缘、峰值、谷值或交点）。UseReference2指定是否使用校正基准设定2。ReferenceParam2指定补正基准设定2。（边缘、峰值、谷值或交点）。XAlignment设定为True时，对齐X坐标，设定为False时，保持XY平面上的倾斜。
### Z补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode VibrationCorrectionZ(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LVibrationCorrectionZParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。filterImage输出处理后的高度图像数据。param输入指定补正设定。
#### 参数

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionZParam
```

```
{
```

```
    ILVibrationCorrectionParam ReferenceParam;
```

```
    bool ZAlignment;
```

```
}
```
成员名称说明ReferenceParam指定补正基准设定（平均、峰值、谷值或交点）。ZAlignment设定为True时，对齐Z坐标，设定为False时，保持YZ平面上的倾斜。
### XZ补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode VibrationCorrectionXZ(
```

```
    this LHeightImage heightImage,
```

```
    LGrayImage grayImage,
```

```
    out LHeightImage filterHeightImage,
```

```
    out LGrayImage filterGrayImage,
```

```
    LVibrationCorrectionZParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。可选输入filterHeightImage输出处理后的高度图像数据。filterGrayImage输出处理后的亮度图像数据。可选输入param输入指定补正设定。
#### 参数

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionXZParam
```

```
{
```

```
    ILVibrationCorrectionParam ReferenceParam;
```

```
    bool XAlignment;
```

```
    bool ZAlignment;
```

```
}
```
成员名称说明ReferenceParam指定补正基准设定（峰值、谷值或交点）。XAlignment设定为True时，对齐X坐标，设定为False时，保持XY平面上的倾斜。ZAlignment设定为True时，对齐Z坐标，设定为False时，保持YZ平面上的倾斜。
### θ补正

#### 方法定义

```
xxxxxxxxxx
```

```
LErrorCode VibrationCorrectionTheta(
```

```
    this LHeightImage heightImage,
```

```
    out LHeightImage filterImage,
```

```
    LVibrationCorrectionThetaParam param)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。filterImage输出处理后的高度图像数据。param输入指定补正设定。
#### 参数

```
xxxxxxxxxx
```

```
struct LVibrationCorrectionThetaParam
```

```
{
```

```
    LVibrationCorrectionLineParam Line;
```

```
    bool SetAngle;
```

```
    double Angle;
```

```


```

```
}
```
成员名称说明Line设定补正用直线。SetAngle指定为True时，可设置直线补正后的角度。Angle设置直线补正后角度。
## 图像合成
图像合成功能通过静态类LImageCombine的静态方法提供。

### 图像合成

#### 方法定义

```


xxxxxxxxxx
```

```
LErrorCode CombineImage(
```

```
    this ref LHeightImage combineImage, LHeightImage[] heightImages, LCombineImageParam[] combineParams)
```

```
LErrorCode CombineImage(
```

```
    this ref LGrayImage combineImage, LGrayImage[] grayImages, LCombineImageParam[] combineParams)
```
参数名输入/输出说明combineImage输出拼接后的高度图像/浓淡图像数据heightImages输入作为拼接处理对象的高度图像grayImages输入作为拼接处理对象的浓淡图像combineParams输入指定拼接处理的具体处理参数
拼接参数必须与拼接处理对象（heightImages／grayImages）传递的图像数量一致
#### 处理参数

```
xxxxxxxxxx
```

```
struct LCombineImageParam
```

```
{
```

```
    int OffsetX;
```

```
    int OffsetY;
```

```
    bool InverseX;
```

```
    bool InverseY;
```

```
    int TrimXEdgePixels;
```

```
}
```
成员名称说明OffsetX／OffsetY当前图像的原点（图像左上角）在拼接后坐标系中的坐标InverseX／InverseY指定拼接前是否沿X/Y方向反转图像TrimXEdgePixels拼接前裁剪图像X方向两端的像素，可以指定的范围为0~X像素数/2
当由于超出X方向测量范围输入图像两端为无效像素时使用
（通过裁剪无效数据，可以与相邻的图像无缝隙排列有效数据）
## 检测工具

### 检测工具类
各个工具以单独类形式提供(类名称：LxxxTool、xxx为工具名)。
在LxxxTool类，检测参数LxxxParam、检测结果LxxxResult在工具类实例中保留。
LxxxTool内提供如下方法，参考如下流程使用：
　设置检查参数(LxxxParam) → 更新主控基准(*)(UpdateReference) → 执行检测(Execute) → 检测结果(LxxxResult)
*：更新主控基准(UpdateReference）仅在必要时执行即可

#### 访问检测结果

作为处理结果，有多种工具间通用的结果类型。
作为检测工具返回结果的Result，继承了各个通用数据的接口。
例如，返回位置偏移信息的检测工具的Result，继承ILDeltaPosition接口

#### 执行检测(Execute)

执行检测工具的处理方法。

#### 更新主控基准(UpdateReference)

指定作为测量基准的主控图像、将该测量值作为基准值记录在检测工具实例内部。
记录的基准值用于测量当前值偏离基准值的量。
对于位置偏移的修正处理，务必执行更新主控基准。

### 高度测量

可测量设定区域的高度峰值/谷值/平均值、凹凸体积等。
设定多个区域时，除了各区域的测量之外，还可以测量“各区域峰值高度的最大值”等内容。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LHeightTool
```

```
{
```

```
    ref LHeightParam Param;
```

```
    LHeightResult Result;
```

```
    LHeightResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据referencePlane输入测量处理时的基准平面信息deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LHeightParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion[] Regions;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Regions要处理的目标区域Region要处理的目标区域、实际是Regions[0]的别名
便于仅单个区域的场合使用MaskRegions要从处理对象中排除的区域
```
xxxxxxxxxx
```

```
class LHeightResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LHeightPosition MaximumPeakHeight;
```

```
    LHeightPosition MinimumPeakHeight;
```

```
    LHeightPosition MaximumBottomHeight;
```

```
    LHeightPosition MinimumBottomHeight;
```

```
    LHeight MaximumAverageHeight;
```

```
    LHeight MinimumAverageHeight;
```

```
    double MaximumConvexVolume;
```

```
    double MinimumConvexVolume;
```

```
    double MaximumConcaveVolume;
```

```
    double MinimumConcaveVolume;
```

```
    LEachHeightResult[] EachResults;
```

```
    LHeight AverageHeight;
```

```
    LHeightPosition PeakHeight;
```

```
    LHeightPosition BottomHeight;
```

```
    double ConvexVolume;
```

```
    double ConcaveVolume;
```

```
    ILRegion[] Regions;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间MaximumPeakHeight各区域的峰值高度中的最大高度值及其坐标信息MinimumPeakHeight各区域的峰值高度中的最小高度值及其坐标信息MaximumBottomHeight各区域的谷值高度中的最大高度值及其坐标信息MinimumBottomHeight各区域的谷值高度中的最小高度值及其坐标信息MaximumAverageHeight各区域的平均高度中的最大高度值及其坐标信息MinimumAverageHeight各区域的平均高度中的最小高度值及其坐标信息MaximumConvexVolume各区域的凸体积中的最大值MinimumConvexVolume各区域的凸体积中的最小值MaximumConcaveVolume各区域的凹体积中的最大值MinimumConcaveVolume各区域的凹体积中的最小值EachResults各区域的个别检测结果AverageHeightEachResults[0].AverageHeight的别名。便于仅单个区域的场合使用PeakHeightEachResults[0].PeakHeight的别名。便于仅单个区域的场合使用BottomHeightEachResults[0].BottomHeight的别名。便于仅单个区域的场合使用ConvexVolumeEachResults[0].ConvexVolume的别名。便于仅单个区域的场合使用ConcaveVolumeEachResults[0].ConcaveVolume的别名。便于仅单个区域的场合使用Regions／Region／MaskRegions实际测量时使用的区域，反映位置补正的结果
```
xxxxxxxxxx
```

```
struct LEachHeightResult
```

```
{
```

```
    bool Enable;
```

```
    LHeightPosition PeakHeight;
```

```
    LHeightPosition BottomHeight;
```

```
    LHeight AverageHeight;
```

```
    double ConvexVolume;
```

```
    double ConcaveVolume;
```

```
}
```
成员名称说明Enable当前区域的检测结果是否有效PeakHeight当前区域的峰值高度及坐标信息BottomHeight当前区域的谷值高度及坐标信息AverageHeight当前区域的平均高度ConvexVolume当前区域的凸体积ConcaveVolume当前区域的凹体积
```
xxxxxxxxxx
```

```
struct LHeight
```

```
{
```

```
    double Height;
```

```
    double AbsoluteZ;
```

```
}
```
成员名称说明Height相对于基准面法线方向的高度(H)AbsoluteZ绝对坐标系中的高度(Z)。
```
xxxxxxxxxx
```

```
struct LHeightPosition
```

```
{
```

```
    double Height;
```

```
    LDPoint3D AbsolutePosition;
```

```
    LDPoint2D RegionRelatedPosition;
```

```
}
```
成员名称说明Height相对于基准面法线方向的高度(H)AbsolutePosition绝对坐标系中的检测点坐标(X,Y,Z)RegionRelatedPosition固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)
需要检测区域内的相对位置移动情况下可使用
### 平面度测量
测量检测区域内的平面度。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LFlatnessTool
```

```
{
```

```
    ref LFlatnessParam Param;
```

```
    LFlatnessResult Result;
```

```
    LFlatnessResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据referencePlane输入测量处理时的基准平面信息deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LFlatnessParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion[] Regions;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref bool AverageEachRegion;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Regions要处理的目标区域Region要处理的目标区域、实际是Regions[0]的别名
便于仅单个区域的场合使用MaskRegions要从处理对象中排除的区域AverageEachRegion设定为True且指定多个区域的场合时，计算各个区域的平均高度，并将平均高度的最大值、最小值差值作为平面度
可以稳定测量结果
```
xxxxxxxxxx
```

```
class LFlatnessResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    double Flatness;
```

```
    ILRegion[] Regions;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Flatness平面度结果Regions／Region／MaskRegions实际测量时使用的区域，反映位置补正的结果
### 图形搜索

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPatternMatchTool : IUpdatePatternLHeightImage>
```

```
{
```

```
    ref LPatternMatchParam Param;
```

```
    LPattern RegisteredPattern;
```

```
    LPatternMatchResult Result;
```

```
    LPatternMatchResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
使用此工具时，请在执行Execute/UpdateReference之前执行UpdatePattern（注册基准图形）方法。
执行UpdatePattern方法时，将在工具内部保存指定的图像提取出的图形信息（注册基准图形）。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LGrayImage grayImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LGrayImage grayImage)
```

```
LErrorCode UpdatePattern(LHeightImage heightImage)
```

```
LErrorCode UpdatePattern(LGrayImage grayImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据grayImage输入作为处理对象的亮度图像数据。deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPatternMatchParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion SearchRegion;
```

```
    ref ILRegion[] SearchMaskRegions;
```

```
    ref LPatternSetting PatternSetting;
```

```
    ref int DetectCount;
```

```
    ref double StartAngle;
```

```
    ref double EndAngle;
```

```
    ref LPattenMatchFitDeformationLevel FitDeformation;
```

```
    ref double ScoreThreshold;
```

```
    ref double Timeout;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等SearchRegion指定要搜索的范围SearchMaskRegions指定搜索范围时中除外的区域PatternSetting图形抽取设定。DetectCount指定要检测的目标最大个数(1～2000)StartAngle指定搜索对象的正方向倾斜上限（0°~180°）EndAngle指定搜索对象的负方向倾斜上限（180°~0°）FitDeformation指定检出的候选对象相对于基准图形有偏差时的容许程度
可以在无/弱/强中选择，容许程度越高，允许候选对象与基准图形的偏差越大ScoreThreshold指定相似度下限值(0≦设定值＜100)Timeout指定搜索时间上限(0.5～60秒)
```
xxxxxxxxxx
```

```
struct LPatternSetting
```

```
{
```

```
    ILRegion PatternRegion;
```

```
    ILRegion[] PatternMaskRegions;
```

```
    bool EnableMaskMap;
```

```
    LMaskMapImage MaskMapImage;
```

```
}
```
成员名称说明PatternRegion指定提取图形的区域PatternMaskRegions指定提取图形时除外的区域EnableMaskMap设定为True时、则使用屏蔽图像对图形抽取时检测出的边进行屏蔽MaskMapImage指定要屏蔽检测到的边的位置。仅当EnableMaskMap为True时有效
```
xxxxxxxxxx
```

```
class LPattern
```

```
{
```

```
    bool Enable;
```

```
    LDPoint2D AbsolutePosition;
```

```
    LEdgeImage EdgeFine;
```

```
    LEdgeImage EdgeCoarse;
```

```
}
```
成员名称说明Enable作为图形信息是否有效AbsolutePosition检测到的图形的绝对坐标（图形区域的中心坐标）EdgeFine／EdgeCoarse检测到的图形的边缘信息
```
xxxxxxxxxx
```

```
struct LEdgeImage
```

```
{
```

```
    byte[] Source;
```

```
    int XSize;
```

```
    int YSize;
```

```
}
```
成员名称说明Source检测到的边缘位置以图像形式表示时的数据。
检测到边缘的位置为1，未检测到边缘的位置为0XSize／YSize边缘图像的X/Y像素数
边缘图像会根据处理对象图像尺寸进行细化
```
xxxxxxxxxx
```

```
class LPatternMatchResult : LBaseResult, ILDeltaPosition
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDeltaPosition DeltaPosition;
```

```
    int DetectCount;
```

```
    LEachPatternMatchResult[] EachResults;
```

```
    double Score;
```

```
    LPositionAngle AbsolutePosition;
```

```
    LPositionAngle RegionRelatedPosition;
```

```
    ILRegion SearchRegion;
```

```
    ILRegion[] SearchMaskRegions;
```

```
    LEdgeImage PatternEdgeFine;
```

```
    LEdgeImage PatternEdgeCoarse;
```

```
    LEdgeImage DetectedEdgeFine;
```

```
    LEdgeImage DetectedEdgeCoarse;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DeltaPosition位置偏移信息DetectCount实际检测的对象个数EachResults各检出对象的检测结果。按照相似度由高到低存储每个检测到的对象的结果。ScoreEachResults[0].Score的别名。便于只检测1个检测对象的场合使用。AbsolutePositionEachResults[0].AbsolutePosition的别名。便于只检测1个检测对象的场合使用。RegionRelatedPositionEachResults[0].RegionRelatedPosition的别名。便于只检测1个检测对象的场合使用SearchRegion／SearchMaskRegions实际测量时使用的区域，反映位置补正的结果。PatternEdgeFine／PatternEdgeCaruse相似度最高的匹配对象的图形边缘信息。DetectedEdgeFine／DetectedEdgeCaruse在搜索区域中检测到的边缘信息。
```
xxxxxxxxxx
```

```
struct LEachPatternMatchResult
```

```
{
```

```
    double Score;
```

```
    LPositionAngle AbsolutePosition;
```

```
    LPositionAngle RegionRelatedPosition;
```

```
}
```
成员名称说明Score相似度AbsolutePosition绝对坐标系中的检出位置RegionRelatedPosition固定搜索区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)。
需要检测区域内的相对位置移动情况下可使用。
```
xxxxxxxxxx
```

```
struct LPositionAngle
```

```
{
```

```
    LDPoint2D CenterPosition;
```

```
    LDPoint2D GravityPosition;
```

```
    double Angle;
```

```
}
```
成员名称说明CenterPosition绝对坐标系中的检出位置坐标(X,Y)
将基准图形匹配到检测对象时图形区域中心坐标作为检出位置时的坐标。GravityPosition绝对坐标系中的检出位置坐标(X,Y)
将将基准图形匹配到检测对象时的图形边缘点集重心位置作为检出位置时的坐标。Angle检出的基准图形旋转角度
### 形状范围

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LShapeRegionTool
```

```
{
```

```
    ref LShapeRegionParam Param;
```

```
    LShapeRegionResult Result;
```

```
    LShapeRegionResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

Execute 方法的行为根据参数而变化。
如果 binarizedImage 作为参数传递，则为该图像生成一个形状区域并将其存储在 Result 中。
如果省略 binarizedImage，ReferenceResult 中的形状范围将被位置补正并存储在 Result 中。
如果位置偏差信息也被省略，则ReferenceResult中的形状范围将被存储在Result中，而不进行位置补正。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LGrayImage binarizedImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LGrayImage binarizedImage)
```
参数名输入/输出说明binarizedImage输入作为处理对象的二值化图像数据。可选输入deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LShapeRegionParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region要处理的目标区域MaskRegions指定要从处理范围中屏蔽的区域
```
xxxxxxxxxx
```

```
class LShapeRegionResult : LBaseResult, ILReferableRegion
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LReferableRegion ReferableRegion;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间ReferableRegion生成的形状范围Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。
### 瑕疵

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDefectTool
```

```
{
```

```
    ref LDefectParam Param;
```

```
    LDefectResult Result;
```

```
    LDefectResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
使用GetDefectImage，可以获得强调了备选瑕疵凹凸情况的图像。
所有方法都以Param中设置的参数进行测量处理。

形状范围工具生成的参照区域也可以传递给每个方法。
如果传递了参照区域，则将使用参照区域作为要处理对象区域，而不是 Param 中设置的 Region。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LHeightImage heightImage, LReferableRegion referenceRegion)
```

```


```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LReferableRegion referenceRegion)
```

```


```

```
LErrorCode GetDefectImage(LHeightImage heightImage, LDeltaPosition deltaPosition, out LHeightImage defectImage)
```

```
LErrorCode GetDefectImage(LHeightImage heightImage, LReferableRegion referenceRegion, out LHeightImage defectImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。deltaPosition输入位置偏移信息。可选输入referenceRegion输入使用此参照区域检测作为检测范围而非Param中设置的区域。defectImage输出包含了将瑕疵的凹凸信息强调后的瑕疵图像数据。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDefectParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LDefectTarget Target;
```

```
    ref double DetectThreshold;
```

```
    ref int DetectCount;
```

```
    ref LDefectFilter[] Filters;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。MaskRegions指定要从检测区域中排除的区域。Target选择要检出的瑕疵对象（两者/凹/凸）。DetectThreshold以绝对值指定瑕疵检测的阈值（Z）。DetectCount指定允许检出的最大瑕疵个数(1～9999)。Filters为了只检出希望查找到的瑕疵，对检出的瑕疵进行过滤。
可根据瑕疵的面积、高度的最大值/最小值/平均值、外接矩形长边、针状度、圆形度等信息进行过滤。
```
xxxxxxxxxx
```

```
struct LDefectFilter
```

```
{
```

```
    LDefectFeature Feature;
```

```
    double LowerLimit;
```

```
    double UpperLimit;
```

```
}
```
成员名称说明Feature指定用于缩小的特征。可指定瑕疵的面积、高度的最大值/最小值/平均值、外接矩形长边、针状度、圆形度。LowerLimit指定特征量低于下限值（LowerLimit）的瑕疵不会作为瑕疵被检出。UpperLimit指定特征量高于上限值（LowerLimit）的瑕疵不会作为瑕疵被检出。
```
xxxxxxxxxx
```

```
class LDefectResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    int DetectCount;
```

```
    double TotalArea;
```

```
    double MaximumConvexAbsoluteHeight;
```

```
    double MaximumConcaveAbsoluteHeight;
```

```
    LEachDefectResult[] EachResults;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectCount检出的瑕疵个数。TotalArea检出的瑕疵总面积。MaximumConvexAbsoluteHeight检出的凸瑕疵最大高度(绝对值)。MaximumConcaveAbsoluteHeight检出的凸瑕疵最大深度(绝对值)。LEachDefectResult检出的各个瑕疵的详细信息。Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。
```
xxxxxxxxxx
```

```
struct LEachDefectResult
```

```
{
```

```
    LDPoint2D Position;
```

```
    LDPoint2D RegionRelatedPosition;
```

```
    LDefectHeightPosition MaximumHeight;
```

```
    LDefectHeightPosition MinimumHeight;
```

```
    double AverageHeight;
```

```
    double Area;
```

```
    LRotatedRectangle BoundingBox;
```

```
    LRotatedRectangle RegionRelatedBoundingBox;
```

```
    double AxisRatio;
```

```
    double Roundness;
```

```
}
```
成员名称说明Position各瑕疵的位置。使用瑕疵的重心（X/Y)。RegionRelatedPosition各瑕疵的相对位置。使用瑕疵的重心（X/Y)。
固定区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y。
需要检测区域内的相对位置移动情况下可使用。MaximumHeight各瑕疵高度的最大值的位置坐标及瑕疵高度(X,Y)。MinimumHeight各瑕疵高度的最小值的位置坐标及瑕疵高度(X,Y)。AverageHeight各瑕疵高度的平均值。Area各瑕疵的面积。BoundingBox各瑕疵的外接矩形（绝对坐标）。RegionRelatedBoundingBox各瑕疵的外接矩形（相对坐标）。
固定区域的坐标，对图像进行位置偏移修正而得到的矩形位置。
需要检测区域内的相对位置移动情况下可使用。AxisRatio各瑕疵的针状度。Roundness各瑕疵的圆形度。
```
xxxxxxxxxx
```

```
struct LDefectHeightPosition
```

```
{
```

```
    double Height;
```

```
    LDPoint2D AbsolutePosition;
```

```
    LDPoint2D RegionRelatedPosition;
```

```
}
```
成员名称说明Height瑕疵的高度。AbsolutePosition检出位置在在绝对坐标系中的坐标(X,Y)。RegionRelatedPosition固定区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标（X/Y）。
需要检测区域内的相对位置移动情况下可使用。
### 细微瑕疵

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LFineDefectTool
```

```
{
```

```
    ref LFineDefectParam Param;
```

```
    LFineDefectResult Result;
```

```
    LFineDefectResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
使用GetDefectImage，可以获得强调了备选瑕疵凹凸情况的图像。
所有方法都以Param中设置的参数进行测量处理。

形状范围工具生成的参照区域也可以传递给每个方法。
如果传递了参照区域，则将使用参照区域作为要处理对象区域，而不是 Param 中设置的 Region。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LHeightImage heightImage, LReferableRegion referenceRegion)
```

```
LErrorCode Execute(LGrayImage grayImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LGrayImage grayImage, LReferableRegion referenceRegion)
```

```


```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LReferableRegion referenceRegion)
```

```
LErrorCode UpdateReference(LGrayImage grayImage)
```

```
LErrorCode UpdateReference(LGrayImage grayImage, LReferableRegion referenceRegion)
```

```


```

```
LErrorCode GetDefectImage(LHeightImage heightImage, LDeltaPosition deltaPosition, LHeightImage out defectImage)
```

```
LErrorCode GetDefectImage(LHeightImage heightImage, LReferableRegion referenceRegion, out LHeightImage defectImage)
```

```
LErrorCode GetDefectImage(LGrayImage grayImage, LDeltaPosition deltaPosition, LHeightImage out defectImage)
```

```
LErrorCode GetDefectImage(LGrayImage grayImage, LReferableRegion referenceRegion, out LHeightImage defectImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。deltaPosition输入位置偏移信息。可选输入referenceRegion输入使用此参照区域检测作为检测范围而非Param中设置的区域。defectImage输出包含了将瑕疵的凹凸信息强调后的瑕疵图像数据。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LFineDefectParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LFineDefectDirection DetectDirection;
```

```
    int SegmentSizeX;
```

```
    int SegmentSizeY;
```

```
    int MinimumDefectLevel;
```

```
    double Sensitivity;
```

```
    int DetectCount;
```

```
    int MinimumDefectArea;
```

```
    bool FillHoles;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。MaskRegions指定要从检测区域中排除的区域。DetectDirection指定检测区域内扫描时的方向(XY/X/Y)。SegmentSizeX指定检测区域内扫描时X方向的扫描间隔。SegmentSizeY指定检测区域内扫描时Y方向的扫描间隔。MinimumDefectLevel指定要检出的瑕疵的最低瑕疵等级。Sensitivity指定检测灵敏度。DetectCount指定允许检出的最大瑕疵个数(1～9999)。MinimumDefectArea指定要检出的瑕疵的最低瑕疵量。FillHoles指定为True时，对中空类型的瑕疵的内部进行填充处理。
```
xxxxxxxxxx
```

```
class LFineDefectResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    int DetectCount;
```

```
    int TotalDefectArea;
```

```
    int MaximumDefectLevel;
```

```
    LEachFineDefectResult[] EachResults;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectCount检出的瑕疵个数。TotalDefectArea检出的总瑕疵量。MaximumDefectLevel检出的最大瑕疵等级。LEachFineDefectResult检出的各瑕疵的详细信息。Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。
```
xxxxxxxxxx
```

```
struct LEachFineDefectResult
```

```
{
```

```
    LDPoint2D Position;
```

```
    LDPoint2D RegionRelatedPosition;
```

```
    int DefectArea;
```

```
    LDefectLevelPosition MaximumDefectLevel;
```

```
    LDefectLevelPosition MinimumDefectLevel;
```

```
    int AverageDefectLevel;
```

```
    LRotatedRectangle BoundingBox;
```

```
    LRotatedRectangle RegionRelatedBoundingBox;
```

```
}
```
成员名称说明Position各瑕疵的位置。使用瑕疵的重心（X/Y)。RegionRelatedPosition各瑕疵的相对位置。使用瑕疵的重心（X/Y)。
固定区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y。
需要检测区域内的相对位置移动情况下可使用。DefectArea各瑕疵的瑕疵量。MaximumDefectLevel各瑕疵的等级最大值及位置坐标(X,Y)。MinimumDefectLevel各瑕疵的等级最小值及位置坐标(X,Y)。AverageDefectLevel各瑕疵的等级平均值。BoundingBox各瑕疵的外接矩形（绝对坐标系）。RegionRelatedBoundingBox各瑕疵的外接矩形(相对坐标）。
固定区域的坐标，对图像进行位置偏移修正而得到的矩形位置。
需要检测区域内的相对位置移动情况下可使用。
```
xxxxxxxxxx
```

```
struct LDefectLevelPosition
```

```
{
```

```
    int DefectLevel;
```

```
    LDPoint2D AbsolutePosition;
```

```
    LDPoint2D RegionRelatedPosition;
```

```
}
```
成员名称说明DefectLevel瑕疵等级。AbsolutePosition检出位置在绝对坐标系中的坐标(X,Y)。RegionRelatedPosition固定区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标（X/Y）。
需要检测区域内的相对位置移动情况下可使用。
### 平面检测

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPlaneTool
```

```
{
```

```
    ref LPlaneParam Param;
```

```
    LPlaneResult Result;
```

```
    LPlaneResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPlaneParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion[] Regions;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LPlaneMethod Method;
```

```
    ref LPlaneTargetData TargetData;
```

```
    ref double OffsetZ;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Regions要处理的目标区域Region要处理的目标区域、实际是Regions[0]的别名
便于仅单个区域的场合使用MaskRegions要从处理对象中排除的区域Method指定平面检测的计算方法，仅支持最小二乘法TargetData从“从所有区域中取样/使用所有区域的全部数据/使用每个区域的平均高度”中选择用于平面检测的数据的提取方法OffsetZ将检测到的平面沿绝对坐标系Z方向偏移指定的距离（单位：mm）
```
xxxxxxxxxx
```

```
class LPlaneResult : LBaseResult, ILPlaneResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LPlane Plane;
```

```
    ILRegion[] Regions;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Plane检测到的平面信息Regions／Region／MaskRegions实际测量时使用的区域，反映位置补正的结果
### 点检测

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPointTool
```

```
{
```

```
    ref LPointParam Param;
```

```
    LPointResult  Result;
```

```
    LPointResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LGrayImage grayImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LGrayImage grayImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPointParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LDetectDirection DetectDirection;
```

```
    ref LEdgeDirection EdgeDirection;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。可指定直线或旋转矩形。MaskRegions指定要从检测区域中排除的区域。DetectDirection指定边缘检测的检测方向(正方向／逆方向)。EdgeDirection指定要检测的边缘的类型(两者／高→低／低→高)。
```
xxxxxxxxxx
```

```
class LPointResult : LBaseResult, ILDetectPoint2D, ILDeltaPosition
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectPoint2D DetectPoint;
```

```
    LDeltaPosition DeltaPosition;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectPoint检测到的点。DeltaPosition位置偏移信息。Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。
### 直线检测

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LLineTool
```

```
{
```

```
    ref LLineParam Param;
```

```
    LLineResult  Result;
```

```
    LLineResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LGrayImage grayImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LGrayImage grayImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LLineParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LDetectDirection DetectDirection;
```

```
    ref LEdgeDirection EdgeDirection;
```

```
    ref bool RemoveNoise;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。只能使用旋转矩形。MaskRegions指定要从检测区域中排除的区域。DetectDirection指定边缘检测的检测方向(正方向／逆方向)。EdgeDirection指定要检测的边缘的类型(两者／高→低／低→高)。RemoveNoise检测边缘时剔除异常点以减少影响。
```
xxxxxxxxxx
```

```
class LLineResult : LBaseResult, ILDetectLine2D, ILDeltaPosition
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectLine2D DetectLine;
```

```
    LDeltaPosition DeltaPosition;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
    LDPoint2D[] EdgePoints;
```

```
    LDPoint2D[] NoisePoints;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectLine检出的直线。DeltaPosition位置偏移信息。Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。EdgePoints检出的边缘点的集合NoisePoints检出但被异常处理排除在外的边缘点的集合
### 圆检测

#### 类定义
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LCircleTool
```

```
{
```

```
    ref LCircleParam Param;
```

```
    LCircleResult  Result;
```

```
    LCircleResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LDeltaPosition deltaPosition)
```

```
LErrorCode Execute(LGrayImage grayImage, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage)
```

```
LErrorCode UpdateReference(LGrayImage grayImage)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LCircleParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LCircleDetectDirection DetectDirection;
```

```
    ref LEdgeDirection EdgeDirection;
```

```
    ref bool RemoveNoise;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。仅支持圆环和圆弧。MaskRegions指定要从检测区域中排除的区域。DetectDirection指定边缘检测的检测方向(正方向／逆方向)。EdgeDirection指定要检测的边缘的类型(两者／高→低／低→高)。RemoveNoise检测边缘时剔除异常点以减少影响。
```
xxxxxxxxxx
```

```
class LCircleResult : LBaseResult, ILDetectCircle2D, ILDeltaPosition
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LDetectCircle2D DetectCircle;
```

```
    LDetectPoint2D DetectPoint;
```

```
    LDeltaPosition DeltaPosition;
```

```
    ILRegion Region;
```

```
    ILRegion[] MaskRegions;
```

```
    LDPoint2D[] EdgePoints;
```

```
    LDPoint2D[] NoisePoints;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectCircle检出的圆。DetectPoint检出的圆的中心点。DeltaPosition位置偏移信息。Region／MaskRegions实际测量时使用的区域，反映位置补正的结果。EdgePoints检出的边缘点的集合NoisePoints检出但被异常处理排除在外的边缘点的集合
### 直线间的中心线
计算直线之间的中心线。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LLineMedianTool
```

```
{
```

```
    ref LLineMedianParam Param;
```

```
    LLineMedianResult  Result;
```

```
    LLineMedianResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line1, LDetectLine2D line2)
```

```
LErrorCode UpdateReference(LDetectLine2D line1, LDetectLine2D line2)
```
参数名输入/输出说明line1输入作为处理对象的直线元素1。line2输入作为处理对象的直线元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LLineMedianParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LDetectDirection DetectDirection;
```

```
    ref LDetectOrientation DetectOrientation;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等DetectDirection指定中线的检测方向（正向/反向）。DetectOrientation指定中心线检测标准（水平基准/垂直基准）。
```
xxxxxxxxxx
```

```
class LLineMedianResult : LBaseResult, ILDetectLine2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectLine2D DetectLine;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectLine检测到的直线。
### 经过两点的直线
可以计算经过两点的直线。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LLineThroughPointsTool
```

```
{
```

```
    ref LLineThroughPointsParam Param;
```

```
    LLineThroughPointsResult  Result;
```

```
    LLineThroughPointsResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectPoint2D point1, LDetectPoint2D point2)
```

```
LErrorCode UpdateReference(LDetectPoint2D point1, LDetectPoint2D point2)
```
参数名输入/输出说明point1输入作为处理对象的检测点元素1。point2输入作为处理对象的检测点元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LLineThroughPointsParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等
```
xxxxxxxxxx
```

```
class LLineThroughPointsResult : LBaseResult, ILDetectLine2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectLine2D DetectLine;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectLine检出的直线
### 直线间的交点
计算直线与直线的交点。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPointIntersectionTool
```

```
{
```

```
    ref LPointIntersectionParam Param;
```

```
    LPointIntersectionResult  Result;
```

```
    LPointIntersectionResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line1, LDetectLine2D line2)
```

```
LErrorCode UpdateReference(LDetectLine2D line1, LDetectLine2D line2)
```
参数名输入/输出说明line1输入作为处理对象的直线元素1。line2输入作为处理对象的直线元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPointIntersectionParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等
```
xxxxxxxxxx
```

```
class LPointIntersectionResult : LBaseResult, ILDetectPoint2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectPoint2D DetectPoint;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectPoint检出的点
### 点和点的中点
可计算两点的中点。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPointMiddleTool
```

```
{
```

```
    ref LPointMiddleParam Param;
```

```
    LPointMiddleResult  Result;
```

```
    LPointMiddleResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectPoint2D point1, LDetectPoint2D point2)
```

```
LErrorCode UpdateReference(LDetectPoint2D point1, LDetectPoint2D point2)
```
参数名输入/输出说明point1输入作为处理对象的检测点元素1。point2输入作为处理对象的检测点元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPointMiddleParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等
```
xxxxxxxxxx
```

```
class LPointMiddleResult : LBaseResult, ILDetectPoint2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LDetectPoint2D DetectPoint;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间DetectPoint检出的点
### 线与线的距离测量
可以测量线与线之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistanceLineLineTool
```

```
{
```

```
    ref LDistanceLineLineParam Param;
```

```
    LDistanceLineLineResult  Result;
```

```
    LDistanceLineLineResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line1, LDetectLine2D line2)
```

```
LErrorCode UpdateReference(LDetectLine2D line1, LDetectLine2D line2)
```
参数名输入/输出说明line1输入作为处理对象的直线元素1。line2输入作为处理对象的直线元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistanceLineLineParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。
```
xxxxxxxxxx
```

```
class LDistanceLineLineResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LMeasuredDistance Distance;
```

```
    LMeasuredDistance MinimumDistance;
```

```
    LMeasuredDistance MaximumDistance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。MinimumDistance最短距离。MaximumDistance最长距离。
### 线与点的距离测量
可以测量线与点之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistanceLinePointTool
```

```
{
```

```
    ref LDistanceLinePointParam Param;
```

```
    LDistanceLinePointResult  Result;
```

```
    LDistanceLinePointResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line, LDetectPoint2D point)
```

```
LErrorCode UpdateReference(LDetectLine2D line, LDetectPoint2D point)
```
参数名输入/输出说明line输入作为处理对象的直线元素。point输入作为处理对象的点元素。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistanceLinePointParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。
```
xxxxxxxxxx
```

```
class LDistanceLinePointResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LMeasuredDistance Distance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。
### 线与圆的距离测量
可以测量线与圆之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistanceLineCircleTool
```

```
{
```

```
    ref LDistanceLineCircleParam Param;
```

```
    LDistanceLineCircleResult  Result;
```

```
    LDistanceLineCircleResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line, LDetectCircle2D circle)
```

```
LErrorCode UpdateReference(LDetectLine2D line, LDetectCircle2D circle)
```
参数名输入/输出说明line输入作为处理对象的直线元素。circle输入作为处理对象的圆元素。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistanceLineCircleParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
    ref LMeasurementPattern MeasurementPattern;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。MeasurementPattern从“中心、最大、最小”中选择距离测量对象。
```
xxxxxxxxxx
```

```
class LDistanceLineCircleResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LMeasuredDistance Distance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。
### 点与点的距离测量
可以测量点与点之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistancePointPointTool
```

```
{
```

```
    ref LDistancePointPointParam Param;
```

```
    LDistancePointPointResult  Result;
```

```
    LDistancePointPointResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectPoint2D point1, LDetectPoint2D point2, LDetectLine2D baseLine)
```

```
LErrorCode UpdateReference(LDetectPoint2D point1, LDetectPoint2D point2, LDetectLine2D baseLine)
```
参数名输入/输出说明point1输入作为处理对象的点元素1。point2输入作为处理对象的点元素2。baseLine输入测量距离时的基准检测线。以X轴为基准时可选择输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistancePointPointParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。
```
xxxxxxxxxx
```

```
class LDistancePointPointResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LMeasuredDistance Distance;
```

```
    LMeasuredDistance BaseHorizontalDistance;
```

```
    LMeasuredDistance BaseVerticalDistance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。BaseHorizontalDistance与基准平行的测量距离。BaseVerticalDistance与基准垂直的测量距离。
### 点与圆的距离测量
可以测量点与圆之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistancePointCircleTool
```

```
{
```

```
    ref LDistancePointCircleParam Param;
```

```
    LDistancePointCircleResult  Result;
```

```
    LDistancePointCircleResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectPoint2D point, LDetectCircle2D circle, LDetectLine2D baseLine)
```

```
LErrorCode UpdateReference(LDetectPoint2D point, LDetectCircle2D circle, LDetectLine2D baseLine)
```
参数名输入/输出说明point输入作为处理对象的点元素。circle输入作为处理对象的圆元素。baseLine输入测量距离时的基准检测线。以X轴为基准时可选择输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistancePointCircleParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
    ref LMeasurementPattern MeasurementPattern;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。MeasurementPattern从“中心、最大、最小”中选择距离测量对象。
```
xxxxxxxxxx
```

```
class LDistancePointCircleResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LMeasuredDistance Distance;
```

```
    LMeasuredDistance BaseHorizontalDistance;
```

```
    LMeasuredDistance BaseVerticalDistance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。BaseHorizontalDistance与基准平行的测量距离。BaseVerticalDistance与基准垂直的测量距离。
### 圆与圆的距离测量
可以测量圆与圆之间的距离。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LDistanceCircleCircleTool
```

```
{
```

```
    ref LDistanceCircleCircleParam Param;
```

```
    LDistanceCircleCircleResult  Result;
```

```
    LDistanceCircleCircleResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectCircle2D circle1, LDetectCircle2D circle2, LDetectLine2D baseLine)
```

```
LErrorCode UpdateReference(LDetectCircle2D circle1, LDetectCircle2D circle2, LDetectLine2D baseLine)
```
参数名输入/输出说明circle1输入作为处理对象的圆元素1。circle2输入作为处理对象的圆元素2。baseLine输入测量距离时的基准检测线。以X轴为基准时可选择输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LDistanceCircleCircleParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LMeasuredValue MeasuredValue;
```

```
    ref LMeasurementPattern MeasurementPattern;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasuredValue选择要输出的距离值类型（绝对值、正方向、反方向）。MeasurementPattern从“中心、最大、最小”中选择距离测量对象。
```
xxxxxxxxxx
```

```
class LDistanceCircleCircleResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LMeasuredDistance Distance;
```

```
    LMeasuredDistance BaseHorizontalDistance;
```

```
    LMeasuredDistance BaseVerticalDistance;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Distance直线距离。BaseHorizontalDistance与基准平行的测量距离。BaseVerticalDistance与基准垂直的测量距离。
### 线与线的角度测量
可以测量线与线之间的角度。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LAngleLineLineTool
```

```
{
```

```
    ref LAngleLineLineParam Param;
```

```
    LAngleLineLineResult  Result;
```

```
    LAngleLineLineResult  ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LDetectLine2D line1, LDetectLine2D line2)
```

```
LErrorCode UpdateReference(LDetectLine2D line1, LDetectLine2D line2)
```
参数名输入/输出说明line1输入作为处理对象的直线元素1。line2输入作为处理对象的直线元素2。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LAngleLineLineParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LAngleMeasurementPattern MeasurementPattern;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等MeasurementPattern从“角度1/角度2/补角1/补角2”中选择角度测量的方式。
```
xxxxxxxxxx
```

```
class LAngleLineLineResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LMeasuredAngle Angle;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Angle测出的角度。
## 截面测量相关工具

### 截面提取

##### 接口
以抽象方式处理提取截面的过滤设置的接口定义。

```


xxxxxxxxxx
```

```
public interface ILProfileFilterParam
```

```
{
```

```
}
```

##### 平滑过滤器参数

```
xxxxxxxxxx
```

```
public struct LProfileSmoothingFilterParam : ILProfileFilterParam
```

```
{
```

```
    bool ShapeRetention;
```

```
    int SmoothingSize;
```

```
}
```
成员名称说明ShapeRetention此设置确定是否保持提取的截面的形状。SmoothingSize指定平滑大小（1 到 127 之间的奇数）。
##### 中间值过滤器参数

```
xxxxxxxxxx
```

```
public struct LProfileMedianFilterParam : ILProfileFilterParam
```

```
{
```

```
    int MedianSize;
```

```
}
```
成员名称说明MedianSize指定中间值的大小（1 到 127 之间的奇数）。
#### 截面提取
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LProfileTool
```

```
{
```

```
    ref LProfileParam Param;
```

```
    LProfileResult Result;
```

```
    LProfileResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。可选输入。referencePlane输入截面轮廓数据提取处理时使用的基准平面信息。deltaPosition输入位置偏移信息。可选输入
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LProfileParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref LExtractProfileSetting ExtractProfileSetting;
```

```
    ref ILProfileFilterParam[] ProfileFilterParams;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。只能指定直线区域。ExtractProfileSetting截面轮廓提取相关的设定。ProfileFilterParams提取截面数据后执行的过滤器设置。
```
xxxxxxxxxx
```

```
public struct LExtractProfileSetting
```

```
{
```

```
    double Width;
```

```
    LExtractProfileMethod Method;
```

```
}
```
成员名称说明Width指定提取截面时“Method”指定的处理方法对应的处理对象范围。Method指定截面提取时的方法（平均值/最大值或最小值）
```
xxxxxxxxxx
```

```
class LProfileResult : LBaseResult, ILProfileResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LProfile[] Profiles;
```

```
    ILRegion Region;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Profile提取到的截面轮廓。Region截面轮廓提取时实际使用的区域。反映位置补正后的结果。
#### 连续截面提取
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LAlignedMultiProfileTool
```

```
{
```

```
    ref LAlignedMultiProfileParam Param;
```

```
    LAlignedMultiProfileResult Result;
```

```
    LAlignedMultiProfileResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。可选输入。referencePlane输入截面轮廓数据提取处理时使用的基准平面信息。deltaPosition输入位置偏移信息。可选输入
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LAlignedMultiProfileParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion Region;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref double StartAngle;
```

```
    ref double EndAngle;
```

```
    ref double Pitch;
```

```
    ref LExtractProfileSetting ExtractProfileSetting;
```

```
    ref ILProfileFilterParam[] ProfileFilterParams;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Region指定要处理的目标区域。可以指定旋转矩形或圆。MaskRegions指定要从检测区域中排除的区域。StartAngle/EndAngle指定要提取截面轮廓的范围（单位为“°”）。仅当区域为圆时有效。Pitch指定提取截面时间隔。
单位:Region为旋转矩形时为“mm”，圆时为“°”。ExtractProfileSetting截面轮廓提取相关的设定。
Width的单位:Region为旋转矩形时为“mm”，圆时为“°”。ProfileFilterParams提取截面数据后执行的过滤器设置。
```
xxxxxxxxxx
```

```
class LAlignedMultiProfileResult : LBaseResult, ILProfileResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LProfile[] Profiles;
```

```
    ILRegion Region;
```

```
    ILRegion[] EachRegion;
```

```
}
```

```
※ 单截面提取／复数截面提取使用同样的接口(ILProfileResult)
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Profiles提取到的截面轮廓。Region用于截面提取的区域。反映位置补正后的结果。EachRegion用于最终提取每个截面的区域。反映位置补正后的结果。
#### 连续截面提取(自由)
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LMultiProfileTool
```

```
{
```

```
    ref LMultiProfileParam Param;
```

```
    LMultiProfileResult Result;
```

```
    LMultiProfileResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LGrayImage grayImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。grayImage输入作为处理对象的亮度图像数据。可选输入。referencePlane输入截面轮廓数据提取处理时使用的基准平面信息。deltaPosition输入位置偏移信息。可选输入
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LMultiProfileParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion[] Regions;
```

```
    ref ILRegion[] MaskRegions;
```

```
    ref LExtractProfileSetting ExtractProfileSetting;
```

```
    ref ILProfileFilterParam[] ProfileFilterParams;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Regions指定要处理的目标区域。只能指定直线。MaskRegions指定要从检测区域中排除的区域。由于此工具暂不支持，将忽略屏蔽设定。ExtractProfileSetting截面轮廓提取相关的设定。ProfileFilterParams提取截面数据后执行的过滤器设置。
```
xxxxxxxxxx
```

```
class LMultiProfileResult : LBaseResult, ILProfileResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LProfile[] Profiles;
```

```
    ILRegion[] Regions;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间Profiles提取到的截面轮廓。Regions用于最终提取每个截面的区域。反映位置补正后的结果。
### 截面测量

#### 参数

##### 直线/圆检测设定

```
xxxxxxxxxx
```

```
public struct LProfileDetectLineCircleParam
```

```
{
```

```
    public LProfileRange Range;
```

```
    bool SpecifyMultipleRanges;
```

```
    public LProfileRange Range2;
```

```
    bool ReduceNoizeInfluence;
```

```
}
```

##### 测量对象设定

###### 接口
用于抽象处理截面测量的每个测量对象的详细设定的接口定义。

```


xxxxxxxxxx
```

```
public interface ILProfileMeasurementTargetParam
```

```
{
```

```
}
```

###### 峰值设定

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetPeakParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileRange Range;
```

```
}
```

###### 谷值设定

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetBottomParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileRange Range;
```

```
}
```

###### 平均设定

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetAverageParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileRange Range;
```

```
}
```

###### 边缘设定

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetEdgeParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileRange Range;
```

```
    public double DetectionLevel;
```

```
    public LProfileEdgeDirection EdgeDirection;
```

```
    public LProfileDetectDirection DetectDirection;
```

```
}
```

###### 拐点设定

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetChangePointParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileRange Range;
```

```
    public double DetectionLevel;
```

```
    public LProfileEdgeDirection EdgeDirection;
```

```
    public LProfileDetectDirection DetectDirection;
```

```
    public LProfileDetectLineCircleType ReferenceType;
```

```
    public LProfileDetectLineCircleParam ReferenceLineCircleParam;
```

```
    public int FilterSize;
```

```
}
```

###### 交点设置

```
xxxxxxxxxx
```

```
public struct LProfileMeasurementTargetCrossPointParam : ILProfileMeasurementTargetParam
```

```
{
```

```
    public LProfileDetectLineCircleParam ReferenceLineCircleParam1;
```

```
    public LProfileDetectLineCircleParam ReferenceLineCircleParam2;
```

```
}
```

#### 截面高度测量
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LProfileHeightTool
```

```
{
```

```
    ref LProfileHeightParam Param;
```

```
    LProfileHeightResult Result;
```

```
    LProfileHeightResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LProfile profiles[])
```

```
LErrorCode UpdateReference(LProfile profiles[])
```
参数名输入/输出说明profiles输入作为处理对象的截面轮廓数据。
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LProfileHeightParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILProfileMeasurementTargetParam TargetParam;
```

```
    ref bool UseReferenceLine;
```

```
    ref LProfileDetectLineCircleParam ReferenceLineParam;
```

```
    ref LDetectEdgeType DetectEdgeType
```

```
    ref bool RemoveNoise;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等TargetParam测量高度对象时的检测设定。UseReferenceLine设置是否使用测量基准线（此工具暂不支持基准线，必须指定 false）。ReferenceLineParam检测测量基准线的检测设定。DetectEdgeType指定根据各轮廓的检出点进行拟合的目标形状类型（无/直线/圆）。RemoveNoise形状拟合时剔除异常点以避免影响。
```
xxxxxxxxxx
```

```
class LProfileHeightResult : LBaseResult, ILDetectLine2D, ILDetectCircle2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    double AverageHeight;
```

```
    LProfileHeight MaximumHeight;
```

```
    LProfileHeight MinimumHeight;
```

```
    LEachProfileHeightResult[] EachResults;
```

```
    LProfileHeight Height;
```

```
    LDetectLine2D DetectLine;
```

```
    LDetectCircle2D DetectCircle;
```

```
    LDetectPoint2D DetectPoint;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间AverageHeight各区域的高度值平均值。(EachResults[].ProfileHeight.Heightの平均値)MaximumHeight各区域的高度值中的最大值及其坐标信息。(通过比较EachResults[].ProfileHeight.Height获得)MinimumHeight各区域的高度值中的最小值及其坐标信息。(通过比较EachResults[].ProfileHeight.Height获得)EachResults各区域的个别检测结果。HeightEachResults[0].Height的别名。只使用1个截面时方便使用。DetectLine检出的直线，DetectEdgeType目标形状类型指定为直线时的拟合结果DetectCircle检出的圆，DetectEdgeType目标形状类型指定为圆时的拟合结果DetectPoint检出的圆的圆心位置
```
xxxxxxxxxx
```

```
struct LEachProfileHeightResult
```

```
{
```

```
    bool Enable;
```

```
    LProfileHeight ProfileHeight;
```

```
}
```
成员名称说明Enable各区域的检测结果是否有效。ProfileHeight测量结果。
```
xxxxxxxxxx
```

```
struct LProfileHeight
```

```
{
```

```
    double Height;
```

```
    bool IsValidReferenceLine;
```

```
    LProfileLine ReferenceLine;
```

```
    bool IsValidHeightPoint;
```

```
    LProfileDPoint Point;
```

```
    LDPoint3D AbsolutePosition;
```

```
    ILDetectProfileShape DetectedShapes[];
```

```
}
```
成员名称说明Height相对于基准线法线方向的高度。IsValidReferenceLine基准线信息是否有效。ReferenceLine用于测量的基准线(如果未指定基准线，则为Z=0的直线)。IsValidHeightPoint检出点是否有效。Point检出点的坐标(X,Z)。AbsolutePosition检出点在高度图像坐标系中的坐标(X,Y,Z)。DetectedShapes根据“测量对象”的设置检出的直线、圆形等形状。
#### 截面段差测量
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LProfileStepTool
```

```
{
```

```
    ref LProfileStepParam Param;
```

```
    LProfileStepResult Result;
```

```
    LProfileStepResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LProfile profiles[])
```

```
LErrorCode UpdateReference(LProfile profiles[])
```
参数名输入/输出说明profiles输入作为处理对象的截面轮廓数据。
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LProfileStepParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILProfileMeasurementTargetParam BaseTargetParam;
```

```
    ref ILProfileMeasurementTargetParam MeasureTargetParam;
```

```
    ref bool UseReferenceLine;
```

```
    ref LProfileDetectLineCircleParam ReferenceLineParam;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等BaseTargetParam测量段差基准对象时的检测设定。MeasureTargetParam测量段差高度对象时的检测设定。UseReferenceLine设置是否使用测量基准线（暂不支持基准线，必须指定 false）。ReferenceLineParam检测测量基准线的检测设定。
```
xxxxxxxxxx
```

```
class LProfileStepResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    double AverageStep;
```

```
    LProfileStep MaximumStep;
```

```
    LProfileStep MinimumStep;
```

```
    LEachProfileStepResult[] EachResults;
```

```
    LProfileStep Step;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间AverageStep各区域段差的平均值。(EachResults[].ProfileStep.Step的平均值)MaximumStep各区域段差中的最大值及其坐标信息。(通过比较EachResults[].ProfileStep.Step获得)MinimumStep各区域段差中的最小值及其坐标信息。(通过比较EachResults[].ProfileStep.Step获得)EachResults各区域的个别检测结果。StepEachResults[0].Step的别名。只使用1个截面时方便使用。
```
xxxxxxxxxx
```

```
struct LEachProfileStepResult
```

```
{
```

```
    bool Enable;
```

```
    LProfileStep ProfileStep;
```

```
}
```
成员名称说明Enable各区域的检测结果是否有效。ProfileStep测量结果。
```
xxxxxxxxxx
```

```
struct LProfileStep
```

```
{
```

```
    double Step;
```

```
    bool IsValidReferenceLine;
```

```
    LProfileLine ReferenceLine;
```

```
    bool IsValidBasePoint;
```

```
    LProfileDPoint BasePoint;
```

```
    LDPoint3D AbsoluteBasePosition;
```

```
    ILDetectProfileShape DetectedBaseShapes[];
```

```
    bool IsValidMeasurePoint;
```

```
    LProfileDPoint MeasurePoint;
```

```
    LDPoint3D AbsoluteMeasurePosition;
```

```
    ILDetectProfileShape DetectedMeasureShapes[];
```

```
}
```
成员名称说明Step相对于基准线法线方向，基准点和高度点之间的段差。IsValidReferenceLine基准线信息是否有效。ReferenceLine用于测量的基准线(如果未指定基准线，则为Z=0的直线)。IsValidBasePoint基准高度检出点是否有效。BasePoint段差基准检出点的坐标(X,Z)。AbsoluteBasePosition段差基准检出点在高度图像坐标系中的坐标(X,Y,Z)。DetectedBaseShapes根据基准高度“测量对象”的设置检出的直线、圆形等形状IsValidMeasurePoint测量高度检出点是否有效。MeasurePoint段差高度检出点的坐标(X,Z)。AbsoluteMeasurePosition段差高度检出点在高度图像坐标系中的坐标(X,Y,Z)。DetectedMeasureShapes根据测量高度“测量对象”的设置检出的直线、圆形等形状。
#### 截面位置测量
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LProfilePositionTool
```

```
{
```

```
    ref LProfilePositionParam Param;
```

```
    LProfilePositionResult Result;
```

```
    LProfilePositionResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LProfile profiles[])
```

```
LErrorCode UpdateReference(LProfile profiles[])
```
参数名输入/输出说明profiles输入作为处理对象的截面轮廓数据。
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LProfilePositionParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILProfileMeasurementTargetParam TargetParam;
```

```
    ref bool UseReferenceLine;
```

```
    ref LProfileDetectLineCircleParam ReferenceLineParam;
```

```
    ref LDetectEdgeType DetectEdgeType
```

```
    ref bool RemoveNoise;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等TargetParam测量目标对象位置时的检测设定。UseReferenceLine设置是否使用测量基准线（不支持基准线，只能指定 false）。ReferenceLineParam检测测量基准线的检测设定。DetectEdgeType指定根据各轮廓的检出点进行拟合的目标形状类型（无/直线/圆）。RemoveNoise形状拟合时剔除异常点以避免影响。
```
xxxxxxxxxx
```

```
class LProfilePositionResult : LBaseResult, ILDetectLine2D, ILDetectCircle2D
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    double AveragePosition;
```

```
    LProfilePosition MaximumPosition;
```

```
    LProfilePosition MinimumPosition;
```

```
    LEachProfilePositionResult[] EachResults;
```

```
    LProfilePosition Position;
```

```
    LDetectLine2D DetectLine;
```

```
    LDetectCircle2D DetectCircle;
```

```
    LDetectPoint2D DetectPoint;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间AveragePosition各区域位置的平均值。(EachResults[].ProfilePosition.Position的平均值)MaximumPosition各区域位置中的最大值及其坐标信息。(通过比较EachResults[].ProfilePosition.Position获得)MinimumPosition各区域位置中的最小值及其坐标信息。(通过比较EachResults[].ProfilePosition.Position获得)EachResults各区域的个别检测结果。PositionEachResults[0].Position的别名。只使用1个截面时方便使用。DetectLine检出的直线，DetectEdgeType目标形状类型指定为直线时的拟合结果DetectCircle检出的圆，DetectEdgeType目标形状类型指定为圆时的拟合结果DetectPoint检出的圆的圆心位置
```
xxxxxxxxxx
```

```
struct LEachProfilePositionResult
```

```
{
```

```
    bool Enable;
```

```
    LProfilePosition ProfilePosition;
```

```
}
```
成员名称说明Enable各区域的检测结果是否有效。ProfilePosition测量结果。
```
xxxxxxxxxx
```

```
struct LProfilePosition
```

```
{
```

```
    double Position;
```

```
    bool IsValidReferenceLine;
```

```
    LProfileLine ReferenceLine;
```

```
    bool IsValidPositionPoint;
```

```
    LProfileDPoint Point;
```

```
    LDPoint3D AbsolutePosition;
```

```
    ILDetectProfileShape DetectedShapes[];
```

```
}
```
成员名称说明Position相对于基准线平行方向的位置。IsValidReferenceLine"基准线信息"是否有效。ReferenceLine用于测量的基准线(如果未指定基准线，则为Z=0的直线)。IsValidPositionPoint检出点是否有效。Point检出点的坐标(X,Z)。AbsolutePosition检出点在高度图像坐标系中的坐标(X,Y,Z)。DetectedShapes根据“测量对象”的设置检出的直线、圆形等形状。
#### 截面宽度测量
结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LProfileWidthTool
```

```
{
```

```
    ref LProfileWidthParam Param;
```

```
    LProfileWidthResult Result;
```

```
    LProfileWidthResult ReferenceResult;
```

```
}
```

##### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LProfile profiles[])
```

```
LErrorCode UpdateReference(LProfile profiles[])
```
参数名输入/输出说明profiles输入作为处理对象的截面轮廓数据。
##### 检测参数／结果

```
xxxxxxxxxx
```

```
class LProfileWidthParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILProfileMeasurementTargetParam TargetParam1;
```

```
    ref ILProfileMeasurementTargetParam TargetParam2;
```

```
    ref bool UseReferenceLine;
```

```
    ref LProfileDetectLineCircleParam ReferenceLineParam;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等TargetParam1测量宽度位置对象1时的检测设定。TargetParam2测量宽度位置对象2时的检测设定。UseReferenceLine设置是否使用测量基准线（暂不支持基准线，只能指定 false）。ReferenceLineParam检测测量基准线的检测设定。
```
xxxxxxxxxx
```

```
class LProfileWidthResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    double AverageWidth;
```

```
    LProfileWidth MaximumWidth;
```

```
    LProfileWidth MinimumWidth;
```

```
    LEachProfileWidthResult[] EachResults;
```

```
    LProfileWidth Width;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间AverageWidth各区域宽度的平均值。(EachResults[].ProfileWidth.Width的平均值)MaximumWidth各区域宽度中的最大值及其坐标信息。(通过比较EachResults[].ProfileWidth.Width获得)MinimumWidth各区域宽度中的最小值及其坐标信息。(通过比较EachResults[].ProfileWidth.Width获得)EachResults各区域的个别检测结果。WidthEachResults[0].Width的别名。只使用1个截面时方便使用。
```
xxxxxxxxxx
```

```
struct LEachProfileWidthResult
```

```
{
```

```
    bool Enable;
```

```
    LProfileWidth ProfileWidth;
```

```
}
```
成员名称说明Enable各区域的检测结果是否有效。ProfileWidth测量结果。
```
xxxxxxxxxx
```

```
struct LProfileWidth
```

```
{
```

```
    double Width;
```

```
    bool IsValidReferenceLine;
```

```
    LProfileLine ReferenceLine;
```

```
    bool IsValidPoint1;
```

```
    LProfileDPoint Point1;
```

```
    LDPoint3D AbsolutePosition1;
```

```
    ILDetectProfileShape DetectedShapes1[];
```

```
    bool IsValidPoint2;
```

```
    LProfileDPoint Point2;
```

```
    LDPoint3D AbsolutePosition2;
```

```
    ILDetectProfileShape DetectedShapes2[];
```

```
}
```
成员名称说明Width相对于基准线平行方向的宽度。IsValidReferenceLine"基准线信息"是否有效。ReferenceLine用于测量的基准线（如果未指定基准线，则为Z=0的直线）。IsValidPoint1检出点1是否有效。Point1位置检出点1的坐标(X,Z)。AbsolutePosition1位置检出点1在高度图像坐标系中的坐标(X,Y,Z)。DetectedShapes1根据“测量对象1”的设置检出的直线、圆形等形状。IsValidPoint2检出点2是否有效。Point2位置检出点2的坐标(X,Z)。AbsolutePosition2位置检出点2在高度图像坐标系中的坐标(X,Y,Z)。DetectedShapes2根据“测量对象2”的设置检出的直线、圆形等形状。
## 专用应用工具

### Pin针检测
可以测量设置的多个区域中的Pin针的位置和高度。
除了测量各区域之外，还可以测量“各区域高度的最大值”等。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LPinTool
```

```
{
```

```
    ref LPinParam Param;
```

```
    LPinResult Result;
```

```
    LPinResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LHeightImage heightImage, LPlane referencePlane, LDeltaPosition deltaPosition)
```

```
LErrorCode UpdateReference(LHeightImage heightImage, LPlane referencePlane)
```
参数名输入/输出说明heightImage输入作为处理对象的高度图像数据。referencePlane输入作为测量基准的平面信息。deltaPosition输入位置偏移信息。可选输入
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LPinParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref ILRegion[] Regions;
```

```
    ref ILRegion Region;
```

```
    ref double PinHeightUpper;
```

```
    ref double PinHeightLower;
```

```
    ref double MinimumPinSize;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Regions指定要处理的目标区域。Region要处理的目标区域、实际是Regions[0]的别名
便于仅单个区域的场合使用PinHeightUpperPin针高度上限（mm）。PinHeightLowerPin针高度下限（mm）。MinimumPinSize可识别为Pin的最小圆的直径（pix）。
```
xxxxxxxxxx
```

```
class LPinResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime
```

```
    LPinPosition MaximumHeightPin;
```

```
    LPinPosition MinimumHeightPin;
```

```
    LPinPosition MaximumXyDeviationPin;
```

```
    LPinPosition MinimumXyDeviationPin;
```

```
    LEachPinResult[] EachResults;
```

```
    ILRegion[] Regions;
```

```
    ILRegion Region;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间MaximumHeightPin各区域检出的Pin中的最大高度及其坐标信息。MinimumHeightPin各区域检出的Pin中的最小高度及其坐标信息。MaximumXyDeviationPin各区域内 XY 偏差最大的Pin针信息。MinimumXyDeviationPin各区域内 XY 偏差最小的Pin针信息。EachResults各个区域的测量结果。Regions／Region实际测量时使用的区域，反映位置补正的结果。
```
xxxxxxxxxx
```

```
struct LEachPinResult
```

```
{
```

```
    bool Enable;
```

```
    LPinPosition Pin;
```

```
}
```
成员名称说明Enable各区域的检测结果是否有效。各区域的检测结果是否有效。Pin各区域检出的Pin的高度、坐标信息。
```
xxxxxxxxxx
```

```
struct LPinPosition
```

```
{
```

```
    double Height;
```

```
    double DistFromCenter
```

```
    LDPoint3D PinPosition;
```

```
}
```
成员名称说明Height相对于基准面法线方向的高度（H）。DistFromCenter相对于测量区域中心的偏差。PinPosition在绝对坐标系中的检测点坐标（X，Y，Z）。
### 涂胶检测
测量涂胶的高度和宽度，可以检查涂胶量和断胶等缺陷。

#### 类定义

结果（Result）在执行检测（Execute）时更新、基准值（ReferenceResult）在更新主控基准（UpdateReference）时更新。

```


xxxxxxxxxx
```

```
class LBeadInspectionTool
```

```
{
```

```
    ref LBeadInspectionParam Param;
```

```
    LBeadInspectionResult Result;
```

```
    LBeadInspectionResult ReferenceResult;
```

```
}
```

#### 方法定义
执行Execute方法时更新Result、执行UpdateReference时更新ReferenceResult。
两种方法均使用Param中的设置参数进行检测处理。
执行 GetInterpolateProfiles 获取对无效数据进行插补后的截面数据。
执行 GetLuminanceEdgeStrengthWaveforms 获取亮度边缘强度波形数据。

```


xxxxxxxxxx
```

```
LErrorCode Execute(LProfile profiles[], LPlane referencePlane)
```

```
LErrorCode UpdateReference(LProfile profiles[], LPlane referencePlane)
```

```
LErrorCode GetInterpolateProfiles(LProfile profiles[], out LProfile interpolateProfiles[])
```

```
LErrorCode GetLuminanceEdgeStrengthWaveforms(LProfile profiles[], out LEdgeStrengthWaveform edgeStrengthWaveforms[])
```
参数名输入/输出说明profiles输入作为处理对象的截面轮廓数据。referencePlane输入作为测量基准的平面信息。interpolateProfiles输出无效数据插补处理后的截面数据。edgeStrengthWaveforms输出亮度边缘强度的波形数据。边缘强度波形（微分波形）数据

```


xxxxxxxxxx
```

```
struct LEdgeStrengthWaveform{
```

```
    public int Count;
```

```
    public double[] Source;
```

```
    public double Pitch;
```

```
}
```
成员名称说明Count数据的数量。Source边缘强度波形值数组。Pitch数据之间的间距。
#### 检测参数／结果

```
xxxxxxxxxx
```

```
class LBeadInspectionParam : LBaseParam
```

```
{
```

```
    ref string Name;
```

```
    ref LProfileRange Range;
```

```
    ref LBeadInspectionEdgeParam LeftEdgeParam;
```

```
    ref LBeadInspectionEdgeParam RightEdgeParam;
```

```
    ref LBeadInspectionThreshold HeightThreshold;
```

```
    ref LBeadInspectionThreshold WidthThreshold;
```

```
    ref bool UseInterpolation;
```

```
    ref bool UseLuminanceWidth;
```

```
}
```
成员名称说明Name测量工具名称，用于区分测量内容等Range指定检测涂胶峰值高度的范围。LeftEdgeParam指定检测涂胶左侧边缘的设置。RightEdgeParam指定检测涂胶右侧边缘的设置。HeightThreshold指定用于高度异常判定的阈值。WidthThreshold指定用于宽度异常判定的阈值。UseInterpolation指定是否进行无效数据插值。UseLuminanceWidth指定是否通过亮度进行宽度检测。
```
xxxxxxxxxx
```

```
public struct LBeadInspectionEdgeParam
```

```
{
```

```
    public double Width;
```

```
    public double DetectionLevel;
```

```
}
```
成员名称说明Width指定相对于检测到的峰值去检测边缘的范围（距离）。DetectionLevel指定涂胶检测的边缘检测阈值。
如果使用亮度进行宽度检测，请将其指定为百分比，对比度变化最大的区域为 100%。
```
xxxxxxxxxx
```

```
public struct LBeadInspectionThreshold
```

```
{
```

```
    public double Upper;
```

```
    public double Lower;
```

```
}
```
成员名称说明Upper测定结果高于该值时，判定为异常。Lower测定结果低于该值时，判定为异常。
```
xxxxxxxxxx
```

```
class LBeadInspectionResult : LBaseResult
```

```
{
```

```
    LErrorCode ErrorCode;
```

```
    TimeSpan ProcessingTime;
```

```
    LProfileHeight MaximumHeight;
```

```
    LProfileHeight MinimumHeight;
```

```
    LProfileWidth MaximumWidth;
```

```
    LProfileWidth MinimumWidth;
```

```
    LEachBeadInspectionResult[] EachResults;
```

```
    LBeadInspectionAbnormalPart LongestAbnormalPartHeightUpper;
```

```
    LBeadInspectionAbnormalPart LongestAbnormalPartHeightLower;
```

```
    LBeadInspectionAbnormalPart LongestAbnormalPartWidthUpper;
```

```
    LBeadInspectionAbnormalPart LongestAbnormalPartWidthLower;
```

```
}
```
成员名称说明ErrorCode处理结果返回值。详情请参照错误代码ProcessingTime存储处理时间MaximumHeight各区域高度中的最大高度、坐标信息。(通过比较EachResults[].ProfileHeight.Height获得)MinimumHeight各区域高度中的最小高度、坐标信息。(通过比较EachResults[].ProfileHeight.Height获得)MaximumWidth各区域高度中的最大宽度、坐标信息。(通过比较EachResults[].ProfileWidth.Width获得)MinimumWidth各区域高度中的最小宽度、坐标信息。(通过比较EachResults[].ProfileWidth.Width获得)EachResults各区域的测量结果。LongestAbnormalPartHeightUpper在高度超过上限而被判定为异常的部位中，持续被判定异常的最大长度的部位。LongestAbnormalPartHeightLower在高度低于下限而被判定为异常的部位中，持续被判定异常的最大长度的部位。LongestAbnormalPartWidthUpper在宽度超过上限而被判定为异常的部位中，持续被判定异常的最大长度的部位。LongestAbnormalPartWidthLower在宽度低于下限而被判定为异常的部位中，持续被判定异常的最大长度的部位。
```
xxxxxxxxxx
```

```
struct LEachBeadInspectionResult
```

```
{
```

```
    LMeasurementStatus HeightStatus;
```

```
    LProfileHeight Height;
```

```
    LMeasurementStatus WidthStatus;
```

```
    LProfileWidth Width;
```

```
}
```
成员名称说明HeightStatus高度结果的异常判定结果（Normal/Upper/Lower/Fail）。Fail时不能参照高度。Height高度。WidthStatus宽度结果的异常判定结果（Normal／Upper／Lower／Fail）。Fail时不能参照宽度。Width宽度。
```
xxxxxxxxxx
```

```
struct LBeadInspectionAbnormalPart
```

```
{
```

```
    double Length;
```

```
    int StartIndex;
```

```
    int EndIndex;
```

```
}
```
成员名称说明Length判定为异常的长度。StartIndex第一个判定为异常的位置（EachResults的索引）。EndIndex最后一个判定为异常的位置（EachResults的索引）。
# 实用程序

## 测量结果访问扩展方法
可以从工具的测量结果（LxxxResult，xxx为工具名，下同）中获取测量值、单位、显示用字符串。
3D显示库（LjDev3dView）的结果使用本扩展方法。

### 方法定义

扩展方法所有工具通用。以LxxxResult.GetResultValue（LxxxResultType）形式使用。

#### 获取测量值

从LxxxResult获取与LxxxResultType相对应的“值”(double)。[返回值示例：3.24564]

```


xxxxxxxxxx
```

```
double GetResultValue(this LxxxResult result, LxxxResultType resultType)
```

#### 获取测量值单位
从LxxxResult获取与LxxxResultType相对应的“单位”(LUnitType)。[返回值示例：LUnitType.Mm]

```


xxxxxxxxxx
```

```
LUnitType GetResultUnitType(this LxxxResult result, LxxxResultType resultType)
```

#### 获取显示用文字
获取与LxxxResultType对应的格式化后字符串。[返回值示例：“3.246mm”]

```


xxxxxxxxxx
```

```
string GetFormattedResultValue(this LxxxResult result, LxxxResultType resultType)
```

#### 获取各区域结果的测量值
获取与LEachxxxResultType相对应的“值”（double）。（区域[0]的结果和所有区域的结果数组）

```


xxxxxxxxxx
```

```
double GetEachResultValue(this LEachxxxResult result, LEachxxxResultType resultType)
```

```
IEnumerabledouble> GetEachResultValues(this LEachxxxResult result, LEachxxxResultType resultType)
```

#### 获取各区域结果的测量值单位
获取与LEachxxxResultType相对应的“单位”(LUnitType)。（区域[0]的结果和所有区域的结果数组）

```


xxxxxxxxxx
```

```
LUnitType GetEachResultUnitType(this LEachxxxResult result, LEachxxxResultType resultType)
```

```
IEnumerableLUnitType> GetEachResultUnitTypes(this LEachxxxResult result, LEachxxxResultType resultType)
```

#### 获取各区域结果的显示用文字
获取与LEachxxxResultType相对应的格式化后字符串。（区域[0]的结果和所有区域的结果数组）

```


xxxxxxxxxx
```

```
string GetFormattedEachResultValue(this LEachxxxResult result, LEachxxxResultType resultType)
```

```
IEnumerablestring> GetFormattedEachResultValues(this LEachxxxResult result, LEachxxxResultType resultType)
```

### 定义

#### 工具公用

##### 测量值单位（LUnitType）
测量值单位有以下种类：


定义(LUnitType) | 含义

None | 无单位

Mm | mm

Degree | °

Mm3 | mm^3^

Number | 个

Percent | %


#### 特定工具

##### 高度测量


定义(LHeightResultType) | 含义

MaximumPeakHeightHeight | 各区域峰值高度中最大的高度、坐标信息、相对于基准面法线方向的高度H

MaximumPeakHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

MaximumPeakHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

MinimumPeakHeightHeight | 各区域峰值高度中最小的高度、坐标信息、相对于基准面法线方向的高度H

MinimumPeakHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

MinimumPeakHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

MaximumBottomHeightHeight | 各区域谷值高度中最大的高度、坐标信息、相对于基准面法线方向的高度H

MaximumBottomHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

MaximumBottomHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

MinimumBottomHeightHeight | 各区域谷值高度中最小的高度、坐标信息、相对于基准面法线方向的高度H

MinimumBottomHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

MinimumBottomHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

MaximumAverageHeightHeight | 各区域平均高度中最大的高度信息、相对于基准面的法线方向的高度H

MaximumAverageHeightAbsoluteZ | 同上、绝对坐标系中的高度Z

MinimumAverageHeightHeight | 各区域平均高度中最小的高度信息、相对于基准面的法线方向的高度H

MinimumAverageHeightAbsoluteZ | 同上、绝对坐标系中的高度Z

MaximumConvexVolume | 各区域凸体积中的最大值

MinimumConvexVolume | 各区域凸体积中的最小值

MaximumConcaveVolume | 各区域凹体积中的最大值

MinimumConcaveVolume | 各区域凹体积中的最小值


定义(LEachHeightResultType) | 含义

EachHeightResultPeakHeightHeight | 峰值高度，相对于基准面法线方向高度H

EachHeightResultPeakHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

EachHeightResultPeakHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

EachHeightResultBottomHeightHeight | 谷值高度，相对于基准面法线方向高度H

EachHeightResultBottomHeightAbsolutePositionX／Y／Z | 同上、绝对坐标系中的检测点坐标X/Y/Z

EachHeightResultBottomHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)

EachHeightResultAverageHeightHeight | 平均高度，相对于基准面法线方向高度H

EachHeightResultAverageHeightAbsoluteZ | 同上、绝对坐标系中的检测点坐标X/Y/Z

EachHeightResultConvexVolume | 凸体积

EachHeightResultConcaveVolume | 凹体积


##### 平面度测量


定义(LFlatnessResultType) | 含义

Flatness | 平面度


##### 图形搜索


定义(LPatternMatchResultType) | 含义

PatternMatchResultDetectCount | 检出个数


定义(LEachPatternMatchResultType) | 含义

EachPatternMatchResultScore | 相似度

EachPatternMatchResultAbsolutePositionCenterPositionX／Y | 绝对坐标系中的检出位置坐标(X,Y) 将基准图形匹配到检测对象时图形区域中心坐标作为检出位置时的坐标。

EachPatternMatchResultAbsolutePositionAngle | 绝对坐标系中的检测图形旋转角

EachPatternMatchResultRegionRelatedPositionCenterPositionX／Y | 固定搜索区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标(X,Y)。

EachPatternMatchResultRegionRelatedPositionAngle | 固定搜索区域的坐标，对图像进行位置偏移修正时的检测图形旋转角


##### 瑕疵


定义(LDefectResultType) | 含义

DetectCount | 检出瑕疵的个数

TotalArea | 检出瑕疵的总面积

MaximumHeight | 检出瑕疵的最大高度


定义(LEachDefectResultType) | 含义

EachDefectResultPositionX／Y | 各瑕疵的位置。使用瑕疵的重心X/Y。

EachDefectResultRegionRelatedPositionX／Y | 各瑕疵的相对位置。固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachDefectResultMaximumHeightHeight | 各瑕疵高度最大值的位置坐标、瑕疵高度

EachDefectResultMaximumHeightAbsolutePositionX／Y | 同上、绝对坐标系中的检出位置坐标X／Y

EachDefectResultMaximumHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachDefectResultMinimumHeightHeight | 各瑕疵高度最小值的位置坐标、瑕疵高度

EachDefectResultMinimumHeightAbsolutePositionX／Y | 同上、绝对坐标系中的检出位置坐标X／Y

EachDefectResultMinimumHeightRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachDefectResultAverageHeight | 各瑕疵的高度的平均值

EachDefectResultArea | 各瑕疵的面积

EachDefectResultBoundingBoxCenterX／Y | 各瑕疵的外接矩形（绝对坐标）、中心坐标X／Y

EachDefectResultBoundingBoxWidth | 同上、矩形的宽度

EachDefectResultBoundingBoxHeight | 同上、矩形的高度

EachDefectResultBoundingBoxAngle | 同上、旋转角度(0≦angle＜360°)

EachDefectResultRegionRelatedBoundingBoxCenterX／Y | 固定各区域的坐标，对图像一方进行位置偏移修正而得到的各瑕疵 外接矩形（相对坐标）位置、中心坐标X/Y

EachDefectResultRegionRelatedBoundingBoxWidth | 同上、矩形的宽度

EachDefectResultRegionRelatedBoundingBoxHeight | 同上、矩形的高度

EachDefectResultRegionRelatedBoundingBoxAngle | 同上、旋转角度(0≦angle＜360°)

EachDefectResultAxisRatio | 各瑕疵的针状度

EachDefectResultRoundness | 各瑕疵的圆形度


##### 细微瑕疵


定义(LFineDefectResultType) | 含义

DetectCount | 检出的瑕疵的个数

TotalDefectArea | 检出的瑕疵的总量

MaximumDefectLevel | 检出的瑕疵的最大等级


定义(LEachFineDefectResultType) | 含义

EachFineDefectResultPositionX／Y | 各瑕疵的位置。瑕疵重心的X/Y。

EachFineDefectResultRegionRelatedPositionX／Y | 各瑕疵的相对位置。固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachFineDefectResultDefectArea | 各瑕疵的瑕疵量

EachFineDefectResultMaximumDefectLevelDefectLevel | 各瑕疵的瑕疵等级最大值的位置坐标、瑕疵等级

EachFineDefectResultMaximumDefectLevelAbsolutePositionX／Y | 同上、绝对坐标系中的检出位置坐标X／Y

EachFineDefectResultMaximumDefectLevelRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachFineDefectResultMinimumDefectLevelDefectLevel | 各瑕疵的瑕疵等级最小值的位置坐标、瑕疵等级

EachFineDefectResultMinimumDefectLevelAbsolutePositionX／Y | 同上、绝对坐标系中的检出位置坐标X／Y

EachFineDefectResultMinimumDefectLevelRegionRelatedPositionX／Y | 同上、固定各区域的坐标，对图像进行位置偏移修正而得到的检测位置坐标X/Y

EachFineDefectResultAverageDefectLevel | 各瑕疵等级的平均值


##### 平面检测


定义(LPlaneResultType) | 含义

PlaneA | 以z=ax+by+c平面公式表示时的平面系数a

PlaneB | 以z=ax+by+c平面公式表示时的平面系数b

PlaneC | 以z=ax+by+c平面公式表示时的平面系数c


##### 点检测


定义(LPointResultType) | 含义

DetectPointPointX／Y | 检出的点的坐标X／Y

DeltaPositionCenterX／Y | 位置偏移信息旋转中心坐标X／Y

DeltaPositionX／Y | 位置偏移信息偏移量X／Y

DeltaPositionTheta | 位置偏移信息偏移量θ


##### 直线检测


定义(LLineResultType) | 含义

DetectLineLineStartX／Y | 检出的直线的起点坐标X／Y

DetectLineLineEndX／Y | 检出的直线的终点坐标X／Y

DeltaPositionCenterX／Y | 位置偏移信息旋转中心坐标X／Y

DeltaPositionX／Y | 位置偏移信息偏移量X／Y

DeltaPositionTheta | 位置偏移信息偏移量θ


##### 圆检测


定义(LCircleResultType) | 含义

DetectCircleCircleCenterX／Y | 检出的圆的中心坐标X／Y

DetectCircleCircleRadius | 检出的圆的半径

DetectCircleCircleDiameter | 检出的圆的直径

DetectPointPointX／Y | 检出的圆的中心点坐标X／Y

DeltaPositionCenterX／Y | 位置偏移信息旋转中心坐标X／Y

DeltaPositionX／Y | 位置偏移信息偏移量X／Y

DeltaPositionTheta | 位置偏移信息偏移量θ


##### 直线间的中心线


定义(LLineMedianResultType) | 含义

DetectLineLineStartX／Y | 检出的直线的起点坐标X／Y

DetectLineLineEndX／Y | 检出的直线的终点坐标X／Y


##### 经过两点的直线


定义(LLineThroughPointsResultType) | 含义

DetectLineLineStartX／Y | 检出的直线的起点坐标X／Y

DetectLineLineEndX／Y | 检出的直线的终点坐标X／Y


##### 直线间的交点


定义(LPointIntersectionResultType) | 含义

DetectPointPointX／Y | 检出的点的坐标X／Y


##### 点与点的中点


定义(LPointMiddleResultType) | 含义

DetectPointPointX／Y | 检出的点的坐标X／Y


##### 线与线的距离测量


定义(LDistanceLineLineResultType) | 含义

DistanceDistance | 线到线的直线距离

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y

MinimumDistanceDistance | 线到线的最短距离

MinimumDistanceStartPointX／Y | 最短距离的起点坐标X／Y

MinimumDistanceEndPointX／Y | 最短距离的终点坐标X／Y

MaximumDistanceDistance | 线到线的最长距离

MaximumDistanceStartPointX／Y | 最长距离的起点坐标X／Y

MaximumDistanceEndPointX／Y | 最长距离的终点坐标X／Y


##### 线与点的距离测量


定义(LDistanceLinePointResultType) | 含义

DistanceDistance | 线与点的距离测量

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y


##### 线与圆的距离测量


定义(LDistanceLineCircleResultType) | 含义

DistanceDistance | 线与圆的直线距离

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y


##### 点与点的距离测量


定义(LDistancePointPointResultType) | 含义

DistanceDistance | 点与点的直线距离

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y

BaseHorizontalDistanceDistance | 与基准平行的测量距离

BaseHorizontalDistanceStartPointX／Y | 与基准平行的测量距离起点坐标X／Y

BaseHorizontalDistanceEndPointX／Y | 与基准平行的测量距离终点坐标X／Y

BaseVerticalDistanceDistance | 与基准垂直的测量距离

BaseVerticalDistanceStartPointX／Y | 与基准垂直的测量距离起点坐标X／Y

BaseVerticalDistanceEndPointX／Y | 与基准垂直的测量距离终点坐标X／Y


##### 点与圆的距离测量


定义(LDistancePointCircleResultType) | 含义

DistanceDistance | 点与圆的直线距离

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y

BaseHorizontalDistanceDistance | 与基准平行的测量距离

BaseHorizontalDistanceStartPointX／Y | 与基准平行的测量距离起点坐标X／Y

BaseHorizontalDistanceEndPointX／Y | 与基准平行的测量距离终点坐标X／Y

BaseVerticalDistanceDistance | 与基准垂直的测量距离

BaseVerticalDistanceStartPointX／Y | 与基准垂直的测量距离起点坐标X／Y

BaseVerticalDistanceEndPointX／Y | 与基准垂直的测量距离终点坐标X／Y


##### 圆与圆的距离测量


定义(LDistanceCircleCircleResultType) | 含义

DistanceDistance | 圆与圆的直线距离

DistanceStartPointX／Y | 直线距离的起点坐标X／Y

DistanceEndPointX／Y | 直线距离的终点坐标X／Y

BaseHorizontalDistanceDistance | 与基准平行的测量距离

BaseHorizontalDistanceStartPointX／Y | 与基准平行的测量距离起点坐标X／Y

BaseHorizontalDistanceEndPointX／Y | 与基准平行的测量距离终点坐标X／Y

BaseVerticalDistanceDistance | 与基准垂直的测量距离

BaseVerticalDistanceStartPointX／Y | 与基准垂直的测量距离起点坐标X／Y

BaseVerticalDistanceEndPointX／Y | 与基准垂直的测量距离终点坐标X／Y


##### 线与线的角度测量


定义(LAngleLineLineResultType) | 含义

AngleAngle | 测量角度

AngleCenterX／Y | 测量角度的中心坐标X/Y

AngleStartAngle | 测量角度的开始角度

AngleEndAngle | 测量角度的结束角度


##### 截面高度测量


定义(LProfileHeightResultType) | 含义

AverageHeight | 各区域高度的平均值

MaximumHeightHeight | 各区域高度中的最大高度、坐标信息、相对于基准线法线方向的高度

MaximumHeightReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumHeightPointX／Z | 同上、检出点的坐标X／Z

MaximumHeightAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

MinimumHeightHeight | 各区域高度中的最小高度、坐标信息、相对于基准线法线方向的高度

MinimumHeightReferenceLineA／B | 同上、用于测量的基准线A／B

MinimumHeightPointX／Z | 同上、检出点的坐标X／Z

MinimumHeightAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

DetectLineLineStartX／Y | 检出的直线的起点坐标X／Y

DetectLineLineEndX／Y | 检出的直线的终点坐标X／Y

DetectPointPointX／Y | 检出的点的坐标X／Y

DetectCircleCircleCenterX／Y | 检出的圆的中心坐标X／Y

DetectCircleCircleRadius | 检出的圆的半径

DetectCircleCircleDiameter | 检出的圆的直径


定义(LEachProfileHeightResultType) | 含义

EachProfileHeightResultProfileHeightHeight | 相对于基准线法线方向的高度

EachProfileHeightResultProfileHeightReferenceLineA／B | 用于测量的基准线A／B

EachProfileHeightResultProfileHeightPointX／Z | 检出点的坐标X／Z

EachProfileHeightResultProfileHeightAbsolutePositionX／Y／Z | 检出点在高度图像坐标系中的坐标X／Y／Z


##### 截面段差测量


定义(LProfileStepResultType) | 含义

AverageStep | 各区域段差的平均值

MaximumStepStep | 各区域段差中的最大段差、坐标信息、相对于基准线法线方向的基准高度和测定高度的段差

MaximumStepReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumStepBasePointX／Z | 同上、段差基准检出点的坐标X／Z

MaximumStepMeasurePointX／Z | 同上、段差高度检出点的坐标X／Z

MaximumStepAbsoluteBasePositionX／Y／Z | 同上、段差基准检出点在高度图像坐标系中的坐标X／Y／Z

MaximumStepAbsoluteMeasurePositionX／Y／Z | 同上、段差高度检出点在高度图像坐标系中的坐标X／Y／Z

MinimumStepStep | 各区域段差中的最小段差、坐标信息、相对于基准线法线方向的基准高度和测定高度的段差

MinimumStepReferenceLineA／B | 同上、用于测量的基准线A／B

MinimumStepBasePointX／Z | 同上、段差基准检出点的坐标X／Z

MinimumStepMeasurePointX／Z | 同上、段差高度检出点的坐标X／Z

MinimumStepAbsoluteBasePositionX／Y／Z | 同上、段差基准检出点在高度图像坐标系中的坐标X／Y／Z

MinimumStepAbsoluteMeasurePositionX／Y／Z | 同上、段差高度检出点在高度图像坐标系中的坐标X／Y／Z


定义(LEachProfileStepResultType) | 含义

EachProfileStepResultProfileStepStep | 相对于基准线法线方向的基准高度和测定高度的段差

EachProfileStepResultProfileStepReferenceLineA／B | 用于测量的基准线A／B

EachProfileStepResultProfileStepBasePointX／Z | 段差基准检出点的坐标X／Z

EachProfileStepResultProfileStepMeasurePointX／Z | 段差高度检出点的坐标X／Z

EachProfileStepResultProfileStepAbsoluteBasePositionX／Y／Z | 段差基准检出点在高度图像坐标系中的坐标X／Y／Z

EachProfileStepResultProfileStepAbsoluteMeasurePositionX／Y／Z | 段差高度检出点在高度图像坐标系中的坐标X／Y／Z


##### 截面位置测量


定义(LProfilePositionResultType) | 含义

AveragePosition | 各区域位置的平均值

MaximumPositionPosition | 各区域位置中的最大值、坐标信息、相对于基准线平行方向的位置

MaximumPositionReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumPositionPointX／Z | 同上、检出点的坐标X／Z

MaximumPositionAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

MinimumPositionPosition | 各区域位置中的最小值、坐标信息、相对于基准线平行方向的位置

MinimumPositionReferenceLineA／B | 同上、用于测量的基准线A／B

MinimumPositionPointX／Z | 同上、检出点的坐标X／Z

MinimumPositionAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

DetectLineLineStartX／Y | 检出的直线的起点坐标X／Y

DetectLineLineEndX／Y | 检出的直线的终点坐标X／Y

DetectPointPointX／Y | 检出的点的坐标X／Y

DetectCircleCircleCenterX／Y | 检出的圆的中心坐标X／Y

DetectCircleCircleRadius | 检出的圆的半径

DetectCircleCircleDiameter | 检出的圆的直径


定义(LEachProfilePositionResultType) | 含义

EachProfilePositionResultProfilePositionPosition | 相对于基准线平行方向的位置

EachProfilePositionResultProfilePositionReferenceLineA／B | 用于测量的基准线A／B

EachProfilePositionResultProfilePositionPointX／Z | 检出点的坐标X／Z

EachProfilePositionResultProfilePositionAbsolutePositionX／Y／Z | 检出点在高度图像坐标系中的坐标X／Y／Z


##### 截面宽度测量


定义(LProfileWidthResultType) | 含义

AverageWidth | 各区域宽度的平均值

MaximumWidthWidth | 各区域宽度中的最大值、坐标信息、相对于基准线平行方向的宽度

MaximumWidthReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumWidthPoint1X／Z | 同上、位置检出点1坐标X／Z

MaximumWidthPoint2X／Z | 同上、位置检出点2坐标X／Z

MaximumWidthAbsolutePosition1X／Y／Z | 同上、位置检出点1在高度图像坐标系中的坐标X／Y／Z

MaximumWidthAbsolutePosition2X／Y／Z | 同上、位置检出点2在高度图像坐标系中的坐标X／Y／Z

MinimumWidthWidth | 各区域宽度中的最小值、坐标信息、相对于基准线平行方向的宽度

MinimumWidthReferenceLineA／B | 同上、用于测量的基准线A／B

 | 同上、位置检出点1坐标X／Z

MinimumWidthPoint2X／Z | 同上、位置检出点2坐标X／Z

MinimumWidthAbsolutePosition1X／Y／Z | 同上、位置检出点1在高度图像坐标系中的坐标X／Y／Z

MinimumWidthAbsolutePosition2X／Y／Z | 同上、位置检出点2在高度图像坐标系中的坐标X／Y／Z


定义(LEachBeadInspectionResultType) | 含义

EachProfileWidthResultProfileWidthWidth | 相对于基准线平行方向的宽度

EachProfileWidthResultProfileWidthReferenceLineA／B | 用于测量的基准线A／B

EachProfileWidthResultProfileWidthPoint1X／Z | 位置检出点1坐标X／Z

EachProfileWidthResultProfileWidthPoint2X／Z | 位置检出点2坐标X／Z

EachProfileWidthResultProfileWidthAbsolutePosition1X／Y／Z | 位置检出点1在高度图像坐标系中的坐标X／Y／Z

EachProfileWidthResultProfileWidthAbsolutePosition2X／Y／Z | 位置检出点2在高度图像坐标系中的坐标X／Y／Z


##### Pin针检测


定义(LPinResultType) | 含义

MaximumPinHeight | 各区域Pin中最大高度、坐标信息、相对于基准面法线方向的高度H

MaximumHeightPinXyDeviation | 同上、相对于测量区域中心的偏移、XY偏差量

MaximumHeightPinPinPositionX／Y／Z | 同上、检出点在绝对坐标系中的坐标X/Y/Z

MinimumHeightPinHeight | 各区域Pin中最小高度、坐标信息、相对于基准面法线方向的高度H

MinimumHeightPinXyDeviation | 同上、相对于测量区域中心的偏移、XY偏差量

MinimumHeightPinPinPositionX／Y／Z | 同上、检出点在绝对坐标系中的坐标X/Y/Z

MaximumXyDeviationPinHeight | 各区域XY偏差最大量的Pin信息，基准平面法线方向高度H

MaximumXyDeviationPinXyDeviation | 同上、检出的Pin位置与测量区域中心的偏差，XY偏差量

MaximumXyDeviationPinPinPositionX／Y／Z | 同上、绝对坐标系下检出点坐标X/Y/Z

MinimumXyDeviationPinHeight | 各区域XY偏差量最小的Pin信息，基准平面法线方向高度H

MinimumXyDeviationPinXyDeviation | 同上、检出的Pin位置与测量区域中心的偏差，XY偏差量

MinimumXyDeviationPinPinPositionX／Y／Z | 同上、绝对坐标系下检出点坐标X/Y/Z


定义(LEachPinResultType) | 含义

EachPinResultPinHeight | Pin的高度、坐标信息、相对于基准面法线方向的高度H

EachPinResultPinXyDeviation | 同上，相对于测量区域中心的偏移、XY偏差量

EachPinResultPinPinPositionX／Y／Z | 同上、检出点在绝对坐标系中的坐标X/Y/Z


##### 涂胶检测


定义(LBeadInspectionResultType) | 含义

MaximumHeightHeight | 各区域高度中的最大高度、坐标信息、相对于基准线法线方向的高度

MaximumHeightReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumHeightPointX／Z | 同上、检出点的坐标X／Z

MaximumHeightAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

MinimumHeightHeight | 各区域高度中的最小高度、坐标信息、相对于基准线法线方向的高度

MinimumHeightReferenceLineA／B | 同上、用于测量的基准线A／B

MinimumHeightPointX／Z | 同上、检出点的坐标X／Z

MinimumHeightAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

MaximumWidthWidth | 各区域宽度中的最大值、坐标信息、相对于基准线平行方向的宽度

MaximumWidthReferenceLineA／B | 同上、用于测量的基准线A／B

MaximumWidthPoint1X／Z | 同上、位置检出点1坐标X／Z

MaximumWidthPoint2X／Z | 同上、位置检出点2坐标X／Z

MaximumWidthAbsolutePosition1X／Y／Z | 同上、位置检出点1在高度图像坐标系中的坐标X／Y／Z

MaximumWidthAbsolutePosition2X／Y／Z | 同上、位置检出点2在高度图像坐标系中的坐标X／Y／Z

MinimumWidthWidth | 各区域宽度中的最小值、坐标信息、相对于基准线平行方向的宽度

MinimumWidthReferenceLineA／B | 同上、用于测量的基准线A／B

MinimumWidthPoint1X／Z | 同上、位置检出点1坐标X／Z

MinimumWidthPoint2X／Z | 同上、位置检出点2坐标X／Z

MinimumWidthAbsolutePosition1X／Y／Z | 同上、位置检出点1在高度图像坐标系中的坐标X／Y／Z

MinimumWidthAbsolutePosition2X／Y／Z | 同上、位置检出点2在高度图像坐标系中的坐标X／Y／Z

LongestAbnormalPartHeightUpperLength | 在高度超过上限而被判定为异常的部位中，持续被判定异常的最大长度

LongestAbnormalPartHeightUpperStartIndex | 同上、被判定为异常的最初位置

LongestAbnormalPartHeightUpperEndIndex | 同上、被判定为异常的最后位置

LongestAbnormalPartHeightLowerLength | 在高度低于下限而被判定为异常的部位中，持续被判定异常的最大长度

LongestAbnormalPartHeightLowerStartIndex | 同上、被判定为异常的最初位置

LongestAbnormalPartHeightLowerEndIndex | 同上、被判定为异常的最后位置

LongestAbnormalPartWidthUpperLength | 在宽度超过上限而被判定为异常的部位中，持续被判定异常的最大长度

LongestAbnormalPartWidthUpperStartIndex | 同上、被判定为异常的最初位置

LongestAbnormalPartWidthUpperEndIndex | 同上、被判定为异常的最后位置

LongestAbnormalPartWidthLowerLength | 在宽度低于下限而被判定为异常的部位中，持续被判定异常的最大长度

LongestAbnormalPartWidthLowerStartIndex | 同上、被判定为异常的最初位置

LongestAbnormalPartWidthLowerEndIndex | 同上、被判定为异常的最初位置


定义(LEachBeadInspectionResultType) | 含义

EachBeadInspectionResultHeightHeight | 峰值高度，相对于基准面法线方向高度

EachBeadInspectionResultHeightReferenceLineA／B | 同上、用于测量的基准线A／B

EachBeadInspectionResultHeightPointX／Z | 同上、检出点的坐标X／Z

EachBeadInspectionResultHeightAbsolutePositionX／Y／Z | 同上、检出点在高度图像坐标系中的坐标X／Y／Z

EachBeadInspectionResultWidthWidth | 宽度，相对于基准线平行方向的宽度

EachBeadInspectionResultWidthReferenceLineA／B | 同上、用于测量的基准线A／B

EachBeadInspectionResultWidthPoint1X／Z | 同上、位置检出点1坐标X／Z

EachBeadInspectionResultWidthPoint2X／Z | 同上、位置检出点2坐标X／Z

EachBeadInspectionResultWidthAbsolutePosition1X／Y／Z | 同上、位置检出点1在高度图像坐标系中的坐标X／Y／Z

EachBeadInspectionResultWidthAbsolutePosition2X／Y／Z | 同上、位置检出点2在高度图像坐标系中的坐标X／Y／Z


# 错误代码

表示工具处理结果的代码


定义(LErrorCode) | 值 | 含义 | 解决方案

Unexecuted | 0 | 工具未运行 | 请调用工具类的Execute方法执行工具

Success | 1 | 成功完成 | －

NeedLicense | 10 | 需要额外许可证 | 激活所使用工具所需的许可证。

InvalidImage | 100 | 图像数据无效 | 请确认上一步的过滤器处理是否失败

UnsupportedImage | 101 | 图像数据无法处理 | 请使用通过LJ Developer通讯库LjDevCommunication.dll获取的图像

UnsupportedImageSize | 102 | 超出可处理的图像大小 | 请确认处理对象图像的尺寸（X/Y像素数）

InvalidParam | 103 | 参数无效 | 请确认参数内容

InvalidDeltaPosition | 104 | 位置补正信息无效 | 请确认是否正确指定/获取了位置补正信息

InvalidPlane | 105 | 平面信息无效 | 请确认是否正确指定了平面信息

InvalidPattern | 106 | 图形无效 | 请确认是否正确注册了图形信息 请在执行工具前调用UpdatePattern更新基准图形

NoDataInRegions | 107 | 没有可处理的对象数据 | 请确认检测区域信息及位置补正信息是否正确

DetectEdgeFailed | 108 | 边缘检出失败 | 请确认目标图像的检测区域中是否存在边缘（有高度差的台阶） 请确认边缘检测参数是否正确

InvalidDetectShape | 109 | 不正确的检出形状 | 请确认检出形状是否正确指定/检测成功。

InvalidProfile | 110 | 不正确的截面轮廓数据 | 请确认截面轮廓数据是否正确指定/提取。

DefectCountOverflow | 111 | 超出瑕疵工具的检测上限 | 请根据瑕疵显示图像，调整设置以减少检出瑕疵。

InvalidRegion | 112 | 不正确的区域 | 请确认是否正确指定了区域 对于形状范围，只能与与创建的图像大小/间距相同的图像一起使用

AllocateMemoryFailed | 200 | 内存分配失败 | 请确认电脑的内存使用情况 请考虑缩小要处理的图像尺寸

Timeout | 201 | 处理超时 | 调整检测设置以缩短处理时间，或延长超时时间

Fail | 299 | 处理失败 | －

 |  |  |
