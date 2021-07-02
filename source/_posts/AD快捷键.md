---
title: AD快捷键
tags: AD
description: 软件AD12 的一些快捷键
top: 24
abbrlink: 5a758763
date: 2020-12-26 20:32:35
---

1：shift+s 键 切换单层显示 
2：q   英寸和毫米 尺寸切换
3：D+R进入布线规则设置。其中 Clearance 是设置最小安全线间距，覆铜时候间距的。比较常用
4：CTRL+鼠标单击某个线，整个线的NET 网络 呈现高亮状态
5：小键盘上的 * （星号键）可以在top、bottom layer 切换，达到快速切换上下层。另外 + - 可以把所有显示的层轮流切换。
6：CTRL+SHIFT+ T 、B、L、R 可以快速对齐所选中的元件 上 下 左 右。
7：M+I 可以把选中所有的元件，翻转过来。这样可以在上下层切换，方便布线，调整印丝层。 很实用的一个操作。
8：如上所述，还可以 查看板子底部，就点击  查看  翻转板子 板子就反过来，但是属性还是 一样。只是从板子底部看了。
9：器件联合 选中两个器件 然后右击 选择 联合-从选中的器件生成联合 这样可以操作两个位置在一起的器件
当要去掉时候 选中器件 右击 联合-从联合打散器件  那么连接在一起的就能够单独操作了。
当选中联合的器件，右击选择联合，有个 选择所有的联合 这样一下子选择所有联合的器件。固定的外框就可以联合起来移动操作。
10：多根线同时画的时候，每个先画个短的线，按SHIFT 选中所有一起画的线，选好，松开SHIFT. 鼠标移动到线头 白点处，然后拖动，那么所有线就一起拖动。 转弯一次，松开， 在拖，又可以转弯。
11: 快捷键 t c 交叉探针 看到寻找 原理图 和 PCB 的元件位置  选下，然后跑到PCB 就能看到原理图那个元件的位置。
12: ed 删线 
13: 捕获焊盘 查看——网格——切换电气网格（shift + E）

方格与格点的切换:View-Grids-ToggleVisible Grid Kind

原点：Edit-Origin-Set
边界的定义：Keep Out Layer-Utility Tools-Place Line 按TAB可定义线宽
选取元件：PCB-PCB Filter-IS Component
逐个放置元件：TOOLS-Component Placement-RepositionSelected Components
自动布局：ToolS-Component Placement--Arrange Within Room
自动布局器：ToolS-Component Placement--Auto Placer
元件排列：选中元件右键Align-  或Alignment Tools--

元件在层之间的快速切换：拖动元件的过程按L键
让焊盘放在格点上：选中元件，右键-Component Actions-Move ComponentOrigin To Grid
移动元件的远近："G"键 选择mil
刷新屏幕： END
改走线模式：shift+空格键
（“45°线性” “45°+圆角” “90°”“ 任意角”“90°+圆弧 ”“圆弧”）
遇障碍物：右键-Options-Preferences-...
推挤： Shift+R
布线快捷菜单：“~ ”键
线宽设置：“Shift+W”

过孔修改规则:Design-Rules-HoleSize;
板边5mm圆弧:Place-KeepOut-Arc
切换英美单位制度：Ctrl+Q 

保护元器件位置：锁定 双击-Lock打钩
保护已锁定物体：Tools-Preference-PCB Editer-General-ProtectLocked Objects 打勾；

显示布线快捷菜单：键盘左上角快捷键“~ ”

层间切换："+""-"

字体（条形码）放置："A"-Place String；
对板的定义：Designers-Board Shape-R/D；
尺寸标注：Place Dimension-Place Linear Dimension
工具栏恢复原始状态:在工具栏处右键CustomizingPCB Editor-Toolbar-Restore；
填充：Place Fill；

 

 

复制粘贴：选中-Edit-Rubber Stamp-单击
粘贴特殊形状：选中-Edit-Paste Special
选择一组Select：“S键”-Touching Liner线/Rectangle矩形
或Shift 一个个选
移动Move:"M"
整体移动：选中-右键-Unions-Create Union fromselected object/break
解脱从联合体
弱小信号线包地：选中-“s”select net,Tool-Outline-Selected Objects
查找相似物体：右键-Find SimilarObject

 

 

测距离：Report-Measure Distance
自动布线:Auto Route:Net/NetClass/Connection/Area/Room

查看布线层：Shift+F或“*”切换层
切断线：Edit-Slice Tracks
布完线进行规则检查：Tools-Design Rule Check-Run D_R_C_
3D视图：数字键“3”或View-Switch to3D,Shift+右键旋转；

铺铜：Place-Polyon Pour

去死铜：**双击铜区，Remove Deader Copper 打勾**

