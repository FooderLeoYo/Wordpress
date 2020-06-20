# Divi

## 目录

[安装](#jump1)

[Divi Builder](#jump2)

[使用前的一些设置](#jump3)

[一些基础操作](#jump4)

[复用](#jump5)

[适配不同终端](#jump6)

[Header相关](#jump7)

[Body相关](#jump8)

---	

<span id="jump1"></span>

## 安装

确保安装包是.zip

在theme添加即可

---

<span id="jump2"></span>

## Divi Builder

### 开启

1. Dashboard/Divi/Theme Options/Builder中，按需要ENABLE相关选项

2. Dashboard/Divi/Theme Customier/Homepage Settings/YOUR HOMEPAGE DISPLAYS选 A static page

3. 进入前台，会发现多了Enable Visual Builder按钮，点击即可开始

---	

<span id="jump3"></span>

## 使用前的一些设置

1. /Divi/Theme Options/General，DISABLE以下功能：

	1. Fixed Navigation Bar

	2. Enqueue Google Maps Script

	3. Use Google Fonts

	4. Show Facebook Icon

	5. Show Twitter Icon

	6. Show Google+ Icon

	7. Show Instagram Icon

	8. Show RSS Icon

2. /Divi/Theme Options/General，ENABLE以下功能：

	1. Back To Top Button

	2. Smooth Scrolling

---

<span id="jump4"></span>

## 一些基础操作

1. 改变row的布局：鼠标停留在目标row，选择蓝绿色框的第四个栅栏形的选项

---

<span id="jump5"></span>

## 复用

### 复用module样式

1. 右键某个Module，选中copy module style

2. 右键目标Module，选中paste module style

3. 还可以将某个Module的样式复用到全局，右键某个Module，选中extend xx style

### 复用Design样式

1. 在某个块或module的设置中，右键选择Copy xx Styles

2. 在需要复用的地方，右键选择Paste xx Styles

### 将某种颜色全部替换成另一种

1. 进入目标块或module的设置

2. 在Backgroud下的颜色区域右键，选Find & Relace

---

<span id="jump6"></span>

## 适配不同终端

### 调整在不同终端的大小

1. 进入目标块或module的设置

2. /Design下的选项的子选项，鼠标停留在某个子选项右边后，会出现一排图表选项

3. 选择手机图标，就可以分别调整在桌面，平板，手机时的大小

### 在某终端下隐藏指定部分

1. 进入目标块或module的设置

2. /Advance/Visibility/Disable on，可以选择在哪种终端下需要隐藏

### 同一个区域在不同终端下显示不同内容

例如想在桌面下显示A，平板、手机下显示B：

1. 复制目标区域A，得到一个新的区域B，修改B的样式

2. 进入A的设置，/Advance/Visibility/Disable on，选中平板、手机

3. 进入B的设置，/Advance/Visibility/Disable on，选中桌面

---

<span id="jump7"></span>

## Header相关

### 自定义Menu

1. 新建一个Row，选一列布局

2. 输入Menu中的文字，然后选中文字，添加超链接，链接到目标url

### 吸顶

1. 进入目标块的设置

2. /Advance/Costom CSS/Main Element中添加：

```css
position: fixed;
top: 0;
left: 0;
right: 0;
```

3. 修改z-index，保证其处于最上层

---

<span id="jump8"></span>

## Body相关

### 用divider做各种形状的区域边界

1. /Section Settings/Design/Dividers/Divider Style中，可选形状

2. 颜色选白色还可以起到削边的效果