原理图和PCB的双向同步更新：
检测PCB与原理图的不同处：Project-Show Differences
在原理图里更改后更新到PCB:Design-Update PCB Document in
在PCB里更改后更新到原理图:Design-UpdateSchematics in
标号Designator显示：PCB FilterISDesignator 然后PCB Inspector Hide
重新标注：Tool- Re Annotate

元器件标号自动排列：选中器件-右键-Align-Position Component Text
补泪滴：Tool-Teardrops，焊盘与导线连接更牢固
生成生产制造文件：File-Fabrication Outputs
生成PDF文件：File-Smart PDF
翻板：View-Flip Board

**打开层对话框：****L**

打开选择：S
跳转：J 
英寸和毫米切换：Q 
翻转元器件：空格 
改变线宽，孔径：选中导线或过孔,同时按下Tab键
选中目标：shift+单击

PCB换层并自动添加过孔：小键盘上的“*”
系统设置：DXP->preferences 
其中General--Use localized resources中文
其中Backup ：设置备份时间
树形图标：home
快捷键：右下角help-shortcuts
默认布局：View-Desktop layouts--Default
窗口缩回的速度：DXP->preferences->system->view--Hidedelay
打开不同面板：右下角System等等
切换不同窗口：ctrl+tab
放大和缩小：ctrl+鼠标中键滚轴
修改右下方的边框(title，日期)格式：DeSign-Template-Set Template File Name...A4 

**走线自动延长：** **Drag---ctrl+鼠标拖动**

复制目标：选择目标，按住shift拖动
自动添加元件编号：Tools->Annotate Schematics
Preferences-->Schematic-->Graphical Editing Convert Special Strings 转换特殊字符串

如何全局修改
例如：单击电容C1选中，鼠标右键选择Find Similar Objects (Select Matching 选中，二步骤可以跳过

(1) Part Comment ---same Current Footprint ---same ,点击OK按钮
(2) Select ALL
(3) SCH Inspector 窗口 修改 Footprint
Tools-->FootPrint Manager

分层设计

(1)一种水平设置，N个分图 ，net设置全局(project-->project options-->http://www.wenkuxiazai.comIdentifier Scope..Gloal) 不推荐
(2)一种垂直设置

，一个总图(Sheet Entry),N个分图(PORT) 连接只能Sheet Entry到PORT
第二种方法：
(1)Place sheet Symbol(方框) 和sheet Entry(放在方框边界内侧)
(2)选择sheet Symbol，右键选择"Sheetsymbol actions"--creat sheet from symbol
原理图库
(1) File-->New-->Library-->sch..
(2) 右边下方SCH打开SCH Library

窗口
(3) Place->RecTangle,注意放在原点
(4) Library Components Properties
Designator U?
Comment max232
Symbol Refernece max234
(5) 可将一个元件库分为两个Part,例如parta,partb(通过Tools-->new part)
特殊用途：选择该元件，按F1打开该元件的pdf文档
Library Components Properties-->Parameters for Component -->Add..
Name: HelpURL Value: C:\zy\abc.pdf#page=5

PCB库

(1) File-->New-->Library-->pcb..
(2) 右边下方PCB打开pcb Library 窗口
**集成库**

(1) File-->New-->Project-->Interger Library
(2) 新建sch.lib和pcb.lib, 在sch.lib中选择Tools-->Model Manage....
(3) Project-->Compile Integrated Library
盲孔（BIINDVIA）：从印制板内仅延展到一个表层的导通孔。
埋孔（BURIEDVIA）：未延伸到印制板表面的一种导通孔。

PCB绘制

(1) 在PCB中 Design-->ImportChanges From.....
(2) S+N 选择相同net的线
(3) Design-->Board layers & color-->show/hide polygons hide (将覆铜隐藏) （L快捷键）
(4) 查看PCB元件，通过打开PCB窗口，选择Components
(5) shift+S 单层打开或关闭
(6) 对弱小信号可选择包地处理(Tools-->Outline Selected Object)
(7) Tools-->Design Rule Check...
(8) File-->Fabrication Outputs-->Gerber Files 

**覆铜：**

place-->polygon Pour...
\1. Pour Over Same Net Polygons Only 相同net铜箔覆盖
\2. Pour Over All Same Net Objects 铜箔覆盖相同net部分（将相同net的导线等等融合了)
注意 ：如果要保存为PCB4.0 Binary File(*.pcb), 覆铜要选择网格式，(可将网格Track With和GridSize设置一样，就如同Solid格式了)
如何隐藏所有Designator(即u1,r1,r2....)
(1) PCB filer-->IsDesignator 选择所有Designator
(2) PCB Inspector-->Hide
如何将Designator(即u1,r1,r2....)自动放置在元件附件
(1) PCB filer-->IsComponent
(2) Align-->Position Component Text....
将PCB翻转 查看反面方便 view-->FilpBoard
PCB查看层数 Design-->Layer Stack Manager
"类" Design-->class
比如新建一个net class ,把Vc3.3 VC5等加入，然后在rule中选择Net class,这样规则适用范围就是自己定义的类了
按键2--2D 按键3--3D

原理图画线：P+W

PCB图画线： P+T
在原理图里同快速查找元器件：CTRL+F
在PCB里面快速查的元件：J+C 

 

 选择net： ctr+H或S+N
去掉全部选中物体：E+E+A 
 删除两个焊点间的导线：T+U+C

单层打开或关闭：shift+S 

去掉过滤：shift+C 

 在交互布线的过程中，切换布线形状：Shift+空格键

 拖动时连线跟着延长：ctrl+鼠标左键拖动

 PCB选择相同net，并高亮：ctrl+鼠标右键

 hide/show层：ctrl+D

**原理图和PCB快速切换：****ctrl+crosspobe**

 分图和总图的切换：ctrl+上下箭头
 测量距离：ctrl+M
放弃上一步操作：Backspace键

**一、PCB中常用快捷键**

 

- R+L 输出PCB中所有网络的布线长度
- Ctrl+左键点击对正在布的线完成自动布线连接
- M+G 可更改铜的形状;
- 按P+T在布线状态下，按Shift+A可直接进行蛇线走线
- T+R对已布完的线进行蛇线布线
- E++M+C点击空白出可迅速找到PCB上想要的元件
- Backspace 撤销正在布线的上一步操作
- \* 切换布线层，可在布线过程中放置过孔
- Ctrl+Shift 切换层并放置过孔
- F8/E+O+S设置圆心点
- M+I 翻转选中的元件
- P+T 布线
- T+E 补泪滴
- P+G 铺铜
- S+Y 单层选择线
- E+B 选择进行复制

 

**二、以下来源郑振宇老师学生总结：**

![640?wx_fmt=jpeg](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9tbWJpei5xcGljLmNuL21tYml6X2pwZy9IbGlicTVBN1o2dFBTajlqdTdSajQwbmlibk44Q3NLTk9qRFdYM01HdFBJZWswOFRtaHlqNEF6bkh3VWM3SHg2TkFTM0RCaFNwN3F4aWNSUVZvd0JRYWRpYXcvNjQwP3d4X2ZtdD1qcGVn)

![640?wx_fmt=jpeg](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9tbWJpei5xcGljLmNuL21tYml6X2pwZy9IbGlicTVBN1o2dFBTajlqdTdSajQwbmlibk44Q3NLTk9qNUxhdlhUS09YOHo3UEFlRnVxQjlZQTdkZExmd1RzR3VCRFFLMWNwWWliR2ljVTZ0bmx2VHA0V2cvNjQwP3d4X2ZtdD1qcGVn)

![640?wx_fmt=jpeg](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9tbWJpei5xcGljLmNuL21tYml6X2pwZy9IbGlicTVBN1o2dFBTajlqdTdSajQwbmlibk44Q3NLTk9qVkdpYUJuZ2FKMU9VYXZ5TXZNTFhLSUU5aWJjUE5qbklZd2h4N0RtbUl0c3d5VHl3VkQwcGg0VlEvNjQwP3d4X2ZtdD1qcGVn)


**三、BGA 扇出注意事项**

 

![640?wx_fmt=png](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9tbWJpei5xcGljLmNuL21tYml6X3BuZy9IbGlicTVBN1o2dFBTajlqdTdSajQwbmlibk44Q3NLTk9qMWdkdDd2OWdPZmNqVDBSc3NsRmpKa2ljaWE5Y01nQTVKOUludWRCcUtpYmtOR0ZRZnV5RFB2RlRnLzY0MD93eF9mbXQ9cG5n)


**四、常见的单位换算**

 

![640?wx_fmt=png](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9tbWJpei5xcGljLmNuL21tYml6X3BuZy9IbGlicTVBN1o2dFBTajlqdTdSajQwbmlibk44Q3NLTk9qNmlhRjFTaWNBQzVuWEY1OGZpYm5nUGNCelhXelgxOWhFaWN6eUd1S0RoaWNvSkJsMWw2YmhYaWF5Y0RRLzY0MD93eF9mbXQ9cG5n)

![640?](https://imgconvert.csdnimg.cn/aHR0cDovL21tYml6LnFwaWMuY24vbW1iaXovNnptOEZxekU3UncxSFNRUTNpY2RpYWNDcEVpY2dselNUWUpBcmdqdnRVbGV3OTNJemlhZTZIcklDeldjV05ZVWZVQzhPWFZFT1Z2b2paZFpTWmliT2w3ZGU4QS82NDA_)

图文转自https://blog.csdn.net/woshiyuzhoushizhe/article/details/97000298，仅供参考