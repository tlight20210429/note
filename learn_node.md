# 1.工具使用篇

## 1.1typora使用教程

### 1.1.1快速开始

#### 1.1.1.1打开面板

打开面板使用快捷键Ctrl+P或者单击菜单栏文件>“快速打开”，在面板中可以查找当前文件夹中的文件

#### 1.1.1.2导入导出

typora可以将文件导出为PDF, HTML等文件格式。单击菜单栏>文件>导出>...

### 1.1.2使用手册

#### 1.1.2.1标题

创建标题使用#+空格+内容，连续1~6个#号代表1~6级标题，或者直接使用快捷键Ctrl+1~6

#### 1.1.2.2引用文字

Markdown使用>字符生成块

#### 1.1.2.3列表

输入*或者+或者-然后+空格可以生成一个无序列表，输入1.+空格可以生成一个有序列表

#### 1.1.2.4任务列表

输入- [ ]+空格可以生成一个带复选框的任务列表

#### 1.1.2.5代码块

输入```+回车可以生成一个代码块，可以编写代码

#### 1.1.2.6数学公式块

输入$$+回车可以生成一个Tex/LaTex源代码的输入区域，用来编写数学公式

#### 1.1.2.7表格

输入| First Header | Second Header |+回车可以生成一个包含2列的表格

#### 1.1.2.8水平线

输入***或者---+回车可以生成一条水平线

#### 1.1.2.9目录(TOC)

输入[toc]+回车可以自动从文档中提取所有标题

#### 1.1.3.0连接

Markdown支持两种类型的链接：内联和引用，链接文本写在[]内。

要创建内联链接，请在链接文本的结束方括号后立即使用一组圆括号并在圆括号内放URL地址以及可选的用引号括起来的链接标题。

将圆括号内的href设置为文档内的标题，可以链接到文档内对应标题处

#### 1.1.3.1斜体、粗体

Ctrl+i设置字体为斜体，Ctrl+b设置字体为粗体

#### 1.1.3.2上标

要使用此功能，首先，请在 `偏好设置` 面板 -> `Markdown扩展语法` 选项卡中启用它。然后用 `^` 来包裹上标内容，例如： `X^2^`。

#### 1.1.3.3下标

要使用此功能，首先，请在 `偏好设置` 面板 -> `Markdown扩展语法` 选项卡中启用它。然后用 `^` 来包裹上标内容，例如： `X^2^`。

#### 1.1.3.4高亮

要使用此功能，首先，请在 `偏好设置` 面板 -> `Markdown扩展语法` 选项卡中启用它。然后用 `==` 来包裹高亮内容，例如： `==highlight==`。

#### 1.1.3.5HTML

您可以使用HTML来设置纯 Markdown 不支持的内容，例如， `<span style="color:red">this text is red</span>` 用于添加红色文本。

#### 1.1.3.6视频

您可以使用 `<video>` HTML标记嵌入视频，例如：

```Markdown
<video src="xxx.mp4" />
```

## 1.2latex学习笔记

### 1.2.1Latex字体设置

正常字体：\mathnormal{A}--->A

罗马字体：\mathrm{A}--->A

斜体：\mathit{A}--->A

黑粗体：\mathbf{A}--->A

黑板体(空心体)：\mathbb{A}--->A

书法艺术体：\mathcal{A}--->A

书写体：\mathscr{A}--->A

更多字体可以参考 [链接](https://blog.csdn.net/wzz110011/article/details/124753129 "Latex字体设置")

### 1.2.2Latex常用符号

#### 1.2.2.1操作符

| Symbol       | Command          | Symbol | Command | Symbol | Command |
| ------------ | ---------------- | ------ | ------- | ------ | ------- |
| ±            | \pm              | ∓      | \mp     | ×      | \times  |
| ÷            | \div             |        |         |        |         |
| ⋆            | \star            |        |         |        |         |
| ⨿            | \amalg           |        |         |        |         |
| ⊎            | \uplus           |        |         |        |         |
| ∨            | \vee             |        |         |        |         |
| ⊖            | \ominus          |        |         |        |         |
| ∙            | \bullet          |        |         |        |         |
| ⊳            | \rhd             |        |         |        |         |
| ⊘            | \oslash          |        |         |        |         |
| ◃            | \triangleleft    |        |         |        |         |
| ▽            | \bigtriangledown |        |         |        |         |
| $\setminus $ | \setminus        |        |         |        |         |
| *x*∘         | x^{\circ}        |        |         |        |         |
| *a**x*       | a^x              |        |         |        |         |

更多符号参考[链接](https://blog.csdn.net/LCCFlccf/article/details/89643585)

# 2.高等数学

## 2.1映射

### 2.1.1映射概念

设X,Y是两个非空集合，如果存在一个法则f,使得X中每个元素x按法则f，在Y中有唯一确定得元素y与之对应，那么称f为从X到Y的映射。记作：
$$
f: \mathbf{X}\rightarrow\mathbf{Y},
$$
其中y称为元素x在映射f下的**像**，记作f(x),即：
$$
y = f(x),
$$
而元素x称为元素y在映射f下的一个**原像;**集合X称为f的**定义域**，记作:
$$
\mathbf{D}_f
$$
X中所有元素的像组成的集合称为f的**值域**，记作：
$$
\mathbf{R}_f 或者f(X)
$$
即：
$$
\mathbf{R}_f = f(X) = \begin{vmatrix}
f(x)\mid x \in \mathbf{X}
\end{vmatrix},
$$

### 2.1.2函数单调性

设函数f(x)的定义域为D,区间
$$
\mathbf{I} \subset \mathbf{D}
$$
如果对于区间I上的任意两点x1及x2，当x1<x2时，恒有
$$
f(x_1) < f(x_2),
$$
那么称f(x)在区间I上单调递增。

如果对于区间I上的任意两点x1及x2，当x1>x2时，恒有
$$
f(x_1) < f(x_2),
$$
那么称f(x)在区间I上单调递减。

### 2.1.3函数奇偶性

设函数f(x)的定义域D关于原点对称，如果对任一
$$
x \in D, f(-x) = f(x)
$$
称函数为偶函数。

如果对任一
$$
x \in D, f(-x) = -f(x)
$$
称函数为奇函数。

偶函数图形关于y轴对称，奇函数图形关于原点对称。

### 2.1.4函数周期性

设函数f(x)的定义域为D，如果存在一个正数l，使得任一
$$
x \in D 有 (x+l) \in D，且 f(x+l) = f(x)
$$
恒成立，称f(x)为周期函数，l称为f(x)的周期。

### 2.1.5初等函数

1.幂函数：
$$
y=x^\mu,(\mu \in R是常数)
$$
2.指数函数：
$$
y = a^x,(a > 0 且 a \neq 1)
$$
3.对数函数：
$$
y = log_ax, (a > 0 且 a \neq 1, 特别当 a=e时,记为y=lnx)
$$
4.三角函数：
$$
y=sinx,\\
y=cosx,\\
y=tanx,等
$$
5.反三角函数：
$$
y=arcsinx,\\
y=arccosx,\\
y=arctanx，等
$$
以上5类函数统称为基本初等函数。

### 2.1.6双曲函数

1.双曲正弦：
$$
shx = \frac{e^x - e ^{-x}}{2},(x \in (-\infty, +\infty))
$$
2.双曲余弦：
$$
chx = \frac{e^x + e^{-x}}{2}, (x \in (-\infty, +\infty))
$$
3.双曲正切：
$$
thx = \frac{shx}{chx}=\frac{e^x - e^{-x}}{e^x + e^{-x}},(x \in (-\infty, +\infty))
$$
双曲图形如下图所示：

![image-20220522102832623](image-20220522102832623.png)
$$
shx是奇函数，通过原点并关于原点对称，在定义域内单调递增，当x趋于正无穷大\\时,shx靠近y=\frac{1}{2}e^x,当x趋于负无穷大时shx靠近y=-\frac{1}{2}e^{-x}。\\chx是偶函数，通过点(0,1)关于y轴对称，当x趋于正无穷大时chx靠近y=\frac{1}{2}e^x\\,当x趋于负无穷大时,chx靠近y=\frac{1}{2}e^{-x}。\\
thx是奇函数，通过原点并关于原点对称，在定义域内单调递增，当x趋于正无穷大\\时,thx靠近y=1,当x趋于负无穷大时,thx靠近y=-1
$$
双曲线4个公式：
$$
sh(x+y) = shxchy+chxshy,\\
sh(x-y) = shxchy-chxshy,\\
ch(x+y) = chxchy+shxshy,\\
ch(x-y) = chxchy-shxshy,
$$
反双曲与反三角函数类似：

反双曲正弦：
$$
y=arshx=ln(x+\sqrt{x^2 + 1}), (x \in (-\infty, +\infty))
$$
反双曲正弦图形：

![image-20220522110604194](image-20220522110604194.png)

反双曲余弦：
$$
y = archx = ln(x+\sqrt{x^2-1}), (x \in [1, +\infty))
$$
反双曲正切：
$$
y=arthx = \frac{1}{2}ln\frac{1+x}{1-x}, (x \in (-1, 1))
$$
反双曲余弦，反双曲正切函数图形：

![image-20220522110440404](image-20220522110440404.png)

### 2.1.7数列极限

定义：设 \{Xn\}为一数列，如果存在常数a，对于任意给定的正数
$$
\varepsilon
$$
(不论它多么小)，总存在正整数N，使得n>N时，不等式
$$
\mid x_n - a \mid < \varepsilon
$$
都成立，那么就称常数a是数列\{x_n\}的极限，或者称数列收敛于a，记为
lim Xn = a,

### 2.1.8夹逼准则

数列{Xn},{yn},{Zn}满足下列条件：

(1)从某项起,当n > n0时，有
$$
y_n \le x_n \le z_n;
$$
(2)
$$
limy_n = a, limz_n = a, n\rightarrow\infty
$$
那么：
$$
limx_n = a，n\rightarrow\infty
$$
两个重要极限：
$$
lim sinx/x = 0, x\rightarrow\infty,\\
lim(1+1/x)^x = e, x\rightarrow\infty,\\
lim sinx/x = 1, x\rightarrow0,
$$

### 2.1.9导数

#### 2.1.9.1导数定义

设函数y=f(x)在点x0的某个邻域内有定义，当x在x0处取得增量△x(x0+△X扔在该邻域内)时，△y=f(x0+△x)-f(x0)，如果△y域△x之比当△x→0时极限存在，那么称函数y=f(x)在点x0处可导，并称这个极限为函数y=f(x)在点x0处的导数，记为：
$$
f'(x0) = \frac{dy}{dx}\mid x=x0,\\
函数在点x_0可导的充分必要条件是点x_0的左导数f'_-(x_0)与右导数f'_+(x_0)都存在，且f'_-(x_0)=f'_+(x_0)
$$

#### 2.1.9.2常规函数导数

$$
f(x)=C,(C是常数)，f'(x) = 0,\\
f(x)=x^n,(n \in N_+), f'(x)=nx^{n-1},\\
f(x)=sinx, f'(x)=cosx,\\
f(x)=cosx, f'(x)=-sinx,\\
f(x)=a^x,(a>0且a\neq1),f'(x)=a^xlna,当a=e时，f'(x)=e^x,\\
f(x)=log_ax,(a>0且a\neq1),f'(x)=\frac{1}{xlna},当a=e时,f'(x)=\frac{1}{x},
$$

#### 2.1.9.3导数的几何意义

![image-20220522120442616](image-20220522120442616.png)

导数表现为在曲线y=f(x)上任意点M(x0, y0)的切线斜率，过点M并与切线MT垂直的直线称为M点的法线
$$
法线的斜率为：-\frac{1}{f'(x0)},
法线方程为：y-y0 = -\frac{1}{f'(x_0)}(x-x_0).
$$
**如果切线水平或者垂直，那么函数不可导**

#### 2.1.9.4函数求导法则

1.常数和基本初等函数的导数公式：
$$
(1) (C)' = 0,\quad(2)(x^\mu)'=\mu x^{\mu-1},\\
(3)(sinx)'=cosx,\quad (4)(cosx)'=-sinx,\\
(5)(tanx)'=sec^2x,\quad (6)(cotx)'=-csc^2x,\\
(7)(secx)'=secxtanx,\quad (8)(cscx)'=-scsxcotx,\\
(9)(a^x)'=a^xlna\quad (a>0, a \neq 1),\quad (10)(e^x)'=e^x,\\
(11)(log_ax)'=\frac{1}{xlna}\quad (a>0,a \neq 1),\quad (12)(lnx)'=\frac{1}{x},\\
(13)(arcsinx)'=\frac{1}{\sqrt{1-x^2}},\quad (14)(arccosx)'=-\frac{1}{\sqrt{1-x^2}},\\
(15)(arctanx)'=\frac{1}{1+x^2},\quad (16)(arccotx)'=-\frac{1}{1+x^2}.
$$
2.函数的和，差，积，商的求导法则
$$
(1)(u \pm v)'=u'\pm v', \quad (2)(Cu)'=Cu'\quad(C是常数).\\
(3)(uv)'=u'v+uv',\quad (4)(\frac{u}{v})'=\frac{u'v - uv'}{v^2}\quad (v \neq 0).
$$

3.反函数求导法则
$$
设x=f(y)在区间I_y内单调，可导且f'(y) \neq 0,则它的反函数y=f^{-1}(x)在I_x=f(I_y)内也可导，且\\
[f^{-1}(x)]'=\frac{1}{f'(y)}\quad 或 \quad \frac{dy}{dx}=\frac{1}{\frac{dx}{dy}}
$$
4.复合函数求导法则
$$
设y=f(u),而u=g(x)且f(u)及g(x)都可导，则复合函数y=f[g(x)]的导数为\\
\frac{dy}{dx}=\frac{dy}{du}\bullet\frac{du}{dx}\quad 或 \quad y'(x)=f'(u)\bullet g'(x).
$$

#### 2.1.9.5高阶导数

变速直线运动的速度v(t)是位置函数s(t)对时间t的导数，即
$$
v=\frac{ds}{dt}\quad 或 \quad v=s'
$$
加速度是速度v对时间t的导数，即
$$
a=\frac{dv}{dt}=\frac{d}{dt}(\frac{ds}{dt})\quad 或 \quad a=(s')'
$$
速度v是s对t的二阶导数，记作
$$
y''=(y')' \quad 或 \quad \frac{d^2y}{dx^2}=\frac{d}{dx}(\frac{dy}{dx})
$$
二阶以及二阶以上的导数称为高阶导数。

#### 2.1.9.6隐函数求导

定义：一般地，如果变量x和y满足一个方程F(x, y) = 0，在一定条件下，当x取某区间内的任一值时，相应地总有满足这方程的唯一的y值存在，那么就说方程F(x, y)=0在该区间内确定了一个隐函数。
$$
例1，求方程e^y+xy-e=0所确定的隐函数的导数\frac{dy}{dx}.\\
解：\\
方程左边对x求导得\quad \frac{d}{dx}(e^y+xy-e)=e^y\frac{dy}{dx}+y+x\frac{dy}{dx},\\
方程右边对x求导得\quad (0)'=0,\\
方程两边对x求导相等，所以\\
e^y\frac{dy}{dx}+y+x\frac{dy}{dx}=0,\\
从而\\
\frac{dy}{dx}=-\frac{y}{x+e^y}
$$

#### 2.1.9.7微分定义

假设一金属片边长为x0,由于受热变成x0+△x，那么金属片面积变化量是△y=(x0+△x)² - x0² = 2x0△x+△x²。由于△x²是比△x高阶的无穷小，所以当△x很小时，面积变化可由2x0△x代替。

设函数y=f(x)在某区间内有定义，x0及x0+△x在这区间内，如果函数的增量△y=f(x0+△x)-f(x0)，可表示为△y=A△x+o(△x).其中A是不依赖△x的常数，那么称函数y=f(x)在点x0是可微的，而A△x叫做函数y=f(x)在点x0相应于自变量增量△x的微分，记作dy，即dy=A△x。

# 3.STM32F429学习笔记

## 3.1Doxygen注释规范

doxygen是解析源文件和生成文档的主要程序。详细使用方法可以参见[Doxygen usage](https://link.zhihu.com/?target=http%3A//doxygen.nl/manual/doxygen_usage.html) 。原文：[http://doxygen.nl/manual](https://link.zhihu.com/?target=http%3A//doxygen.nl/manual)

### 3.1.1注释块描述方法

1.使用带两个*开头的javadoc风格

```java
/**
 * ... text ...
 */
```

2.使用*!开头的Qt风格

```c++
/*!
 * ... text ...
 */
```

3.至少用两行C++注释开始，每行以额外的/或!开头并且注释末尾是一个空行

```C++
///
/// ... text ...
///
```

or

```C++
//!
//!... text ...
//!
```

4.如果要使注释块在文档中更明显，可以使用一下方法

```C++
/********************************************//**
 *  ... text
 ***********************************************/
```

or

```C++
/////////////////////////////////////////////////
/// ... text ...
/////////////////////////////////////////////////
```

or

```C++
/************************************************
 *  ... text
 ***********************************************/
```

以上是注释块详细描述方法，以下是注释块简短描述方法

5.使用\brief命令，该命令以段落结束，所以详细描述以一个空行开始，例如：

```C++
/*! \brief Brief description.
 *         Brief description continued.
 *
 *  Detailed description starts here.
 */
```

6.如果配置文件里的JAVADOC_AUTOBRIEF被设置成YES，这会使用javadoc风格注释块自动开始一个brief并且以空格或新行后的第一个点结束，例如：

```java
/** Brief description which ends at this dot. Details follow
 *  here.
 */
```

```C++
/// Brief description which ends at this dot. Details follow
/// here.
```

7.使用C++风格，注释不超过1行

```C++
/// Brief description.
/** Detailed description. */
```

or

```c++
//! Brief description.

//! Detailed description
//! starts here.
```

8.将注释放在变量之后需要添加一个<标记，例如

```java
int var; /*!< Detailed description after the member */
```

or

```c++
int var; /**< Detailed description after the member */
```

or

```c++
int var; //!< Detailed description after the member
         //!<
```

or

```c++
int var; ///< Detailed description after the member
         ///<
```

对于函数用@param命令来标记参数，使用[in],[out],[in, out]来标记参数方向

```c
void foo(int v /**< [in] docs for input parameter v. */);
```

使用注释块例子：

```java
/*! A test class */

 

class Afterdoc_Test

{

  public:

    /** An enum type. 

     \*  The documentation block cannot be put after the enum! 

     */

    enum EnumType

    {

      int EVal1,     /**< enum value 1 */

      int EVal2      /**< enum value 2 */

    };

    void member();   //!< a member function.

    

  protected:

    int value;       /*!< an integer value */

};
```

Qt风格注释块

```c++
//!  A test class. 

/*!

  A more elaborate class description.

*/

 

class QTstyle_Test

{

  public:

 

    //! An enum.

    /*! More detailed enum description. */

    enum TEnum { 

                 TVal1, /*!< Enum value TVal1. */  

                 TVal2, /*!< Enum value TVal2. */  

                 TVal3  /*!< Enum value TVal3. */  

               } 

         //! Enum pointer.

         /*! Details. */

         *enumPtr, 

         //! Enum variable.

         /*! Details. */

         enumVar;  

    

    //! A constructor.

    /*!

      A more elaborate description of the constructor.

    */

    QTstyle_Test();

 

    //! A destructor.

    /*!

      A more elaborate description of the destructor.

    */

   ~QTstyle_Test();

    

    //! A normal member taking two arguments and returning an integer value.

    /*!

      \param a an integer argument.

      \param s a constant character pointer.

      \return The test results

      \sa QTstyle_Test(), ~QTstyle_Test(), testMeToo() and publicVar()

    */

    int testMe(int a,const char *s);

       

    //! A pure virtual member.

    /*!

      \sa testMe()

      \param c1 the first argument.

      \param c2 the second argument.

    */

    virtual void testMeToo(char c1,char c2) = 0;

   

    //! A public variable.

    /*!

      Details.

    */

    int publicVar;

       

    //! A function variable.

    /*!

      Details.

    */

    int (*handler)(int a,int b);

};
```

JAVA风格注释块

```c++
/**

 \*  A test class. A more elaborate class description.

 */

 

class Javadoc_Test

{

  public:

 

    /** 

     \* An enum.

     \* More detailed enum description.

     */

 

    enum TEnum { 

          TVal1, /**< enum value TVal1. */  

          TVal2, /**< enum value TVal2. */  

          TVal3  /**< enum value TVal3. */  

         } 

       *enumPtr, /**< enum pointer. Details. */

       enumVar;  /**< enum variable. Details. */

       

      /**

       \* A constructor.

       \* A more elaborate description of the constructor.

       */

      Javadoc_Test();

 

      /**

       \* A destructor.

       \* A more elaborate description of the destructor.

       */

     ~Javadoc_Test();

    

      /**

       \* a normal member taking two arguments and returning an integer value.

       \* @param a an integer argument.

       \* @param s a constant character pointer.

       \* @see Javadoc_Test()

       \* @see ~Javadoc_Test()

       \* @see testMeToo()

       \* @see publicVar()

       \* @return The test results

       */

       int testMe(int a,const char *s);

       

      /**

       \* A pure virtual member.

       \* @see testMe()

       \* @param c1 the first argument.

       \* @param c2 the second argument.

       */

       virtual void testMeToo(char c1,char c2) = 0;

   

      /** 

       \* a public variable.

       \* Details.

       */

       int publicVar;

       

      /**

       \* a function variable.

       \* Details.

       */

       int (*handler)(int a,int b);

};
```

文档结构命令

\struct 用来代表一个结构体类型

\union 用来代表一个联合体类型

\enum 用来代表一个枚举类型

\fn 用来代表一个函数

\var 用来代表一个变量类型或枚举的值

\def 用来代表一个宏

\typedef 用来代表一个typedef类型

\file 用来代表一个文件

\namespace 用来代表一个命令空间

\package 用来代表一个包

\interface 用来代表一个接口

更过其它结构命令请参考 [Special Commands](https://doxygen.nl/manual/commands.html) 

对于全局对象，你必须记住它们定义的文件

```c
/*! \file */ 
```

or

```c
/** @file */
```

例如：

```C++
/*! \file structcmd.h

    \brief A Documented file.

    

    Details.

*/

 

/*! \def MAX(a,b)

    \brief A macro that returns the maximum of \a a and \a b.

   

    Details.

*/

 

/*! \var typedef unsigned int UINT32

    \brief A type definition for a .

    

    Details.

*/

 

/*! \var int errno

    \brief Contains the last error code.

 

    \warning Not thread safe!

*/

 

/*! \fn int open(const char *pathname,int flags)

    \brief Opens a file descriptor.

 

    \param pathname The name of the descriptor.

    \param flags Opening flags.

*/

 

/*! \fn int close(int fd)

    \brief Closes the file descriptor \a fd.

    \param fd The descriptor to close.

*/

 

/*! \fn size_t write(int fd,const char *buf, size_t count)

    \brief Writes \a count bytes from \a buf to the filedescriptor \a fd.

    \param fd The descriptor to write to.

    \param buf The data buffer to write.

    \param count The number of bytes to write.

*/

 

/*! \fn int read(int fd,char *buf,size_t count)

    \brief Read bytes from a file descriptor.

    \param fd The descriptor to read from.

    \param buf The buffer to read into.

    \param count The number of bytes to read.

*/

 

\#define MAX(a,b) (((a)>(b))?(a):(b))

typedef unsigned int UINT32;

int errno;

int open(const char *,int);

int close(int);

size_t write(int,const char *, size_t);

int read(int,char *,size_t);
```

使用\verbinclude可以阻止doxygen解析文档

```shell
/*! \file myscript.sh
 *  Look at this nice script:
 *  \verbinclude myscript.sh
 */
```

### 3.1.2python注释块

```python
"""@package docstring

Documentation for this module.

 

More details.

"""

 

def func():

    """Documentation for a function.

 

    More details.

    """

    pass

 

class PyClass:

    """Documentation for a class.

 

    More details.

    """

   

    def __init__(self):

        """The constructor."""

        self._memVar = 0;

   

    def PyMethod(self):

        """Documentation for a method."""

        pass
```

```python
## @package pyexample

\#  Documentation for this module.

\#

\#  More details.

 

\## Documentation for a function.

\#

\#  More details.

def func():

​    pass

 

\## Documentation for a class.

\#

\#  More details.

class PyClass:

   

    \## The constructor.

    def __init__(self):

        self._memVar = 0;

   

    \## Documentation for a method.

    \#  @param self The object pointer.

    def PyMethod(self):

        pass

     

    \## A class variable.

    classVar = 0;

 

    \## @var _memVar

    \#  a member variable
```

## 3.2Doxywizard工具使用说明

Doxywizard是一个帮助生成帮助文档的工具，具体使用可参看[中文教程](https://blog.csdn.net/qq_43331089/article/details/124489068)或者[官网教程](https://doxygen.nl/manual/doxywizard_usage.html)

## 3.3sourceinsight使用quicker.em

quicker.em是华为一个员工开发的sourceinsight宏，用来快速生成注释。

1.在GitHub搜[jaytang0923](https://github.com/jaytang0923)/**[sourceinsight_quicker.em](https://github.com/jaytang0923/sourceinsight_quicker.em)**下载

2.将它放入sourceinsight的base工程根目录下。

3.关闭base工程，打开自己的工程，选择菜单Options->Key Assignments，找到autoExpand设置快捷键，一般选择Ctrl+Enter

![image-20220528201547242](image-20220528201547242.png)

4.选择菜单Options->Menu Assignments，找到HeaderFileCreate，Menu选择Work后点击插入，这样就可以在菜单栏看到增加work，点击HeaderFileCreate可以自动添加头文件.

（1）、首先要把这个文件搞到手，然后将其加载到Base工程中，其次要定义一个快捷键调用quiker.em中的宏AutoExpand。quiker.em中写了那么多宏，为什么只调用AutoExpand宏就可以。因为调用AutoExpand宏后，AutoExpand会根据当前文本内容自动调用其他宏。一般情况下都用快捷键ctrl+enter调用AutoExpand宏。

（2）、输入文本config，然后执行AutoExpand，根据提示完成语言、姓名配置。

（3）、输入文本fu，然后执行AutoExpand，根据提示完成函数的注释。（在函数名的上一行执行）

（4）、输入文本if，然后执行AutoExpand，可以自动完成语法。其他类似。

（5）、输入文本file，然后执行AutoExpand，可以自动生成.c文件描述。

（6）、输入文本hdn，然后执行AutoExpand，根据提示完成.h文件宏定义。

（7）、在.c文件里输入hd，然后执行AutoExpand，可以自动生成.c文件对应的头文件。
————————————————
版权声明：本文为CSDN博主「程序员阿周」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/qq_39660930/article/details/77499455

## 3.4sourceinsight宏

### 3.4.1宏函数声明

宏函数必须已macro或者function关键字开头，函数可以带参数，参数不用声明变量类型。

```C
macro HelloWorld()

{

  msg("Hello World!")  // message box appears with  "Hello World"

}
```

or

```c
function add2(n)

{

  return n + 2

}
```

### 3.4.2函数风格

宏函数有三种风格：

1.你可以使用快捷键或者菜单访问宏，但是这种宏一定要以macro关键字声明而且不能有参数

2.用来作为宏调用的函数必须以function关键字开头，例如：

```c
macro SaveCurrentFileNow()
{
	perform_save()
}
function perform_save()
{
	var hbuf
	hbuf = GetCurrentBuf()
	if (hbuf != nil)
		SaveBuf(hbuf)
}
```

3.用来连接到事件的函数必须以event关键字开头

# 4.git学习笔记

## 4.1git简介

git是一个代码管理工具，可以方便查看代码版本和团队合作开发项目。该章节学习内容参考[git手册](https://git-scm.com/)

## 4.2git安装和配置

### 4.2.1git安装

官方下载链接[Git - Downloads (git-scm.com)](https://git-scm.com/downloads)，打开后点击Download for Windows

![image-20220903001752523](E:\databases\note\image-20220903001752523.png)

点击64-bit Git for Windows Setup.下载

![image-20220903001919412](E:\databases\note\image-20220903001919412.png)

下载后双击运行安装就可以。

### 4.2.2git配置

1.git安装后首先要配置用户名和邮箱，右键鼠标运行Git Bash Here，执行命令：

```console
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

2.配置git默认文本编辑器，这里以Notepad++为例。[可选]

执行命令：

```console
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
```

3.检查配置，执行命令：

```console
$ git config --list
```

也可以通过输入 `git config <key>`： 来检查 Git 的某一项配置，例如：

```console
$ git config user.name
```

### 4.2.3git帮助命令

git可以通过以下3种方式获取git命令帮助说明：

```console
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
```

例如想要获取git config命令帮助说明，可以输入

```console
$ git help config
```

如果不想要全面的手册，可以在后面加-h选项。

```console
$ git help config -h
```

## 4.3git基础

### 4.3.1创建git仓库

创建git仓库主要有两种方式。

1.在本地目录执行命令：

```console
$ git init
```

2.从远程库克隆代码：

```console
$ git clone 远程仓库链接
```

### 4.3.2在本地创建git仓库

选择一个文件夹输入`<span style="color:red">git init</span>创建仓库，这里将文件夹命名为learnGit，成功会出现一个.git文件夹，如果没有出现要点击查看->显示->隐藏项目就能看到了。

![image-20220903005736148](E:\databases\note\image-20220903005736148.png)

在learnGit根目录下新建文件readme.txt，然后输入命令 `<span style="color:red">git status</span>查看仓库文件状态。

![image-20220903010139596](E:\databases\note\image-20220903010139596.png)

此时文件名显示为红色，untracked表示文件未被git跟踪，可以输入命令`<span style="color:red">git add readme.txt</span>使该文件被git跟踪。此时再次运行<span style="color:red">git status</span>查看文件状态，发现文件名已变成绿色，说明该文件已被git跟踪

![image-20220903011121989](E:\databases\note\image-20220903011121989.png)

往readme.txt文件随便写入一些内容，再次运行<span style="color:red">git status</span>

发现文件名变成红色并且git提示该文件已被修改，可以使用命令

```console
git add readme.txt
```

将该文件放入暂存区，或者使用命令

```console
git restore readme.txt
```

放弃该文件的修改。

继续执行命令

```console
git add readme.txt
git status
```

文件名变成绿色，说明该文件已放入暂存区。

![image-20220903012239435](E:\databases\note\image-20220903012239435.png)

执行命令

```console
git commit -m "本次提交描述"
```

完成一次提交，再次执行

```console
git status
```

发现工作区已变干净，没有任何修改记录。

![image-20220903012537365](E:\databases\note\image-20220903012537365.png)

执行命令

```console
git log
```

可以查看提交记录

![image-20220903012630721](E:\databases\note\image-20220903012630721.png)

当然有时也可以通过git commit 后面加-a选项跳过git add步骤直接将被跟踪的文件一并提交。

```console
git commit -a readme.txt
```

### 4.3.3git删除文件或取消跟踪

#### 4.3.3.1git删除文件

git删除文件可以使用命令：

```console
git rm filename
```

如果该文件已经添加到暂存区或者已经修改过了需要加-f选项：

```console
git rm -f filename
```

如果希望只是取消git跟踪而保留文件的话需要加--cached选项：

```console
git rm --cached filename
```

删除命令可以使用glob模式，比如：

```console
git rm log/\*.log
```

该命令删除log目录下扩展名为.log的文件。

```console
git rm \*~
```

该命令会删除所有以~结尾的文件。

#### 4.3.3.2git重命名文件或移动文件

git重命名文件或移动文件使用命令：

```console
git mv filename_from filename_to
```

### 4.3.4git更改提交信息

要更改提交信息可以使用命令：

```console
git commit --amend
```

该命令会将暂存区中的文件提交，如果没有则只修改上一次的提交内容。

#### 4.3.4.1取消暂存文件

取消暂存文件使用命令：

```console
git reset HEAD filename
```

#### 4.3.4.2取消工作区文件内容修改

取消工作区文件内容修改可以使用命令：

```console
git restore filename
```

#### 4.3.4.3更改提交信息

1.更改最后一次提交信息方式

```c
git commit --amend
```

该命令输入后进入VIM编辑界面，在该界面修改提交信息，如果已经提交到远程库，可以使用命令：

```
git push origin -f
```

将修改信息强制推送到远程库。

2.

### 4.3.5git忽略文件

git忽略文件可以在和.git同一目录下新建文件.gitignore实现。但是.gitignore只能忽略未被git跟踪的文件，如果文件已被跟踪则需要使用git rm --cached filename取消git跟踪才行。

文件 .gitignore 的格式规范如下： 

• 所有空行或者以 # 开头的行都会被 Git 忽略。 

• 可以使用标准的 glob 模式匹配，它会递归地应用在整个工作区中。 • 匹配模式可以以（/）开头防止递归。 

• 匹配模式可以以（/）结尾指定目录。 

• 要忽略指定模式以外的文件或目录，可以在模式前加上叹号（!）取反。

所谓的 glob 模式是指 shell 所使用的简化了的正则表达式。 

星号（*）匹配零个或多个任意字符；

[abc] 匹配 任何一个列在方括号中的字符 （这个例子要么匹配一个 a，要么匹配一个 b，要么匹配一个 c）； 

问号（?）只 匹配一个任意字符；如果在方括号中使用短划线分隔两个字符， 表示所有在这两个字符范围内的都可以匹配 （比如 [0-9] 表示匹配所有 0 到 9 的数字）。 

使用两个星号（\**）表示匹配任意中间目录，比如 a/**/z 可以 匹配 a/z 、 a/b/z 或 a/b/c/z 等。

比如:

```console
# 忽略所有的 .a 文件
*.a
# 但跟踪所有的 lib.a，即便你在前面忽略了 .a 文件
!lib.a
# 只忽略当前目录下的 TODO 文件，而不忽略 subdir/TODO
/TODO
# 忽略任何目录下名为 build 的文件夹
build/
# 忽略 doc/notes.txt，但不忽略 doc/server/arch.txt
doc/*.txt
# 忽略 doc/ 目录及其所有子目录下的 .pdf 文件
doc/**/*.pdf
#忽略所有以.o或.a结尾的文件
*.[oa]
#忽略所有以~结尾的文件
*~
```

### 4.3.6git取消文件追踪

git取消文件追踪，但不删除文件

```shell
git rm --cached file
```

git取消文件夹追踪，但不删除文件

```shell
git rm -r --cached dir
```

git取消文件追踪并删除本地文件

```shell
git rm --f file
```

GitHub 有一个十分详细的针对数十种项目及语言的 .gitignore 文件列表， 你可以在 https://github.com/github/gitignore 找到它。

### 4.3.6git添加远程库

**1.创建SSH Key。（如果用户主目录已经有.ssh目录，这一步跳过）**

```console
ssh-keygen -t rsa -C "youremail@example.com"
```

运行改命令后一路回车，最终会在主目录下生成一个.ssh目录，该目录的id_rsa和id_rsa.pub就是SSH Key的秘钥对，id_rsa是私钥，不能泄露，id_rsa.pub是公钥。可以告诉别人。

**2.登陆GitHub，打开“settings”，点击SSH and GPG keys，**

**然后，点“New SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容：**

![image-20220904153558831](E:\databases\note\image-20220904153558831.png)

点击Add SSH key

![image-20220904154030328](E:\databases\note\image-20220904154030328.png)

添加完成

![image-20220904154138996](E:\databases\note\image-20220904154138996.png)

**3.点击your repositories, 点击New创建一个新仓库**。

![image-20220904154742389](E:\databases\note\image-20220904154742389.png)

填好仓库信息，点击Create repository创建一个仓库。

![image-20220904155032160](E:\databases\note\image-20220904155032160.png)

**4.执行命令添加远程仓库：**

```console
git remote add origin git@github.com:tlight20210429/learnGit.git
```

添加远程库后执行命令查看远程库，显示远程库已添加

```console
git remote -v
```

![image-20220904155654352](E:\databases\note\image-20220904155654352.png)

**5.添加远程库之后还要拉取远程库分支到本地，拉取远程库到本地有两种方式，分别是git fetch 和 git pull.**

执行命令：

```console
git fetch origin main
```

将远程库origin的main分支抓取到本地，第一次执行该命令会得到一个警告，可以不用管它直接yes就行。

![image-20220904160955702](E:\databases\note\image-20220904160955702.png)

抓取到本地后执行命令：

```console
git branch -a
```

可以看到远程分支已经抓取到本地了

![image-20220904161128973](E:\databases\note\image-20220904161128973.png)

注意此时还不会影响到本地分支的内容，用户需要自己执行命令合并远程分支才行：

```console
git merge FETCH_HEAD
```

如果合并失败提示refusing to merge unrelated histories。那么需要添加合并条件--allow-unrelated-histories

```console
git merge FETCH_HEAD --allow-unrelated-histories
```

git pull命令会将远程分支拉取到本地的同时合并本地分支。

**6.将本地分支推送到远程库执行命令：**

```console
git push origin main
```

将main分支推送到远程库

**7.删除远程库**

删除远程库可以使用命令

```console
git remote rm origin
```

或者

```console
git remote remove origin
```

解决github打开慢方法：



### 4.3.7git打标签

git标签分为两种，分别是轻量标签和附注标签。轻量标签只是某个特定提交的引用；附注标签是存储在Git数据库中的一个完整对象，它是可以被校验的，其中包含打标签者的名字、电子邮件 地址、日期时间， 此外还有一个标签信息，并且可以使用 GNU Privacy Guard （GPG）签名并验证。 通常会建 议创建附注标签，这样你可以拥有以上所有信息。但是如果你只是想用一个临时的标签， 或者因为某些原因不 想要保存这些信息，那么也可以用轻量标签。

创建附注标签：

```console
git tag -a v1.0 -m "my version 1.0"
```

创建轻量标签:

```console
git tag v1.0
```



显示标签命令：

```console
git tag
```

如歌要筛选可以在后面加一个-l选项：

```console
git tag -l "v1.8.5*"
```

此时会显示出所有包含v1.8.5的标签。

对过去的提交打标签

```console
git tag -a v1.1 9cda892e
```

9cda892e是过去某次提交ID的一小部分长度

默认情况git push命令并不会将标签推到远程库，必须显示使用命令

```console
git push origin tagname
```

将标签推到远程库。

如果一次要推很多标签到远程库的话需要添加 --tags命令：

```console
git push origin --tags
```

删除标签

删除标签可以使用命令：

```console
git tag -d tagname
```

默认删除的是本地标签不会影响远程库的标签。如果要把远程库的标签也删除，必须执行命令：

```console
git push origin :refs/tags/tagname
```

或者

```console
git push origin --delete tagname
```

### 4.3.8git分支

1.**查看分支**

查看分支可以使用命令：

```console
git branch
```

2.**创建分支**

创建分支不切换当前分支可以使用命令：

```console
git branch bug
```

上面的命令创建了一个bug分支，如果要创建分支并切换到要创建的分支可以使用命令：

```console
git switch -c test
```

上面命令创建了一个test分支并切换到test分支。

3.**切换分支**

切换分支可以使用命令：

```console
git switch test
```

上面命令切换到test分支。

3.**分支合并**

```console
git merge bug
```

将bug分支合并到当前分支上。当两个分支都修改的相同的部分的内容时，git无法快速合并产生冲突，出现下面的情况：

![image-20220904194533231](E:\databases\note\image-20220904194533231.png)

查看冲突文件里会发现<<<<<<<HEAD 和||||||||bug，其中<<<<<<<HEAD是本分支的内容，||||||||bug是bug分支的内容，需要手动解决分支才行。

![image-20220904195326457](E:\databases\note\image-20220904195326457.png)

这里我们保留bug分支的内容，去掉main分支内容。然后重现提交就可以顺利完成合并了。

![image-20220904195509522](E:\databases\note\image-20220904195509522.png)

![image-20220904195642995](E:\databases\note\image-20220904195642995.png)

然后再执行命令就可以看到合并效果：

```console
git log --graph --pretty=oneline --abbrev-commit
```



4.**分支删除**

```console
git branch -d bug
```

删除bug分支，如果删不掉可以使用将-d改成-D强制删除。

5.**查看分支合并情况**

```console
git log --graph --pretty=oneline --abbrev-commit
```

# 5.Nordic NRF52832学习

## 5.1SDK包目录介绍

以下是nRF5_SDK_15.3.0_59ac345版本SDK包目录：

![image-20220918234451206](E:\databases\note\image-20220918234451206.png)

1.components文件包存放的是各类驱动、蓝牙协议栈、芯片库程序等文件，是后期我们编程所需要的文件，是SDK的核心部分。

2.config文件包提供开发环境以及库函数配置。

3.documentaion是帮助文档，里面提供一个index.html网页引导文件。点开这个文件就可以打开官方对整个SDK支持包的说明网站，说明文档包含了各个函数定义，找到其定义，对于理解nrf5x系列处理器的编程很重要。

4.example文件夹包含了官方提供给开发者的应用实例，通过参考官方的演示实例，便于开发者快速的开发出自己的应用。

![image-20220918235723548](E:\databases\note\image-20220918235723548.png)

802_15_4文件夹提供的nrf52840的802_15_4通信应用实例

ant文件夹提供多个ANT+通信的应用实例

ble_central文件夹提供多个蓝牙BLE主机的应用实例

ble_central_and_peripheral文件夹提供蓝牙主从一体的应用实例

ble_peripheral文件夹提供多个蓝牙BLE从机的应用实例

connectivity文件夹提供蓝牙直接连接方式的几个测试代码

dfu文件夹提供官方dfu的BootLoader工程和dfu的演示实例

dtm文件夹Direct Test Mode，也就是直接连接测试模式的演示实例

multiprotocol文件夹提供混合协议演示实例

nfc文件夹提供nfc的演示实例

peripheral文件夹提供多个外设的应用实例

peripheral_rf文件夹提供2.4G通信下的应用实例

usb_drivers文件夹提供usb驱动设备声明

5.external文件夹提供了一些第三方驱动

6.external_tools文件夹用来放置一些外部工具包，目前该文件夹只包含了CMSIS的配置向导

7.integration文件夹提供老版本驱动兼容头文件

8.modules->nrfx->drivers最新版的驱动文件，modules->nrfx->hal老版本硬件配置头文件

## 5.2蓝牙协议栈结构

以下是BLE协议栈整体架构

![image-20220919001525403](E:\databases\note\image-20220919001525403.png)

1.PHY层，PHY层用来指定BLE所用的无线频段，调制解调方式和方法等。PHY层做得好不好直接影响整个BLE芯片的功耗，灵敏度以及selectivity等射频指标。

2.LL层，LL层是整个BLE协议栈的核心，也是BLE协议栈的难点和重点。像Nordic的BLE协议栈能同时支持20个link(连接)，就是LL层的功劳。LL层要做的事情非常多，比如具体选择哪个射频通道进行通信，怎么识别空中数据包，具体在哪个时间点把数据包发送出去，怎么保证数据的完整性，ACK如何接收，如何进行重传，以及如何对链路进行管理和控制等等。LL层只负责把数据发送出去或者接收回来，对数据进行怎样的解析则交给上面的GAP或者ATT。

3.HCI层，Host controller interface，HCI是可选的，HCI主要用于2颗芯片实现BLE协议栈的场合，用来规范两者之间的通信协议和通信命令等。

4.L2CAP层，L2CAP层对LL层进行了一次简单封装，LL层只关心传输的数据本身，L2CAP就要区分是加密通道还是普通通道，同时还要对连接间隔进行管理。

5.SMP层，SMP层用来管理BLE连接的加密和安全的，如何保证连接的安全性，同时不影响用户的体验，这些都是SMP要考虑的工作。

6.ATT层，ATT层用来定义用户命令及命令操作的数据，比如读取某个数据或者写某个数据，BLE协议栈中，开发者接触最多的就是ATT。BLE引入了attribute概念，用来描述一条一条的数据。Attribute除了定义数据，同时定义该数据可以使用的ATT命令，因此这一层被称为ATT层。

7.GATT层，GATT层用来规范attribute中的数据内容，并运用group的概念对attribute进行分类管理。没有GATT，BLE协议栈也能跑，但互联互通就会出问题。

8.GAP层，GAP层是对LL层payload(有效数据包)如何进行解析的两种方式中的一种，而且是最简单的那一种，GAP简单的对LL payload进行一些规范和定义，因此GAP能实现的功能极其有限。GAP目前主要用来进行广播，扫描和发起连接等。

## 5.3蓝牙实现连接与通信过程

BLE设备只有主机和从机两种角色，发起连接的设备称为主机，被连接的设备称为从机。

### 5.3.1从机广播

从机要想被主机连接，那么它就必须要使用广播将自身信息发射出去。广播包是周期性循环发送的，假如两个广播包间隔时间为t，那么称t为广播间隔，每发送一次广播包称为一次广播事件(advertising event)，因此t也称为广播事件间隔。广播事件是一阵一阵的，每次会有一个持续时间，蓝牙芯片只有在广播事件期间才打开射频模块发射广播，这时功耗比较高，其余时间蓝牙芯片处于idle待机状态，功耗非常低。

![image-20220920001947204](E:\databases\note\image-20220920001947204.png)

当广播发出时，每一个广播事件包含三个广播部，分别在37,38,39三个通道上同时广播相同信息。

![image-20220920002108424](E:\databases\note\image-20220920002108424.png)

### 5.3.2主机扫描

设备不断发送广播信号给主机(Observer)，这时只有主机开启了扫描窗口并且射频接收窗口跟广播发送的发射窗口匹配成功，主机才能收到设备的广播信号。这种匹配成功是一个概率事件，所以主机可能很快就扫描到从机，也可能要一会才能扫描到从机。

![image-20220920002817257](E:\databases\note\image-20220920002817257.png)

控制器收到扫描数据包后将向主机发送一个广播报告事件(adv_report),该事件包含了链路层数据包的广播类型。因此，主机能够判断对端设备是否可以连接或者扫描，并且区分出广播数据包和扫描响应数据包。

### 5.3.3建立连接

主机收到从机广播包A1后，延时T_IFS时间给从机发送connection request命令，即A2数据包，告诉从机我将要过来连接你，请做好准备。从机根据connect_req命令信息做好接收准备。connect_req其实是告诉从机主机将要在Transmit Window期间发送第一个同步包P1给你，请在这段时间里把你的射频接收窗口打开。从机收到P1后延时T_IFS时间给主机回复数据包P2。一旦主机收到数据包P2，连接即可认为建立成功。后续主机将以P1为锚点(原点)，Connection Interval为周期，周期性地给从机发送Packet。

![image-20220920005209072](E:\databases\note\image-20220920005209072.png)

连接成功后，master和slave在每一个connection interval开始的时候，都必须交互一次，即master给slave发送一个包，slave再给master回一个包，整个交互过程称为一个connection event。在connection event期间，master可以发多个包给slave，以提高吞吐率。

![image-20220920005728960](E:\databases\note\image-20220920005728960.png)

主机RX从机TX方向：

通知：从机上传数据给主机，不需要主机回复一个响应。

指示：从机上传数据给主机，需要主机发一个确认给从机。

主机TX从机RX方向：

1.写

2.没有回应的写

3.读

## 5.4串口Log输出配置

### 5.4.1UART打印

1.打开sdk_config.h勾选配置

![image-20220926002747145](E:\databases\note\image-20220926002747145.png)

2.勾选后切换到Text Editor，可以看到UART已使能

![image-20220926003119781](E:\databases\note\image-20220926003119781.png)

3.打开main.c文件，log_init()即为log初始化函数。

![image-20220926003420966](E:\databases\note\image-20220926003420966.png)

4.依次查看NRF_LOG_DEFAULT_BACKENDS_INIT()，nrf_log_backend_uart_init()，uart_init()，最后可以看到串口初始化函数只初始化了一个脚。

![image-20220926003833087](E:\databases\note\image-20220926003833087.png)

5.最后调佣NRF_LOG_INFO()函数就可以使用串口打印数据了。

### 5.4.2RTT打印

1.打开配置文件配置为RTT打印

![image-20220926002747145](E:\databases\note\image-20220926002747145.png)

2.使能之后就可以使用NRF_LOG_INFO()函数打印数据了。

3.打开J-Link RTT Viewer

![image-20220926004454241](E:\databases\note\image-20220926004454241.png)

4.连接好J-Link，配置好参数

![image-20220926004710090](E:\databases\note\image-20220926004710090.png)

5.最终可以看到和串口一样的输出

![image-20220926004930093](E:\databases\note\image-20220926004930093.png)

## 5.5BLE定时器使用

1.声明定时器，定时周期，定时超时回调函数

![image-20221001000338761](E:\databases\note\image-20221001000338761.png)

2.创建定时器

![image-20221001000431010](E:\databases\note\image-20221001000431010.png)

3.启动定时器

![image-20221001000525436](E:\databases\note\image-20221001000525436.png)

4.使用app timer 宏

![image-20221001005323819](E:\databases\note\image-20221001005323819.png)

note：

如果电脑用户名是中文的话，编译将会出错，这时需要将用户名改为英文才可以。如下图所示，编译出来的工程名称后缀带有中文的，说明电脑用户名是中文，需要修改为英文才行。

![image-20221001005811377](E:\databases\note\image-20221001005811377.png)

修改步骤：

1.win+r将输入netplwiz，点击确定

![image-20221001010023838](E:\databases\note\image-20221001010023838.png)

2.在打开的界面输入一个自己想要修改的英文名，比如tlight。

3.打开注册表，双击ProfileImagePath，按下图方式修改

![image-20221001010421465](E:\databases\note\image-20221001010421465.png)

4.重启电脑，将C:\User目录下的Administrator文件夹删掉，将原来的用户名目录改成Administrator，再重启电脑即可。

## 5.6蓝牙协议栈按键配置

1.定义按键数量

![image-20221001160419667](E:\databases\note\image-20221001160419667.png)

2.定义按键ID，注意按键ID不可以大于按键数量

![image-20221001160537074](E:\databases\note\image-20221001160537074.png)

3.定义按键处理事件

![image-20221001160204776](E:\databases\note\image-20221001160204776.png)

4.配置按键动作

![image-20221001160818659](E:\databases\note\image-20221001160818659.png)

![image-20221001160859158](E:\databases\note\image-20221001160859158.png)

5.添加事件处理工作

![image-20221001161004706](E:\databases\note\image-20221001161004706.png)

6.配置按键IO

![image-20221001161525754](E:\databases\note\image-20221001161525754.png)

7.如果要更改按键长按时间，可以修改这里，默认按键长按是1s。

![image-20221001161952327](E:\databases\note\image-20221001161952327.png)

LED部分可以参考类似按键这方面修改，这里不做过多了解。

## 5.7BLE协议栈剖析

### 5.7.1协议栈初始化

![image-20221001163106302](E:\databases\note\image-20221001163106302.png)

1.nrf_sdh_enable_request()函数主要是使能协议栈回复使能应答，配置系统时钟。该函数会向所有使用NRF_SDH_REQUEST_OBSERVER宏注册的observers发出一个NRF_SDH_EVT_ENABLE_REQUEST请求，当所有observers都确认请求后，协议栈将启用。否则，进程会被终止。

```c
ret_code_t nrf_sdh_enable_request(void)
{
    ret_code_t ret_code;

    if (m_nrf_sdh_enabled)
    {
        return NRF_ERROR_INVALID_STATE;
    }

    m_nrf_sdh_continue = true;

    // Notify observers about SoftDevice enable request.
    if (sdh_request_observer_notify(NRF_SDH_EVT_ENABLE_REQUEST) == NRF_ERROR_BUSY)
    {
        // Enable process was stopped.
        return NRF_SUCCESS;
    }

    // Notify observers about starting SoftDevice enable process.
    sdh_state_observer_notify(NRF_SDH_EVT_STATE_ENABLE_PREPARE);
	//配置时钟源
    nrf_clock_lf_cfg_t const clock_lf_cfg =
    {
        .source       = NRF_SDH_CLOCK_LF_SRC,
        .rc_ctiv      = NRF_SDH_CLOCK_LF_RC_CTIV,
        .rc_temp_ctiv = NRF_SDH_CLOCK_LF_RC_TEMP_CTIV,
        .accuracy     = NRF_SDH_CLOCK_LF_ACCURACY
    };

    CRITICAL_REGION_ENTER(); //进入临界区
#ifdef ANT_LICENSE_KEY
    ret_code = sd_softdevice_enable(&clock_lf_cfg, app_error_fault_handler, ANT_LICENSE_KEY);
#else
    ret_code = sd_softdevice_enable(&clock_lf_cfg, app_error_fault_handler);
#endif
    m_nrf_sdh_enabled = (ret_code == NRF_SUCCESS);
    CRITICAL_REGION_EXIT();////退出临界区

    if (ret_code != NRF_SUCCESS)
    {
        return ret_code;
    }

    m_nrf_sdh_continue  = false;
    m_nrf_sdh_suspended = false;

    // Enable event interrupt.
    // Interrupt priority has already been set by the stack.
    softdevices_evt_irq_enable();

    // Notify observers about a finished SoftDevice enable process.
    sdh_state_observer_notify(NRF_SDH_EVT_STATE_ENABLED);

    return NRF_SUCCESS;
}
```

.source是选择时钟源，协议栈需要一个低频时钟源，时钟源有3种选择:

// <0=> NRF_CLOCK_LF_SRC_RC : 内部RC时钟
// <1=> NRF_CLOCK_LF_SRC_XTAL : 外部晶振时钟
// <2=> NRF_CLOCK_LF_SRC_SYNTH : 从高速时钟合成的低速时钟

内部RC时钟由内部RC时钟振荡器生成，如果需要使用内部RC时钟时，进行校准的时候芯片32MHz高速时钟必须运行，在4s间隔下将增加6到7ua的平均电流消耗。同时RC功能也消耗一点电流，因此相比于外部晶振将增加8到10ua的电流。

外部晶振需要使用32.768KHz低速晶振，这种状态下电流消耗最低，同时要配置.accuracy参数，该参数代表外部时钟的精度。当选择外部晶振时.rc_ctiv, .rc_temp_ctiv参数必须为0.

内部高速时钟合成，这种方式和RC时钟振荡器生成类似，需要高速时钟作为生成基础。这种方式电流消耗是最大的，功耗是最高的。

.rc_ctiv：在0.25s单位下的校准时间间隔，为了避免过度的时间漂移，在一个刻度时间间隔下，最大的温度变化允许为0.5°。

.rc_temp_ctiv: 温度变化下的校准间隔。

在NRF52下推荐配置NRF_CLOCK_LF_SRC_RC为：rc_ctiv=16 and rc_temp_ctiv=2.

2.nrf_sdh_ble_default_cfg_set(APP_BLE_CONN_CFG_TAG, &ram_start);协议栈初始化，为相应的蓝牙协议栈事件分配RAM空间。

APP_BLE_CONN_CFG_TAG：表示连接参数配置标号

ram_start：表示协议栈RAM起始地址。

```c
ret_code_t nrf_sdh_ble_default_cfg_set(uint8_t conn_cfg_tag, uint32_t * p_ram_start)
{
    uint32_t ret_code;

    ret_code = nrf_sdh_ble_app_ram_start_get(p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        return ret_code;
    }

#if defined (S112) || defined(S312)
    STATIC_ASSERT(NRF_SDH_BLE_CENTRAL_LINK_COUNT == 0, "When using s112, NRF_SDH_BLE_CENTRAL_LINK_COUNT must be 0.");
#endif

    // Overwrite some of the default settings of the BLE stack.
    // If any of the calls to sd_ble_cfg_set() fail, log the error but carry on so that
    // wrong RAM settings can be caught by nrf_sdh_ble_enable() and a meaningful error
    // message will be printed to the user suggesting the correct value.
    ble_cfg_t ble_cfg;

#if (NRF_SDH_BLE_TOTAL_LINK_COUNT != 0)
    // Configure the connection count.
    memset(&ble_cfg, 0, sizeof(ble_cfg));
    ble_cfg.conn_cfg.conn_cfg_tag                     = conn_cfg_tag;//设置连接标号，可以作为配置连接的标志，可以在创建连接的时候，使得sd_ble_gap_adv_start()和sd_ble_gap_connect()函数调用该配置
    ble_cfg.conn_cfg.params.gap_conn_cfg.conn_count   = NRF_SDH_BLE_TOTAL_LINK_COUNT;//设置总连接数，该数目等于程序中设定的从机和主机的数目和
    ble_cfg.conn_cfg.params.gap_conn_cfg.event_length = NRF_SDH_BLE_GAP_EVENT_LENGTH;//设置GAP事件长度，GAP事件长度是在蓝牙底层发送数据包时给的处理时间。如果数据MTU大的话，可以把数据处理时间设置长点。

    ret_code = sd_ble_cfg_set(BLE_CONN_CFG_GAP, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_CONN_CFG_GAP.",
                      nrf_strerror_get(ret_code));
    }

    // Configure the connection roles.
    memset(&ble_cfg, 0, sizeof(ble_cfg));
    ble_cfg.gap_cfg.role_count_cfg.periph_role_count  = NRF_SDH_BLE_PERIPHERAL_LINK_COUNT;//从机数量
#if !defined (S112) && !defined(S312)
    ble_cfg.gap_cfg.role_count_cfg.central_role_count = NRF_SDH_BLE_CENTRAL_LINK_COUNT;//主机数量
    ble_cfg.gap_cfg.role_count_cfg.central_sec_count  = MIN(NRF_SDH_BLE_CENTRAL_LINK_COUNT,
                                                            BLE_GAP_ROLE_COUNT_CENTRAL_SEC_DEFAULT);
#endif

    ret_code = sd_ble_cfg_set(BLE_GAP_CFG_ROLE_COUNT, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_GAP_CFG_ROLE_COUNT.",
                      nrf_strerror_get(ret_code));
    }

    // Configure the maximum ATT MTU.
#if (NRF_SDH_BLE_GATT_MAX_MTU_SIZE != 23)
    memset(&ble_cfg, 0x00, sizeof(ble_cfg));
    ble_cfg.conn_cfg.conn_cfg_tag                 = conn_cfg_tag;
    ble_cfg.conn_cfg.params.gatt_conn_cfg.att_mtu = NRF_SDH_BLE_GATT_MAX_MTU_SIZE;//MTU(Maximum Transmission Unit, MTU)是指一种通信协议的某一层上面所能通过的最大数据包大小，单位是字节。因为协议数据单元的包头和包尾的长度是固定的，MTU越大，传送相同的用户数据所需的数据包个数也越低。早期蓝牙4.0的MTU为23个bytes，蓝牙5.0理论上可以设置672个字节。
    ret_code = sd_ble_cfg_set(BLE_CONN_CFG_GATT, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_CONN_CFG_GATT.",
                      nrf_strerror_get(ret_code));
    }
#endif  // NRF_SDH_BLE_GATT_MAX_MTU_SIZE != 23
#endif  // NRF_SDH_BLE_TOTAL_LINK_COUNT != 0

    // Configure number of custom UUIDS.
    memset(&ble_cfg, 0, sizeof(ble_cfg));
    ble_cfg.common_cfg.vs_uuid_cfg.vs_uuid_count = NRF_SDH_BLE_VS_UUID_COUNT;//设置私有任务的UUID数目，也就是自定义的128bit的UUID数目。比如你定制了蓝牙串口和蓝牙LED两个主任务，每个主任务分配128bit UUID，这里NRF_SDH_BLE_VS_UUID_COUNT就设置为2，加入UUID服务后RAM使用空间要增加，RAM的空间也要修改。一个服务大概是0x10大小，RAM设置里增加对应的参数值。

    ret_code = sd_ble_cfg_set(BLE_COMMON_CFG_VS_UUID, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_COMMON_CFG_VS_UUID.",
                      nrf_strerror_get(ret_code));
    }

    // Configure the GATTS attribute table.
    memset(&ble_cfg, 0x00, sizeof(ble_cfg));
    ble_cfg.gatts_cfg.attr_tab_size.attr_tab_size = NRF_SDH_BLE_GATTS_ATTR_TAB_SIZE;//GATT中，由Primary Service、Secondary Service和Characteristic构成了属于ATT protocol中定义的group of attributes，NRF_SDH_BLE_GATTS_ATTR_TAB_SIZE就是为了这些设置的数据分配一个空间。

    ret_code = sd_ble_cfg_set(BLE_GATTS_CFG_ATTR_TAB_SIZE, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_GATTS_CFG_ATTR_TAB_SIZE.",
                      nrf_strerror_get(ret_code));
    }

    // Configure Service Changed characteristic.
    memset(&ble_cfg, 0x00, sizeof(ble_cfg));
    ble_cfg.gatts_cfg.service_changed.service_changed = NRF_SDH_BLE_SERVICE_CHANGED;

    ret_code = sd_ble_cfg_set(BLE_GATTS_CFG_SERVICE_CHANGED, &ble_cfg, *p_ram_start);
    if (ret_code != NRF_SUCCESS)
    {
        NRF_LOG_ERROR("sd_ble_cfg_set() returned %s when attempting to set BLE_GATTS_CFG_SERVICE_CHANGED.",
                      nrf_strerror_get(ret_code));
    }

    return NRF_SUCCESS;
}
```

NRF_SDH_BLE_PERIPHERAL_LINK_COUNT和NRF_SDH_BLE_CENTRAL_LINK_COUNT定义：

1.作为从机

#define NRF_SDH_BLE_CENTRAL_LINK_COUNT 	  0

#define NRF_SDH_BLE_PERIPHERAL_LINK_COUNT 1

(1个可使用从机进行连接的链路)

2.作为主机

#define NRF_SDH_BLE_CENTRAL_LINK_COUNT 	  1

#define NRF_SDH_BLE_PERIPHERAL_LINK_COUNT 0

(1个可使用主机进行连接的链路，也就是连接1路从机)

3.作为主从一体机

#define NRF_SDH_BLE_CENTRAL_LINK_COUNT 	  2

#define NRF_SDH_BLE_PERIPHERAL_LINK_COUNT 1

(2个可使用主机进行连接的链路，也就是作为主机连接2路从机，作为从机可连接1个主机)

## 5.8GAP和GATT详解

GAP(Generic Access Profile, GAP), 该Profile保证不同的Bluetooth产品可以互相发现对方并建立连接。

GAP定义了蓝牙设备如何发现和建立与其它设备的安全或不安全连接。他处理一些一般模式的业务（如询问、命名和搜索）和一些安全性问题（如担保），同时还处理一些一般性的运行任务。因此，它具有强制性，并作为所有其它蓝牙应用规范的基础。

```c
static void gap_params_init(void)
{
    ret_code_t              err_code;
    ble_gap_conn_params_t   gap_conn_params;
    ble_gap_conn_sec_mode_t sec_mode;
	//安全权限设置
    BLE_GAP_CONN_SEC_MODE_SET_OPEN(&sec_mode);//连接模式，主要是是否需要加密
	//设备名称设置
    err_code = sd_ble_gap_device_name_set(&sec_mode,
                                          (const uint8_t *)DEVICE_NAME,
                                          strlen(DEVICE_NAME));
    APP_ERROR_CHECK(err_code);

    /* YOUR_JOB: Use an appearance value matching the application's use case.应用图标值的设置，如果没有图标，可以不配置
       err_code = sd_ble_gap_appearance_set(BLE_APPEARANCE_);
       APP_ERROR_CHECK(err_code); */

    memset(&gap_conn_params, 0, sizeof(gap_conn_params));

    gap_conn_params.min_conn_interval = MIN_CONN_INTERVAL;
    gap_conn_params.max_conn_interval = MAX_CONN_INTERVAL;
    gap_conn_params.slave_latency     = SLAVE_LATENCY;
    gap_conn_params.conn_sup_timeout  = CONN_SUP_TIMEOUT;

    err_code = sd_ble_gap_ppcp_set(&gap_conn_params);
    APP_ERROR_CHECK(err_code);
}
```

GAP通常还会负责启动BLE连接的安全功能。只有对通过身份验证的连接而言某些数据是可读可写的。一旦形成一个连接，两个设备可以通过一个过程被称为配对。进行配对时，秘钥建立加密和认证的链接。在一个典型的案例，从机需要主机提供秘钥以完成配对过程。这可能是一个固定值，如“000000”，或可能是一个随机生成的值。主机发送正确秘钥后，两台设备交换安全秘钥加密和验证的链接。

在许多情况下，主机和从机会经常断开、建立连接。BLE具有一个安全功能允许两个设备在配对的时候给对方一个长久的安全秘钥。这称为绑定，使两个重连设备能够快速重新确立加密和认证而不需要经过充分的配对过程，只要它们存储长期的秘钥信息。

![image-20221002000744773](E:\databases\note\image-20221002000744773.png)

安全连接模式分为7种：

安全模式0水平0：不允许连接

安全模式1水平1：无安全要求

安全模式1水平2：需要加密链接（又称为直接打开链接）

安全模式1水平3：加密链接和MITM保护

安全模式1水平4：LESC加密链接和MITM保护

安全模式2水平1：签名或者加密，无MITM保护

安全模式2水平2：MITM保护签名或者加密链接

默认蓝牙名称是显示英文的，直接把英文改成中文可能会导致蓝牙名称显示的时候出现乱码。要显示蓝牙名称为中文的步骤如下：

新建main.h文件，定义蓝牙设备名称

![image-20221002002447495](E:\databases\note\image-20221002002447495.png)

加入头文件

![image-20221002002600699](E:\databases\note\image-20221002002600699.png)

在Misc Controls栏加入--locale=english

![image-20221002002940375](E:\databases\note\image-20221002002940375.png)

连接间隔：

在一个BLE连接中，跳频机制需要被使用，这样两个设备之间可以在一个特定的通道上进行数据收发，在一个特定的时间之后会跳到一个新的通道上，LL层负责通道切换。

这个遇见设备收到数据被称作是连接事件。

尽管没有应用程序数据需要收发，两个设备之间仍然会交换链路层数据来保持连接。连接间隔是两个连接事件之间的时间，使用1.25ms的步进，最小值是6（6x1.25=7.5ms）到最大值3200（4s）。

gap_conn_params.slave_latency从机潜伏周期：这个参数描述了从机跳过连接事件的次数。如果从机没有任何数据传送，它可以选择跳过连接事件，并保持睡眠。

gap_conn_params.conn_sup_timeout监督超时：这是两个成功连接事件之间间隔的最大值。如果超过这个时间还未出现成功的连接事件，那么设备将会考虑失去连接，返回一个未连接状态。使用10ms步进，最小值是10（100ms）到最大值3200（32s）。同时超时时间必须大于有效连接事件。有效连接事件事件=连接间隔x(1+从机潜伏周期)。

## 5.9广播初始化与广播切换

```c
static void advertising_init(void)
{
    ret_code_t             err_code;
    ble_advertising_init_t init;

    memset(&init, 0, sizeof(init));

    init.advdata.name_type               = BLE_ADVDATA_FULL_NAME;//广播全名
    init.advdata.include_appearance      = true;//是否需要图标
    init.advdata.flags                   = BLE_GAP_ADV_FLAGS_LE_ONLY_GENERAL_DISC_MODE;//蓝牙设备模式
    init.advdata.uuids_complete.uuid_cnt = sizeof(m_adv_uuids) / sizeof(m_adv_uuids[0]);
    init.advdata.uuids_complete.p_uuids  = m_adv_uuids;

    init.config.ble_adv_fast_enabled  = true;
    init.config.ble_adv_fast_interval = APP_ADV_INTERVAL;//蓝牙广播间隔
    init.config.ble_adv_fast_timeout  = APP_ADV_DURATION;//蓝牙广播超时时间，如果希望一直广播，这里置0并且上面的蓝牙设备模式要设置为普通发现模式，不支持BR/EDR

    init.evt_handler = on_adv_evt;//蓝牙广播模式设置成功回调函数

    err_code = ble_advertising_init(&m_advertising, &init);
    APP_ERROR_CHECK(err_code);

    ble_advertising_conn_cfg_tag_set(&m_advertising, APP_BLE_CONN_CFG_TAG);//设置广播识别号
}
```

蓝牙设备模式设置通过flags来进行标识：

```c
#define BLE_GAP_ADV_FLAG_LE_LIMITED_DISC_MODE         (0x01)   /**< LE Limited Discoverable Mode. *///LE有限发现模式
#define BLE_GAP_ADV_FLAG_LE_GENERAL_DISC_MODE         (0x02)   /**< LE General Discoverable Mode. *///LE普通发现模式
#define BLE_GAP_ADV_FLAG_BR_EDR_NOT_SUPPORTED         (0x04)   /**< BR/EDR not supported. *///不支持BR/EDR模式
#define BLE_GAP_ADV_FLAG_LE_BR_EDR_CONTROLLER         (0x08)   /**< Simultaneous LE and BR/EDR, Controller. *///同时支持BLE和EDR模式（控制器）
#define BLE_GAP_ADV_FLAG_LE_BR_EDR_HOST               (0x10)   /**< Simultaneous LE and BR/EDR, Host. *///同时支持BLE和BR/EDR模式（主机）
#define BLE_GAP_ADV_FLAGS_LE_ONLY_LIMITED_DISC_MODE   (BLE_GAP_ADV_FLAG_LE_LIMITED_DISC_MODE | BLE_GAP_ADV_FLAG_BR_EDR_NOT_SUPPORTED)   /**< LE Limited Discoverable Mode, BR/EDR not supported. */
#define BLE_GAP_ADV_FLAGS_LE_ONLY_GENERAL_DISC_MODE   (BLE_GAP_ADV_FLAG_LE_GENERAL_DISC_MODE | BLE_GAP_ADV_FLAG_BR_EDR_NOT_SUPPORTED)   /**< LE General Discoverable Mode, BR/EDR not supported. */
```

LE有限发现模式和LE普通发现模式是有区别的，有限发现模式下，设备广播间隔比一般发现模式小，同时持续时间有限。而普通发现模式没有时间限制，如果需要设备一直不停广播不休眠就必须设置为普通发现模式。

蓝牙BR/EDR（蓝牙基本速率/增强数据率），其数据吞吐量更高，功耗也会相应增加。

## 5.10profile私有服务建立

BLE私有服务这里用一个led点灯例子举例。

在ble_servers文件夹下新建ble_leds文件夹，添加文件ble_led.c, ble_led.h文件。

```c
#ifndef __BLE_LED_H__
#define __BLE_LED_H__

#include <stdint.h>
#include <stdbool.h>
#include "ble.h"
#include "nrf_sdh_ble.h"


#ifdef __cplusplus
#if __cplusplus
extern "C"{
#endif
#endif /* __cplusplus */

/**@brief	Macro for defining a ble_led instance.定义一个LED服务实例
 *
 * @param	_name	Name of the instance.
 * @hideinitializer
 */
#define BLE_LED_DEF(_name)                                                                          \
	static ble_led_t _name; 																			\
	NRF_SDH_BLE_OBSERVER(_name ## _obs, 																\
						 BLE_LBS_BLE_OBSERVER_PRIO, 													\
						 ble_led_on_ble_evt, &_name)

#define BLE_LED_UUID_BASE 		{0xD3, 0xBC, 0x30, 0xB2, 0xB1, 0xD9, 0x59, 0xB4, 0xC4, 0x44, 0xCC, 0xF9, 0x00, 0x00, 0x60, 0xB5}//定义UUID

#define BLE_LED_UUID_SERVICE	0x1523    //定义LED服务UUID
#define BLE_LED_UUID_CHAR		0x1524    //定义LED特征UUID

typedef struct ble_led ble_led_t;
typedef void (*ble_led_write_handler_t)(uint16_t conn_handle, ble_led_t *p_led, uint8_t new_state);
typedef struct
{
	ble_led_write_handler_t led_write_handler;
}ble_led_init_t;
struct ble_led
{
	uint16_t service_handle;
	ble_gatts_char_handles_t led_char_handles;
	uint8_t uuid_type;
	ble_led_write_handler_t led_write_handler;
};//定义LED服务结构体

uint32_t ble_led_init(ble_led_t *p_led, const ble_led_init_t *p_led_init);
void ble_led_on_ble_evt(ble_evt_t const *p_ble_evt, void *p_context);

#ifdef __cplusplus
#if __cplusplus
}
#endif
#endif /* __cplusplus */


#endif /* __BLE_LED_H__ */

```

定义UUID需要使用nRFgo工具生成UUID，步骤如下：

![image-20221024003340007](E:\databases\note\image-20221024003340007.png)

点击nRF8001 Setup下拉菜单的Edit 128 bit UUIDs...，在打开的页面点击Add new新增UUID

![image-20221024003610613](E:\databases\note\image-20221024003610613.png)

将UUID复制到代码里并倒序定义，xxxx处直接用0代替。

![image-20221024003736735](E:\databases\note\image-20221024003736735.png)

.c文件里编写如下内容：

```c
#include "ble_led.h"
#include "sdk_common.h"

static void led_on_write(ble_led_t * p_led, ble_evt_t const * p_ble_evt)
{
    ble_gatts_evt_write_t const * p_evt_write = &p_ble_evt->evt.gatts_evt.params.write;
	
    if (   (p_evt_write->handle == p_led->led_char_handles.value_handle)
        && (p_evt_write->len == 1)
        && (p_led->led_write_handler != NULL))
    {
        p_led->led_write_handler(p_ble_evt->evt.gap_evt.conn_handle, p_led, p_evt_write->data[0]);
    }
}


uint32_t ble_led_init(ble_led_t *p_led, const ble_led_init_t *p_led_init)
{
	uint32_t err_code;
	ble_uuid_t ble_uuid;
	ble_gatts_char_md_t ble_led_char_param;
	ble_gatts_attr_md_t ble_led_attr_param;
	ble_gatts_attr_t ble_led_char_value;
	ble_uuid128_t base_uuid = BLE_LED_UUID_BASE;
	
	p_led->led_write_handler = p_led_init->led_write_handler;
	
	//向协议栈添加LED base uuid
	err_code = sd_ble_uuid_vs_add(&base_uuid, &p_led->uuid_type);
	VERIFY_SUCCESS(err_code);
	ble_uuid.type = p_led->uuid_type;
	ble_uuid.uuid = BLE_LED_UUID_SERVICE;
	//向协议栈添加服务
	err_code = sd_ble_gatts_service_add(BLE_GATTS_SRVC_TYPE_PRIMARY, &ble_uuid, &p_led->service_handle);
	VERIFY_SUCCESS(err_code);
	//向协议栈添加特征值
	memset(&ble_led_char_param, 0, sizeof(ble_gatts_char_md_t));
	memset(&ble_led_attr_param, 0, sizeof(ble_gatts_attr_md_t));
	memset(&ble_led_char_value, 0, sizeof(ble_gatts_attr_t));
	ble_led_char_param.char_props.write = 1; //允许无回复的写
	ble_led_char_param.char_props.read = 1;  //允许读
	ble_led_char_param.p_char_user_desc = NULL;
	ble_led_char_param.p_char_pf = NULL;
	ble_led_char_param.p_user_desc_md = NULL;
	ble_led_char_param.p_cccd_md = NULL;
	ble_led_char_param.p_sccd_md = NULL;
	ble_uuid.type = p_led->uuid_type;
	ble_uuid.uuid = BLE_LED_UUID_CHAR;
	BLE_GAP_CONN_SEC_MODE_SET_OPEN(&ble_led_attr_param.read_perm);
	BLE_GAP_CONN_SEC_MODE_SET_OPEN(&ble_led_attr_param .write_perm);
	ble_led_attr_param.vloc = BLE_GATTS_VLOC_STACK;
	ble_led_char_value.p_uuid = &ble_uuid;
	ble_led_char_value.p_attr_md = &ble_led_attr_param;
	ble_led_char_value.init_len = sizeof(uint8_t);
	ble_led_char_value.init_offs = 0;
	ble_led_char_value.max_len = sizeof(uint8_t);
	ble_led_char_value.p_value = NULL;
	err_code = sd_ble_gatts_characteristic_add(p_led->service_handle, &ble_led_char_param, &ble_led_char_value, &p_led->led_char_handles);
	VERIFY_SUCCESS(err_code);
	
	return NRF_SUCCESS;
}

void ble_led_on_ble_evt(ble_evt_t const *p_ble_evt, void *p_context)
{
	switch (p_ble_evt->header.evt_id)
	{
		case BLE_GATTS_EVT_WRITE:
			led_on_write((ble_led_t *)p_context, p_ble_evt);
			break;
		default:
			break;
	}
}
```

应用层：

1.声明LED服务实例

![image-20221027010826525](E:\databases\note\image-20221027010826525.png)

2.添加服务

![image-20221027010948906](E:\databases\note\image-20221027010948906.png)

3.添加广播内容

![image-20221027011054689](E:\databases\note\image-20221027011054689.png)

![image-20221027011141739](E:\databases\note\image-20221027011141739.png)

4.编译下载运行，如果提示内存不足就根据提示增加内存就可以了。

## 5.11抓包工具下载安装配置

这里参考官方教程https://infocenter.nordicsemi.com/index.jsp?topic=%2Fug_sniffer_ble%2FUG%2Fsniffer_ble%2Fintro.html&cp=11_5编写。

![image-20230327174131620](E:\databases\note\image-20230327174131620.png)

1.下载安装wireshark抓包工具，安装过程要勾选Install USBPcap，其它一路点next就可以。

![image-20230327172416300](E:\databases\note\image-20230327172416300.png)

2.安装nRF Sniffer，官网下载nRF Sniffer capture tool，下载后解压，在extcap文件夹里打开cmd窗口执行命令

py -3 -m pip install -r requirements.txt.安装pyserial，安装成功如图所示

![image-20230327172910378](E:\databases\note\image-20230327172910378.png)

3.复制extcap文件夹下所有文件和目录，打开wireshark菜单栏帮助>关于wireshark(A)双击Personal Extcap path路径创建目录，将先前复制的内容粘贴到这里，并在这里打开cmd窗口执行命令nrf_sniffer_ble.bat --extcap-interfaces

![image-20230327173307462](E:\databases\note\image-20230327173307462.png)

出现以下信息代表安装成功

![image-20230327173545995](E:\databases\note\image-20230327173545995.png)

4.点击使能wireshark菜单栏视图>接口工具栏>**nRF Sniffer for Bluetooth LE**，然后按F5或者点击菜单栏捕获>刷新接口列表刷新接口就可以看到**nRF Sniffer for Bluetooth LE COM**了。

![image-20230327173940375](E:\databases\note\image-20230327173940375.png)

## 5.12广播包解析

参考连接https://blog.csdn.net/qq_26226375/article/details/128129273?spm=1001.2101.3001.6650.5&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-128129273-blog-111901325.235%5Ev27%5Epc_relevant_3mothn_strategy_and_data_recovery&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-128129273-blog-111901325.235%5Ev27%5Epc_relevant_3mothn_strategy_and_data_recovery&utm_relevant_index=10

广播类型主要有9种：

ADV_IND：通用广播，该广播最常用，可被连接和扫描

ADV_DIRECT_IND: 定向广播，该广播只能被指定设备发现

ADV_NONCONNN_IND: 非连接广播，该广播不能被其它设备连接

SCAN_REQ: 主机扫描包，当主机收到从机广播包后，由主机发出扫描包

AUX_SCAN_REQ:  扫描请求扩展包，该包由主机发出，不在传统广播信道37,38,39上，而在其它数据信道上。

SCAN_RSP:	扫描响应包，从机收到主机的SCAN_REQ包后，给主机一个SCAN_RSP包，让主机获取更多广播数据。

CONNECT_IND:	连接包，由主机发出

AUX_CONNECT_REQ:	连接请求扩展包，该包由主机发出，不在传统广播信道37,38,39上，而在其它数据信道上。

ADV_SCAN_IND:	可扫描非定向广播包，有从机发出。

![image-20230408161804420](E:\databases\note\image-20230408161804420.png)

### 5.12.1 ADV_IND: 通用广播

![image-20230329112438884](E:\databases\note\image-20230329112438884.png)

byte0~byte16: 这是wrieshark工具生成内容，其中byte9是广播信道。

byte17~byte55: 这是广播包内容。

byte17~byte20: 广播接入地址，为固定值。

byte21~byte22: 这是PDU包头。

byte23~byte28: 这是蓝牙MAC地址。

byte29~byte52: 这是数据结构部分。

byte29~byte32: 这是第一组数据，byte29是length，byte30是AD Type，byte31和byte32是数据。

byte33~byte35: 这是第二组数据，byte33是length，byte34是AD Type，byte35是数据。

byte36~byte52: 这是第三组数据，byte36是length，byte37是AD Type，byte38~byte52是数据。

byte53~byte55: 这是CRC检验码。

### 5.12.2 SCAN_REQ: 扫描请求帧

![image-20230329113736943](E:\databases\note\image-20230329113736943.png)

byte0~byte16: 这是wrieshark工具生成内容，其中byte9是广播信道。

byte17~byte20: 广播接入地址，为固定值。

byte21~byte22: 这是PDU包头。

byte23~byte28: 这是主机MAC地址。

byte29~byte34: 这是蓝牙MAC地址。

byte35~byte37: 这是CRC校验码。

### 5.12.3 SCAN_RSP: 扫描响应帧

![image-20230329114350292](E:\databases\note\image-20230329114350292.png)

byte0~byte16: 这是wrieshark工具生成内容，其中byte9是广播信道。

byte17~byte49: 这是广播包内容。

byte17~byte20: 广播接入地址，为固定值。

byte21~byte22: 这是PDU包头。

byte23~byte28: 这是蓝牙MAC地址。

byte29~byte46: byte29是length，byte30是AD Type，byte31~byte46是数据。

byte47~byte49: 这是CRC检验码。

### 5.12.4 CONNECT_IND: 连接请求包

![image-20230329115044735](E:\databases\note\image-20230329115044735.png)

byte0~byte16: 这是wrieshark工具生成内容，其中byte9是广播信道。

byte17~byte20: 广播接入地址，为固定值。

byte21~byte22: 这是PDU包头。

byte23~byte28: 这是主机MAC地址。

byte29~byte34: 这是蓝牙MAC地址。

byte35~byte37: 这是CRC校验码。



AD Type：广播数据类型

0x07: 128bit service class uuids

0x08: Device Name(shortened)

0x09: Device Name

0x16: service data

0xff: Manufacturer Specific

## 5.13在广播包里添加service data

![image-20230329173842953](E:\databases\note\image-20230329173842953.png)

![image-20230329173918797](E:\databases\note\image-20230329173918797.png)

如果是扫描回应包SCAN_RSP，只需要将

```c
init.advdata.service_data_count = 1;
init.advdata.p_service_data_array = &service_data;
改为
init.srdata.service_data_count = 1;
init.srdata.p_service_data_array = &service_data;
即可
或者按以下方式改也行：
static void advertising_init(void)
{
    ret_code_t             err_code;
    ble_advertising_init_t init;
	ble_advertising_t            *p_advertising = &m_advertising;
	ble_uuid_t adv_uuids[] = {{LED_KEY_UUID_SERVICE, mUser_led_key_id.uuid_type}};
	ble_advdata_manuf_data_t manuf_data = {0x004c, {sizeof("hello nor")-1, "hello nor"}};
    memset(&init, 0, sizeof(init));

    init.advdata.name_type               = BLE_ADVDATA_SHORT_NAME;
	init.advdata.short_name_len = 6;
    init.advdata.include_appearance      = true;
    init.advdata.flags                   = BLE_GAP_ADV_FLAGS_LE_ONLY_GENERAL_DISC_MODE;
    init.srdata.uuids_complete.uuid_cnt = sizeof(adv_uuids) / sizeof(adv_uuids[0]);
    init.srdata.uuids_complete.p_uuids  = adv_uuids;

    init.config.ble_adv_fast_enabled  = true;
    init.config.ble_adv_fast_interval = APP_ADV_INTERVAL;
    init.config.ble_adv_fast_timeout  = APP_ADV_DURATION;

    init.evt_handler = on_adv_evt;
	init.advdata.p_manuf_specific_data = &manuf_data;
    err_code = ble_advertising_init(&m_advertising, &init);
    APP_ERROR_CHECK(err_code);
    ble_advertising_conn_cfg_tag_set(&m_advertising, APP_BLE_CONN_CFG_TAG);
}
```

## 5.13添加BLE按键通知

在新建的私有服务user_led_key.c文件里添加如下代码

```c
uint32_t led_ble_init(user_led_key_t *p_led, const led_init_t *p_led_init)
{
	uint32_t err_code;
	ble_uuid_t	ble_uuid;
	ble_add_char_params_t add_char_params;
	ble_uuid128_t base_uuid = {LED_KEY_BASE_UUID};

	//1.register UUID
	p_led->led_write_handler = p_led_init->led_write_handler;
	err_code = sd_ble_uuid_vs_add(&base_uuid, &p_led->uuid_type);
	VERIFY_SUCCESS(err_code);
	//2.add service
	ble_uuid.type = p_led->uuid_type;
	ble_uuid.uuid = LED_KEY_UUID_SERVICE;
	err_code = sd_ble_gatts_service_add(BLE_GATTS_SRVC_TYPE_PRIMARY, &ble_uuid, &p_led->service_handle);
	VERIFY_SUCCESS(err_code);
	//3.set char params
	memset(&add_char_params, 0, sizeof(ble_add_char_params_t));
	add_char_params.uuid = KEY_CHAR_UUID;
	add_char_params.uuid_type = p_led->uuid_type;
	add_char_params.init_len = 1;
	add_char_params.max_len = 1;
	add_char_params.char_props.read = 1;
	add_char_params.char_props.notify = 1;
	add_char_params.read_access = SEC_OPEN;
	add_char_params.cccd_write_access = SEC_OPEN;
	
	return characteristic_add(p_led->service_handle, &add_char_params, &p_led->key_char_handles);
}

uint32_t key_on_ble_changed(uint16_t conn_handle, user_led_key_t *p_key, uint8_t button_state)
{
	ble_gatts_hvx_params_t params;
	uint16_t len = sizeof(button_state);
	
	memset(&params, 0, sizeof(ble_gatts_hvx_params_t));
	params.type = BLE_GATT_HVX_NOTIFICATION;
	params.handle = p_key->key_char_handles.value_handle;
	params.p_data = &button_state;
	params.p_len = &len;

	return sd_ble_gatts_hvx(conn_handle, &params);
}
```

在main.c文件里的按键回调函数调用key_on_ble_changed函数，APP端连接后使能通知功能即可。

```c
static void bsp_event_handler(bsp_event_t event)
{
    ret_code_t err_code;

    switch (event)
    {
        case BSP_EVENT_SLEEP:
            sleep_mode_enter();
            break; // BSP_EVENT_SLEEP

        case BSP_EVENT_DISCONNECT:
            err_code = sd_ble_gap_disconnect(m_conn_handle,
                                             BLE_HCI_REMOTE_USER_TERMINATED_CONNECTION);
            if (err_code != NRF_ERROR_INVALID_STATE)
            {
                APP_ERROR_CHECK(err_code);
            }
            break; // BSP_EVENT_DISCONNECT

        case BSP_EVENT_WHITELIST_OFF:
            if (m_conn_handle == BLE_CONN_HANDLE_INVALID)
            {
                err_code = ble_advertising_restart_without_whitelist(&m_advertising);
                if (err_code != NRF_ERROR_INVALID_STATE)
                {
                    APP_ERROR_CHECK(err_code);
                }
            }
            break; // BSP_EVENT_KEY_0
		case BSP_EVENT_KEY_0:
			NRF_LOG_INFO("BSP_EVENT_KEY_0 PUSH");
			break;
		case BSP_EVENT_KEY_1:
			NRF_LOG_INFO("BSP_EVENT_KEY_1 RELEASE");
			mUser_key_state = !mUser_key_state;
			err_code = key_on_ble_changed(m_conn_handle, &mUser_led_key_id, mUser_key_state);
			if (err_code != NRF_SUCCESS &&
                err_code != BLE_ERROR_INVALID_CONN_HANDLE &&
                err_code != NRF_ERROR_INVALID_STATE &&
                err_code != BLE_ERROR_GATTS_SYS_ATTR_MISSING)
			{
				APP_ERROR_CHECK(err_code);
            }
			break;
		case BSP_EVENT_KEY_2:
			NRF_LOG_INFO("BSP_EVENT_KEY_2 LONG PUSH");
			break;
        default:
            break;
    }
}
```



## 5.14添加BLE指示功能

## 5.15添加BLE电池电量服务

### 5.15.1在工程中加入官方写好的服务，使能电池电量检测模块

![image-20230330110503163](E:\databases\note\image-20230330110503163.png)

![image-20230330151052866](E:\databases\note\image-20230330151052866.png)

![image-20230330161212441](E:\databases\note\image-20230330161212441.png)

saadc初始化：可以参考es_battery_voltage_saadc.c或者example/peripheral/saadc/main.c

```c
#define SAMPLES_IN_BUFFER 1
static nrf_saadc_value_t adc_buf[SAMPLES_IN_BUFFER];

void battery_check_init(nrf_drv_saadc_event_handler_t        event_handler)
{
    nrf_saadc_channel_config_t channel_config = NRF_DRV_SAADC_DEFAULT_CHANNEL_CONFIG_SE(NRF_SAADC_INPUT_AIN2);
	ret_code_t err_code = nrf_drv_saadc_init(NULL, event_handler);

    APP_ERROR_CHECK(err_code);

    err_code = nrf_drv_saadc_channel_init(2, &channel_config);
    APP_ERROR_CHECK(err_code);

    err_code = nrf_drv_saadc_buffer_convert(adc_buf, SAMPLES_IN_BUFFER);//只有采样满SAMPLES_IN_BUFFER才会触发event_handler
    APP_ERROR_CHECK(err_code);

}
```

定义ADC采样回调函数：

```c
void battery_saadc_callback(nrf_drv_saadc_evt_t const * p_event)
{
	int i;
	ret_code_t err_code;
	nrf_saadc_value_t adc_result;
	uint16_t batt_lvl_in_milli_volts;
	uint8_t percentage_batt_lvl;
	
    if (p_event->type == NRF_DRV_SAADC_EVT_DONE)
    {
		adc_result = p_event->data.done.p_buffer[SAMPLES_IN_BUFFER-1];
		err_code = nrfx_saadc_buffer_convert(p_event->data.done.p_buffer, SAMPLES_IN_BUFFER);
        APP_ERROR_CHECK(err_code);
		//adc value to vbat value
		batt_lvl_in_milli_volts = ADC_RESULT_IN_MILLI_VOLTS(adc_result)+DIODE_FWD_VOLT_DROP_MILLIVOLTS;
		percentage_batt_lvl = battery_level_in_percent(batt_lvl_in_milli_volts);
		//vbat value send master by ble
		err_code = ble_bas_battery_level_update(&m_bas_id, percentage_batt_lvl, BLE_CONN_HANDLE_ALL);
		if((err_code != NRF_SUCCESS)&&
			(err_code != NRF_ERROR_INVALID_STATE)&&
			(err_code != NRF_ERROR_RESOURCES)&&
			(err_code != NRF_ERROR_BUSY)&&
			(err_code != BLE_ERROR_GATTS_SYS_ATTR_MISSING))
		{
			APP_ERROR_HANDLER(err_code);
		}
	}
}
```

添加服务：

```c
BLE_BAS_DEF(m_bas_id);
ble_bas_init_t bas_init;
memset(&bas_init, 0, sizeof(ble_bas_init_t));
bas_init.evt_handler = ble_bas_evt_handler;
bas_init.support_notification = 1;
bas_init.initial_batt_level = 100;
bas_init.bl_cccd_wr_sec = SEC_OPEN;
bas_init.bl_rd_sec = SEC_OPEN;
ble_bas_init(&m_bas_id, &bas_init);
```

## 5.16添加心率服务

添加文件，使能心率模块

![image-20230331164737334](E:\databases\note\image-20230331164737334.png)

添加服务

```c
static void services_init(void)
{
    ble_bas_init_t bas_init;
    ble_hrs_init_t hrs_init;
    ble_dis_init_t dis_init;
    uint8_t body_sensor_location;
    ....
    memset(&bas_init, 0, sizeof(ble_bas_init_t));
    bas_init.evt_handler = NULL;
    bas_init.support_notification = true;
    bas_init.p_report_ref = NULL;
    bas_init.initial_batt_level = 100;
    bas_init.bl_cccd_wr_sec = SEC_OPEN;
    bas_init.bl_rd_sec = SEC_OPEN;
    bas_init.bl_report_rd_sec = SEC_OPEN;
    ble_bas_init(&m_bas_id, &bas_init);

    body_sensor_location = BLE_HRS_BODY_SENSOR_LOCATION_FINGER;
    memset(&hrs_init, 0, sizeof(ble_hrs_init_t));

    hrs_init.evt_handler = NULL;
    hrs_init.is_sensor_contact_supported = true;
    hrs_init.p_body_sensor_location = &body_sensor_location;
    hrs_init.hrm_cccd_wr_sec = SEC_OPEN;
    hrs_init.bsl_rd_sec = SEC_OPEN;
    ble_hrs_init(&m_hrs_id, &hrs_init);
    APP_ERROR_CHECK(err_code);

    memset(&dis_init, 0, sizeof(ble_dis_init_t));
    ble_srv_ascii_to_utf8(&dis_init.manufact_name_str, (char *)MANUFACTURER_NAME);
    dis_init.dis_char_rd_sec = SEC_OPEN;
    err_code = ble_dis_init(&dis_init);
    APP_ERROR_CHECK(err_code);
    ...
}
```

配置定时器

```c
//1.声明定时器
#define BATTERY_LEVEL_MEAS_INTERVAL		APP_TIMER_TICKS(2000)
#define MIN_BATTERY_LEVEL	0
#define MAX_BATTERY_LEVEL	100
#define BATTERY_LEVEL_INCREMENT	1

#define HEART_RATE_MEAS_INTERVAL	APP_TIMER_TICKS(1000)
#define MIN_HEART_RATE	140
#define MAX_HEART_RATE	300
#define HEART_RATE_INCREMENT	10

#define RR_INTERVAL_MEAS_INTERVAL	APP_TIMER_TICKS(300)
#define MIN_RR_INTERVAL	100
#define MAX_RR_INTERVAL	500
#define RR_INTERVAL_INCREMENT	1

#define SENSOR_CONTACT_DETECTED_INTERVAL	APP_TIMER_TICKS(5000)

APP_TIMER_DEF(mUser_battery_timer_id);
APP_TIMER_DEF(mUser_heart_timer_id);
APP_TIMER_DEF(mUser_rr_timer_id);
APP_TIMER_DEF(mUser_sensor_timer_id);
//2.定时器初始化
static void timers_init(void)
{
    // Initialize timer module.
    ...
       ret_code_t err_code;
       err_code = app_timer_create(&m_app_timer_id, APP_TIMER_MODE_REPEATED, timer_timeout_handler);
       APP_ERROR_CHECK(err_code); */
       err_code = app_timer_create(&mUser_battery_timer_id, APP_TIMER_MODE_REPEATED, mUser_battery_timeout_handler);
       APP_ERROR_CHECK(err_code);
	   err_code = app_timer_create(&mUser_heart_timer_id, APP_TIMER_MODE_REPEATED, mUser_heart_timeout_handler);
       APP_ERROR_CHECK(err_code);
	   err_code = app_timer_create(&mUser_rr_timer_id, APP_TIMER_MODE_REPEATED, mUser_rr_timeout_handler);
       APP_ERROR_CHECK(err_code);
	   err_code = app_timer_create(&mUser_sensor_timer_id, APP_TIMER_MODE_REPEATED, mUser_sensor_timeout_handler);
       APP_ERROR_CHECK(err_code);
}
//3.编写定时器回调函数
void mUser_battery_timeout_handler(void * p_context)
{
	UNUSED_PARAMETER(p_context);
	ret_code_t err_code;
	uint8_t battery_level;

	battery_level = (uint8_t)sensorsim_measure(&m_battery_sim_state, &m_battery_sim_cfg);
	err_code = ble_bas_battery_level_update(&m_bas_id, battery_level, BLE_CONN_HANDLE_ALL);
	if((err_code != NRF_SUCCESS)&&
			(err_code != NRF_ERROR_INVALID_STATE)&&
			(err_code != NRF_ERROR_RESOURCES)&&
			(err_code != NRF_ERROR_BUSY)&&
			(err_code != BLE_ERROR_GATTS_SYS_ATTR_MISSING))
		{
			APP_ERROR_HANDLER(err_code);
		}
	//err_code = nrf_drv_saadc_sample();
	//APP_ERROR_CHECK(err_code);
}
void mUser_heart_timeout_handler(void * p_context)
{
	UNUSED_PARAMETER(p_context);
	ret_code_t err_code;
	uint16_t heart_rate;
	static uint32_t cnt = 0;

	heart_rate = (uint16_t)sensorsim_measure(&m_heart_rate_sim_state, &m_heart_rate_sim_cfg);
	cnt++;
	err_code = ble_hrs_heart_rate_measurement_send(&m_hrs_id, heart_rate);
	if((err_code != NRF_SUCCESS)&&
			(err_code != NRF_ERROR_INVALID_STATE)&&
			(err_code != NRF_ERROR_RESOURCES)&&
			(err_code != NRF_ERROR_BUSY)&&
			(err_code != BLE_ERROR_GATTS_SYS_ATTR_MISSING))
		{
			APP_ERROR_HANDLER(err_code);
		}
	m_rr_interval_enabled = ((cnt%3) != 0);
}
void mUser_rr_timeout_handler(void * p_context)
{
	UNUSED_PARAMETER(p_context);
	if(m_rr_interval_enabled)
	{
		uint16_t rr_interval;

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);

		rr_interval = (uint16_t)sensorsim_measure(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
		ble_hrs_rr_interval_add(&m_hrs_id, rr_interval);
	}

}
void mUser_sensor_timeout_handler(void * p_context)
{
	UNUSED_PARAMETER(p_context);
	static bool sensor_contact_detected = false;

	sensor_contact_detected = !sensor_contact_detected;
	ble_hrs_sensor_contact_detected_update(&m_hrs_id, sensor_contact_detected);

}
//4.启动定时器
static void application_timers_start(void)
{
    /* YOUR_JOB: Start your timers. below is an example of how to start a timer.
       ret_code_t err_code;
       err_code = app_timer_start(m_app_timer_id, TIMER_INTERVAL, NULL);
       APP_ERROR_CHECK(err_code); */
	
	ret_code_t err_code;
	err_code = app_timer_start(mUser_battery_timer_id, HEART_RATE_MEAS_INTERVAL, NULL);
	APP_ERROR_CHECK(err_code);
	err_code = app_timer_start(mUser_heart_timer_id, HEART_RATE_MEAS_INTERVAL, NULL);
	APP_ERROR_CHECK(err_code);
	err_code = app_timer_start(mUser_rr_timer_id,RR_INTERVAL_MEAS_INTERVAL, NULL);
	APP_ERROR_CHECK(err_code);
	err_code = app_timer_start(mUser_sensor_timer_id, SENSOR_CONTACT_DETECTED_INTERVAL, NULL);
	APP_ERROR_CHECK(err_code);

}
//5.初始化传感器数据
static void buttons_leds_init(bool * p_erase_bonds)
{
...
	m_battery_sim_cfg.min = MIN_BATTERY_LEVEL;
	m_battery_sim_cfg.max = MAX_BATTERY_LEVEL;
	m_battery_sim_cfg.incr = BATTERY_LEVEL_INCREMENT;
	m_battery_sim_cfg.start_at_max = true;
	sensorsim_init(&m_battery_sim_state, &m_battery_sim_cfg);
	m_heart_rate_sim_cfg.min = MIN_HEART_RATE;
	m_heart_rate_sim_cfg.max = MAX_HEART_RATE;
	m_heart_rate_sim_cfg.incr = HEART_RATE_INCREMENT;
	m_heart_rate_sim_cfg.start_at_max = false;
	sensorsim_init(&m_heart_rate_sim_state, &m_heart_rate_sim_cfg);
	m_rr_interval_sim_cfg.min = MIN_RR_INTERVAL;
	m_rr_interval_sim_cfg.max = MAX_RR_INTERVAL;
	m_rr_interval_sim_cfg.incr = RR_INTERVAL_INCREMENT;
	m_rr_interval_sim_cfg.start_at_max = false;
	sensorsim_init(&m_rr_interval_sim_state, &m_rr_interval_sim_cfg);
...
}
```

## 5.17BLE串口透传

将串口透传需要的文件添加到工程中并修改sdk_config.h配置

需要添加的文件有ble_link_ctx_manager.c, app_fifo.c, app_uart_fifo.c, ble_nus.c，并在keil中添加对应的头文件路径。

sdk_config.h修改如下：

```c
// <e> BLE_NUS_ENABLED - ble_nus - Nordic UART Service
//==========================================================
#ifndef BLE_NUS_ENABLED
#define BLE_NUS_ENABLED 1
#endif
// <e> BLE_NUS_CONFIG_LOG_ENABLED - Enables logging in the module.
//==========================================================
#ifndef BLE_NUS_CONFIG_LOG_ENABLED
#define BLE_NUS_CONFIG_LOG_ENABLED 1
#endif

//==========================================================

// <h> nRF_Libraries 

//==========================================================
// <q> APP_FIFO_ENABLED  - app_fifo - Software FIFO implementation
 

#ifndef APP_FIFO_ENABLED
#define APP_FIFO_ENABLED 1
#endif


// <e> APP_UART_ENABLED - app_uart - UART driver
//==========================================================
#ifndef APP_UART_ENABLED
#define APP_UART_ENABLED 1
#endif
// <o> APP_UART_DRIVER_INSTANCE  - UART instance used
 
// <0=> 0 

#ifndef APP_UART_DRIVER_INSTANCE
#define APP_UART_DRIVER_INSTANCE 0
#endif

// </e>

// <q> APP_USBD_AUDIO_ENABLED  - app_usbd_audio - USB AUDIO class
 
 
 // <o> NRF_SDH_BLE_GATT_MAX_MTU_SIZE - Static maximum MTU size. 
#ifndef NRF_SDH_BLE_GATT_MAX_MTU_SIZE
#define NRF_SDH_BLE_GATT_MAX_MTU_SIZE 247//23
#endif

#ifndef NRF_SDH_BLE_GAP_DATA_LENGTH
#define NRF_SDH_BLE_GAP_DATA_LENGTH 251
#endif

#ifndef NRF_SDH_BLE_GATT_MAX_MTU_SIZE
#define NRF_SDH_BLE_GATT_MAX_MTU_SIZE 247
#endif
```

main.c修改如下：

```c
增加串口透传实例m_nus_id.
BLE_NUS_DEF(m_nus_id, NRF_SDH_BLE_TOTAL_LINK_COUNT);
定义数据包长度
static uint16_t   m_ble_nus_max_data_len = BLE_GATT_ATT_MTU_DEFAULT - 3;
//串口发送
static void app_uart_event_handler(app_uart_evt_t * p_app_uart_event)
{
	static uint8_t data_array[BLE_NUS_MAX_DATA_LEN];
	static uint8_t index = 0;
	uint32_t err_code;
	
	switch (p_app_uart_event->evt_type)
		{
		case APP_UART_DATA_READY:
			UNUSED_VARIABLE(app_uart_get(&data_array[index]));
			index++;
			if((data_array[index-1]=='\n')||(data_array[index-1]=='\r'||(index >= m_ble_nus_max_data_len)))
			{
				if(index > 1)
				{
					NRF_LOG_DEBUG("Ready to send data over ble nus");
					NRF_LOG_HEXDUMP_DEBUG(&data_array[0], index);
					do
					{
						uint16_t length = (uint16_t)index;
						err_code = ble_nus_data_send(&m_nus_id, data_array, &length, m_conn_handle);
						if((err_code != NRF_ERROR_INVALID_STATE) && (err_code != NRF_ERROR_RESOURCES) && (err_code != NRF_ERROR_NOT_FOUND))
						{
							APP_ERROR_CHECK(err_code);
						}
					}
					while (err_code == NRF_ERROR_RESOURCES);
					
				}
				index = 0;
			}
			break;
		case APP_UART_COMMUNICATION_ERROR:
			APP_ERROR_HANDLER(p_app_uart_event->data.error_communication);
			break;
		case APP_UART_FIFO_ERROR:
			APP_ERROR_HANDLER(p_app_uart_event->data.error_code);
			break;
		default:
			break;
		}
}
//从机串口接收处理函数
static void ble_nus_data_handler(ble_nus_evt_t * p_evt)
{
	uint32_t err_code;
	uint32_t i;
	
	if(p_evt->type == BLE_NUS_EVT_RX_DATA)
	{
		NRF_LOG_DEBUG("received data from ble nus. writing data on uart.");
		NRF_LOG_HEXDUMP_DEBUG(p_evt->params.rx_data.p_data, p_evt->params.rx_data.length);
		for(i = 0; i < p_evt->params.rx_data.length; i++)
		{
			do
			{
				err_code = app_uart_put(p_evt->params.rx_data.p_data[i]);
				if((err_code != NRF_SUCCESS)&&(err_code != NRF_ERROR_BUSY))
				{
					NRF_LOG_ERROR("failed receiving nus message. error 0x%x.",err_code);
					APP_ERROR_CHECK(err_code);
				}
			}
			while (err_code == NRF_ERROR_BUSY);		
		}
		if(p_evt->params.rx_data.p_data[p_evt->params.rx_data.length-1] == '\r')
		{
			while(app_uart_put('\n') == NRF_ERROR_BUSY){}
		}
	}
}
//串口函数初始化
static void user_uart_init(void)
{
	uint32_t err_code;
	const app_uart_comm_params_t comm_params = 
	{
		.rx_pin_no = 8,
	    .tx_pin_no = 6,  
	    .rts_pin_no = 7, 
	    .cts_pin_no = 5,   
	    .flow_control = APP_UART_FLOW_CONTROL_DISABLED, 
	    .use_parity = false,
	    .baud_rate = NRF_UART_BAUDRATE_115200
	};
	
	APP_UART_FIFO_INIT(&comm_params, 256, 256, app_uart_event_handler, APP_IRQ_PRIORITY_LOWEST, err_code);
	APP_ERROR_CHECK(err_code);
}
//设置gatt的MTU值
static void gatt_evt_handler(nrf_ble_gatt_t *p_gatt, nrf_ble_gatt_evt_t const *p_evt)
{
	if((m_conn_handle == p_evt->conn_handle) && (p_evt->evt_id == NRF_BLE_GATT_EVT_ATT_MTU_UPDATED))
	{
		m_ble_nus_max_data_len = p_evt->params.att_mtu_effective - OPCODE_LENGTH - HANDLE_LENGTH;
		NRF_LOG_INFO("Data len is set to 0x%x(%d)",m_ble_nus_max_data_len,m_ble_nus_max_data_len);
	}
	NRF_LOG_DEBUG("ATT MTU exchanged completed. center 0x%x peripheral 0x%x",p_gatt->att_mtu_desired_central, p_gatt->att_mtu_desired_periph);
}

/**@brief Function for initializing the GATT module.
 */
static void gatt_init(void)
{
    ret_code_t err_code = nrf_ble_gatt_init(&m_gatt, gatt_evt_handler);
    APP_ERROR_CHECK(err_code);
}
//添加服务
static void services_init(void)
{
    ret_code_t         err_code;
    nrf_ble_qwr_init_t qwr_init = {0};

	ble_nus_init_t nus_init;
	uint8_t body_sensor_location;
	
    // Initialize Queued Write Module.
    qwr_init.error_handler = nrf_qwr_error_handler;

    err_code = nrf_ble_qwr_init(&m_qwr, &qwr_init);
    APP_ERROR_CHECK(err_code);
    
	nus_init.data_handler = ble_nus_data_handler;
	ble_nus_init(&m_nus_id, &nus_init);
}
```

如果characteristic_add返回NRF_ERROR_NO_MEM错误，要增加NRF_SDH_BLE_GATTS_ATTR_TAB_SIZE大小才行。

## 5.18fstorage用法

1.在keil5添加宏SOFTDEVICE_PRESENT

2.天假头文件

```c
#include "nrf_fstorage.h"
#include "nrf_fstorage_sd.h"
```

3.添加fstorage实例

```c
static void user_fds_event_handle(nrf_fstorage_evt_t *p_evt);
NRF_FSTORAGE_DEF(nrf_fstorage_t fstorage) =
{
    /* Set a handler for fstorage events. */
    .evt_handler = user_fds_event_handle,

    /* These below are the boundaries of the flash space assigned to this instance of fstorage.
     * You must set these manually, even at runtime, before nrf_fstorage_init() is called.
     * The function nrf5_flash_end_addr_get() can be used to retrieve the last address on the
     * last page of flash available to write data. */
    .start_addr = 0x3e000,
    .end_addr   = 0x3ffff,
};
```

4.定义测试数据

```c
static uint32_t m_data          = 0xBADC0FFE;
static char     m_hello_world[] = "hello world";
```

5.定义fstorage回调函数

```c
static void user_fds_event_handle(nrf_fstorage_evt_t *p_evt)
{
	if (p_evt->result != NRF_SUCCESS)
    {
        NRF_LOG_INFO("--> Event received: ERROR while executing an fstorage operation.");
        return;
    }

    switch (p_evt->id)
    {
        case NRF_FSTORAGE_EVT_WRITE_RESULT:
        {
            NRF_LOG_INFO("--> Event received: wrote %d bytes at address 0x%x.",
                         p_evt->len, p_evt->addr);
        } break;

        case NRF_FSTORAGE_EVT_ERASE_RESULT:
        {
            NRF_LOG_INFO("--> Event received: erased %d page from address 0x%x.",
                         p_evt->len, p_evt->addr);
        } break;

        default:
            break;
    }
}
```

6.定义一些功能函数

```c
static uint32_t nrf5_flash_end_addr_get()
{
    //该函数用于检测是否是最后一页
    uint32_t const bootloader_addr = BOOTLOADER_ADDRESS;
    uint32_t const page_sz         = NRF_FICR->CODEPAGESIZE;
    uint32_t const code_sz         = NRF_FICR->CODESIZE;

    return (bootloader_addr != 0xFFFFFFFF ?
            bootloader_addr : (code_sz * page_sz));
}

static void power_manage(void)
{
#ifdef SOFTDEVICE_PRESENT
    (void) sd_app_evt_wait();
#else
    __WFE();
#endif
}
//用于等待写入完成操作
void wait_for_flash_ready(nrf_fstorage_t const * p_fstorage)
{
  /* While fstorage is busy, sleep and wait for an event. */
  while (nrf_fstorage_is_busy(p_fstorage))
  {
    power_manage();
  }
}
static void print_flash_info(nrf_fstorage_t *p_fstorage)
{
    //打印一些信息
	NRF_LOG_INFO("=============| flash info |=============");
	NRF_LOG_INFO("erase unit: \t%d bytes", p_fstorage->p_flash_info->erase_unit);
	NRF_LOG_INFO("program unit: \t%d bytes", p_fstorage->p_flash_info->program_unit);
	NRF_LOG_INFO("========================================");
}
```

7.定义测试功能函数

```c
static void user_fds_test(void)
{
	nrf_fstorage_api_t * p_fs_api;
	ret_code_t err_code;
#ifdef SOFTDEVICE_PRESENT
	p_fs_api = &nrf_fstorage_sd;
#else
	p_fs_api = &nrf_fstorage_nvmc;
#endif

	err_code = nrf_fstorage_init(&fstorage, p_fs_api, NULL);
	APP_ERROR_CHECK(err_code);
	print_flash_info(&fstorage);
	(void)nrf5_flash_end_addr_get();
	NRF_LOG_INFO("Writing \"%x\" to flash", m_data);
	err_code = nrf_fstorage_write(&fstorage, 0x3e000, &m_data, sizeof(uint32_t), NULL);
	APP_ERROR_CHECK(err_code);
	wait_for_flash_ready(&fstorage);
	NRF_LOG_INFO("Done.");

	m_data = 0xDEFABC12;
	err_code = nrf_fstorage_write(&fstorage, 0x3e100, &m_data, sizeof(uint32_t), NULL);
	APP_ERROR_CHECK(err_code);
	wait_for_flash_ready(&fstorage);
	NRF_LOG_INFO("Done.");

	err_code = nrf_fstorage_write(&fstorage, 0x3f000, m_hello_world, sizeof(m_hello_world), NULL);
	APP_ERROR_CHECK(err_code);
	wait_for_flash_ready(&fstorage);
	NRF_LOG_INFO("Done.");

	NRF_LOG_INFO("read test");

	err_code = nrf_fstorage_read(&fstorage, 0x3e000, &m_data, sizeof(uint32_t));
	APP_ERROR_CHECK(err_code);
	NRF_LOG_INFO("read:%x",m_data);
	err_code = nrf_fstorage_read(&fstorage, 0x3e100, &m_data, sizeof(uint32_t));
	APP_ERROR_CHECK(err_code);
	NRF_LOG_INFO("read:%x",m_data);
	m_hello_world[0] = 'a';
	m_hello_world[1] = 'b';
	err_code = nrf_fstorage_read(&fstorage, 0x3f000, m_hello_world, sizeof(m_hello_world));
	APP_ERROR_CHECK(err_code);
	NRF_LOG_INFO("read:%s",m_hello_world);
	
}
```

8.在main.c中调用user_fds_test()即可。

## 5.19蓝牙MAC地址类型

蓝牙地址类型主要包含2类，一是public device address，而是random device address。地址共有48bits。random device address又分为static random device address和private device address。private device address又分为Non-resolvable private address和resolvable private address。

**public device address**：公共设备地址是需要购买的，要想IEEE申请，IEEE保证地址的唯一性。地址前高24bits是company id公司表示，低24bits由公司内部自己赋值。

**static random device address**：是设备上电后随机生成的。最高2个bit是11，剩下的46bit不能全是0或者全是1。未重新上电之前地址保持不变，在重新上电之后地址可以选择重新生成也可以选择保持不变。

**Non-resolvable private address**: 该地址和static random device address类似，区别只是该地址会定时更新，最高2个bits是00，更新周期由GAP规定，建议值是15分钟。

**Resolvable private address**: 该地址会根据安全等级进行加密，在进行连接时可以根据加密信息进行秘钥交换，确保安全连接。最高2个bits是10，高24bits是随机数部分，低24bits是随机数和（identity resolving key）IRK经过hash运算得到的hash值。

运算公式hash=ah(IRK, prand)，当对端BLE设备扫描到该类型地址后，会使用本地IRK和该prand进行同样的hash运算，将结果和地址中的hash字段比较，相同的时候才进行后续操作，这个过程叫做resolve（解析），如果不同会继续用下一个IRK重复resolve过程直到找到一个关联的IRK或者一个都没找到。该地址不能单独使用，需要同时具备public device address或者static device address中的一种。

从广播包中分析地址类型：

![image-20230406113851357](E:\databases\note\image-20230406113851357.png)

TxAdd代表发送方地址类型，0是public device address，1是random device address。

RxAdd代表接收方地址类型，在定向广播时才会出现RxAdd。

测试代码：

```c
void mac_set(void)
{
	ble_gap_addr_t addr;
	uint32_t err_code;
	
	//get ble default address
    err_code = sd_ble_gap_addr_get(&addr);
	APP_ERROR_CHECK(err_code);
	addr.addr_type = BLE_GAP_ADDR_TYPE_RANDOM_STATIC;
	addr.addr[BLE_GAP_ADDR_LEN-1] = 0xC0;
    err_code = sd_ble_gap_addr_set(&addr); 
	APP_ERROR_CHECK(err_code);
}
int main(void)
{
    bool erase_bonds;

    // Initialize.
    //user_uart_init();
    log_init();
    timers_init();
    buttons_leds_init(&erase_bonds);
    power_management_init();
    ble_stack_init();
    gap_params_init();
    gatt_init();
	services_init();
    advertising_init();
	mac_set();
    conn_params_init();
    peer_manager_init();

    // Start execution.
    NRF_LOG_INFO("Template example started.");
    application_timers_start();

    advertising_start(erase_bonds);
	//user_fds_test();
    // Enter main loop.
    for (;;)
    {
        idle_state_handle();
    }
}

```

![image-20230406121223170](E:\databases\note\image-20230406121223170.png)

## 5.20IBeacon应用

Beacon帧格式为

![image-20230407110807940](E:\databases\note\image-20230407110807940.png)

AD Field Length表示advertisement Data的长度，表示有用的广播信息长度。

Type表示advertisement type, 表示广播类型。这里使用厂家自定义ble_advdata_manuf_data_t数据，所以这里的Type是0xFF。

company ID表示公司标识，nordic公司是0x0059

IBeacon Type这里是固定值0x02，表示这是beacon设备

IBeacon Length表示剩下字段长度

UUID IBeacon这里写入ibeacon的UUID

Major表示分组号

Minor表示组内单元编号

TX Power表示1米处RSSI信号强度值

```c
#define APP_BEACON_INFO_LENGTH	0x17
#define APP_ADV_DATA_LENGTH		0x15
#define APP_DEVICE_TYPE			0x02
#define APP_MEASURED_RSSI		0xC3
#define APP_COMPANY_INDENTIFIER 0x0059
#define APP_MAJOR_VALUE			0x01,0x02
#define APP_MINOR_VALUE			0x03,0x04
#define APP_BEACON_UUID			0x01, 0x12, 0x23, 0x34, \
                                0x45, 0x56, 0x67, 0x78, \
                                0x89, 0x9a, 0xab, 0xbc, \
                                0xcd, 0xde, 0xef, 0xf0
                                
static uint8_t m_beacon_info[APP_BEACON_INFO_LENGTH] = 
{
	APP_DEVICE_TYPE,	//固定值0x02，代表这是一个beacon设备
	APP_ADV_DATA_LENGTH,//广播数据长度
	APP_BEACON_UUID,//beacon uuid
	APP_MAJOR_VALUE,//major
	APP_MINOR_VALUE,//minor
	APP_MEASURED_RSSI//1米处RSSI强度
};
```

设置广播包：

```c
static void advertising_init(void)
{
    ret_code_t             err_code;
    ble_advertising_init_t init;
	ble_advdata_manuf_data_t manuf_data;
    memset(&init, 0, sizeof(init));

	manuf_data.company_identifier = APP_COMPANY_INDENTIFIER;//设置公司标识
	manuf_data.data.p_data = m_beacon_info;//设置广播数据
	manuf_data.data.size = APP_BEACON_INFO_LENGTH;//设置广播数据长度
    init.advdata.name_type               = BLE_ADVDATA_NO_NAME;//设置广播包内不包含设备名以节省广播包空间
    init.advdata.include_appearance      = false;
    init.advdata.flags                   = BLE_GAP_ADV_FLAG_BR_EDR_NOT_SUPPORTED;//设置该广播包不支持BR/EDR
	...
    init.config.ble_adv_fast_enabled  = true;
    init.config.ble_adv_fast_interval = 100;//APP_ADV_INTERVAL;
    init.config.ble_adv_fast_timeout  = 0;//APP_ADV_DURATION;//设置一直广播
    ...
	init.advdata.p_manuf_specific_data = &manuf_data;
    err_code = ble_advertising_init(&m_advertising, &init);
    ...
}
```

编译烧录后抓取广播包如下：

![image-20230407114318187](E:\databases\note\image-20230407114318187.png)

广播包只有31字节，beacon信息已经差不多占满整个广播包了。如果希望在广播中继续添加数据，只能将数据放到广播回包中。下面将UUID放入广播回包如下。

```c
static void advertising_init(void)
{
    ret_code_t             err_code;
    ble_advertising_init_t init;
    ble_uuid_t adv_uuids[] = {{LED_KEY_UUID_SERVICE, mUser_led_key_id.uuid_type}};
    ...
    memset(&init, 0, sizeof(init));
...
    init.srdata.uuids_complete.uuid_cnt = sizeof(adv_uuids) / sizeof(adv_uuids[0]);
    init.srdata.uuids_complete.p_uuids  = adv_uuids;
...
    err_code = ble_advertising_init(&m_advertising, &init);
...
}
uint32_t ble_advertising_init(ble_advertising_t            * const p_advertising,
                              ble_advertising_init_t const * const p_init)
{
    ...
    p_advertising->adv_params.properties.type = BLE_GAP_ADV_TYPE_NONCONNECTABLE_SCANNABLE_UNDIRECTED;//将广播类型改为有回包类型
     ret = sd_ble_gap_adv_set_configure(&p_advertising->adv_handle, NULL, &p_advertising->adv_params);
    ...
}
```

## 5.21蓝牙协议栈下硬件定时器使用

RTC0, TIMER0被协议栈占用，RTC1被软件定时器使用。因此在使用协议栈时需要避开这3个外设。

1.使能定时器模块

![image-20230407120818906](E:\databases\note\image-20230407120818906.png)

2.添加nrfx_timer.c到工程中，定义一个定时器实例

![image-20230407130718770](E:\databases\note\image-20230407130718770.png)

```c
nrfx_timer_t m_timer1_id = NRFX_TIMER_INSTANCE(1);
```

定义定时器回调函数和初始化函数

```c
static void timer1_event_handler(nrf_timer_event_t event_type, void         *p_context)
{
	uint32_t ticks;
	switch(event_type)
	{
		case NRF_TIMER_EVENT_COMPARE0:
			nrf_gpio_pin_toggle(BSP_LED_1);
			NRF_LOG_INFO("timer1 handler");
			break;
	}
}
static void user_timer1_init(void)
{
	nrfx_err_t err_code;
	uint32_t ticks_ms;
	nrfx_timer_config_t config = NRFX_TIMER_DEFAULT_CONFIG;
	
	err_code = nrfx_timer_init(&m_timer1_id, &config, timer1_event_handler);
	APP_ERROR_CHECK(err_code);
	ticks_ms = nrfx_timer_ms_to_ticks(&m_timer1_id, 1000);//定时1000ms
	nrfx_timer_extended_compare(&m_timer1_id, NRF_TIMER_CC_CHANNEL0, ticks_ms, NRF_TIMER_SHORT_COMPARE0_CLEAR_MASK, true);//NRF_TIMER_SHORT_COMPARE0_CLEAR_MASK:周期性定时，NRF_TIMER_SHORT_COMPARE0_STOP_MASK:单次定时
	nrfx_timer_enable(&m_timer1_id);
}
```

## 5.22蓝牙防丢器应用实例

1.使能相应模块

![image-20230407230932926](E:\databases\note\image-20230407230932926.png)

![image-20230407231142338](E:\databases\note\image-20230407231142338.png)

2.在sdk_config.h添加模块

```c
// <e> BLE_DB_DISCOVERY_ENABLED - ble db discovery - Ble Db Discovery
//==========================================================
#ifndef BLE_DB_DISCOVERY_ENABLED
#define BLE_DB_DISCOVERY_ENABLED 1
#endif
// </e>
// <e> NRF_BLE_GQ_ENABLED - nrf_ble_gq - BLE GATT Queue Module
//==========================================================
#ifndef NRF_BLE_GQ_ENABLED
#define NRF_BLE_GQ_ENABLED 1
#endif
// <o> NRF_BLE_GQ_DATAPOOL_ELEMENT_SIZE - Default size of a single element in the pool of memory objects.
#ifndef NRF_BLE_GQ_DATAPOOL_ELEMENT_SIZE
#define NRF_BLE_GQ_DATAPOOL_ELEMENT_SIZE 20
#endif

// <o> NRF_BLE_GQ_DATAPOOL_ELEMENT_COUNT - Default number of elements in the pool of memory objects.
#ifndef NRF_BLE_GQ_DATAPOOL_ELEMENT_COUNT
#define NRF_BLE_GQ_DATAPOOL_ELEMENT_COUNT 8
#endif

// <o> NRF_BLE_GQ_GATTC_WRITE_MAX_DATA_LEN - Maximal size of the data inside GATTC write request (in bytes).
#ifndef NRF_BLE_GQ_GATTC_WRITE_MAX_DATA_LEN
#define NRF_BLE_GQ_GATTC_WRITE_MAX_DATA_LEN 2
#endif

// <o> NRF_BLE_GQ_GATTS_HVX_MAX_DATA_LEN - Maximal size of the data inside GATTC notification or indication request (in bytes).
#ifndef NRF_BLE_GQ_GATTS_HVX_MAX_DATA_LEN
#define NRF_BLE_GQ_GATTS_HVX_MAX_DATA_LEN 16
#endif

// </e>
```

3.添加头文件编译路径

![image-20230407231343540](E:\databases\note\image-20230407231343540.png)

4.添加.c文件

![image-20230407231447391](E:\databases\note\image-20230407231447391.png)

5.声明服务实例

```c
#include "ble_bas.h"
#include "ble_ias.h"
#include "ble_ias_c.h"
#include "ble_lls.h"
#include "ble_tps.h"

BLE_BAS_DEF(m_bas_id);
BLE_IAS_DEF(m_ias_id, 1);
BLE_IAS_C_DEF(m_ias_c_id);
BLE_LLS_DEF(m_lls_id);
BLE_TPS_DEF(m_tps_id);
```

6.添加服务

```c
#define TX_POWER_LEVEL		-4
static void services_init(void)
{
    ret_code_t         err_code;
    nrf_ble_qwr_init_t qwr_init = {0};
	ble_bas_init_t bas_init;
	ble_ias_init_t ias_init;
	ble_lls_init_t lls_init;
	ble_tps_init_t tps_init;

    // Initialize Queued Write Module.
    ...
	memset(&bas_init, 0, sizeof(ble_bas_init_t));
	bas_init.evt_handler = ble_bas_evt_handler;
	bas_init.support_notification = true;
	bas_init.p_report_ref = NULL;
	bas_init.initial_batt_level = 100;
	bas_init.bl_cccd_wr_sec = SEC_OPEN;
	bas_init.bl_rd_sec = SEC_OPEN;
	bas_init.bl_report_rd_sec = SEC_OPEN;
	ble_bas_init(&m_bas_id, &bas_init);

	memset(&ias_init, 0, sizeof(ble_ias_init_t));
	ias_init.alert_wr_sec = SEC_OPEN;
	ias_init.evt_handler = ble_ias_evt_handler;
	ble_ias_init(&m_ias_id, &ias_init);
	
	memset(&lls_init, 0, sizeof(ble_lls_init_t));
	lls_init.alert_level_rd_sec = SEC_OPEN;
	lls_init.alert_level_wr_sec = SEC_OPEN;
	lls_init.initial_alert_level = BLE_CHAR_ALERT_LEVEL_NO_ALERT;
	lls_init.evt_handler = ble_lls_evt_handler;
	lls_init.error_handler = ble_srv_error_handler;
	ble_lls_init(&m_lls_id, &lls_init);
	
	memset(&tps_init, 0, sizeof(ble_tps_init_t));
	tps_init.initial_tx_power_level = TX_POWER_LEVEL;
	tps_init.tpl_rd_sec = SEC_OPEN;
	ble_tps_init(&m_tps_id, &tps_init);
}

static void alert_signal(uint8_t alert_level)
{
	app_timer_stop(mUser_led_timer_id);
	switch ( alert_level )
	{
	    case  BLE_CHAR_ALERT_LEVEL_NO_ALERT:
	        nrf_gpio_pin_set(BSP_LED_1);
	        break;
	    case  BLE_CHAR_ALERT_LEVEL_MILD_ALERT:
			app_timer_start(mUser_led_timer_id, LED_INTERVAL_LOW, NULL);
	        break;
	    case  BLE_CHAR_ALERT_LEVEL_HIGH_ALERT:
			app_timer_start(mUser_led_timer_id, LED_INTERVAL_FAST, NULL);
	        break;
	    default:
	    	//lose
			nrf_gpio_pin_clear(BSP_LED_1);
	        break;
	}
}
void ble_bas_evt_handler(ble_bas_t * p_bas, ble_bas_evt_t * p_evt)
{
	ret_code_t err_code;
	UNUSED_PARAMETER(p_bas);
	
	switch (p_evt->evt_type)
	{
		case BLE_BAS_EVT_NOTIFICATION_ENABLED:
			err_code = app_timer_start(mUser_battery_timer_id, BATTERY_LEVEL_MEAS_INTERVAL, NULL);
			APP_ERROR_CHECK(err_code);
			break;
		case BLE_BAS_EVT_NOTIFICATION_DISABLED:
			err_code = app_timer_stop(mUser_battery_timer_id);
			APP_ERROR_CHECK(err_code);
			break;
		default:
			break;
	}
	
}
void ble_ias_evt_handler(ble_ias_t * p_ias, ble_ias_evt_t * p_evt)
{
	switch ( p_evt->evt_type )
	{
	    case BLE_IAS_EVT_ALERT_LEVEL_UPDATED:
			alert_signal(p_evt->p_link_ctx->alert_level);
	        break;
	    default:
	        break;
	}
}
void ble_lls_evt_handler(ble_lls_t * p_lls, ble_lls_evt_t * p_evt)
{
	switch ( p_evt->evt_type )
	{
	    case  BLE_LLS_EVT_LINK_LOSS_ALERT:
	        alert_signal(p_evt->params.alert_level);
	        break;
	    default:
	        break;
	}
}
void ble_srv_error_handler(uint32_t nrf_error)
{
	NRF_LOG_ERROR("nrf_error:%x",nrf_error);
}


uint32_t ble_advertising_init(ble_advertising_t            * const p_advertising,
                              ble_advertising_init_t const * const p_init)
{
    uint32_t ret;
   ...
    ret = sd_ble_gap_adv_set_configure(&p_advertising->adv_handle, NULL, &p_advertising->adv_params);
    VERIFY_SUCCESS(ret);
    //注意sd_ble_gap_tx_power_set函数调用必须在ble_advertising_start之前，其它具体看官方文档
	ret = sd_ble_gap_tx_power_set(BLE_GAP_TX_POWER_ROLE_ADV, p_advertising->adv_handle, -4);
	VERIFY_SUCCESS(ret);
    p_advertising->initialized = true;
    return ret;
}
```

## 5.23DFU介绍

DFU(Device Firmware Update), 设备固件升级。OTA(Over the Air)是DFU的一种类型, OTA的全称应该是OTA DFU, OTA代表固件空中升级。DFU除了可以通过无线方式OTA进行升级，也可以通过有线方式升级，比如UART, USB, SPI等。

DFU可以采用dual bank或者single bank模式，dual bank的做法是升级时系统先进入bootloader, 然后把新固件下载下来并校验成功，然后擦除老固件并升级新固件。dual bank方式虽然牺牲了很多存储空间，但是换来了更好的升级体验。

single bank的做法是升级时系统先进入bootloader，然后立马擦除老固件，直接升级新固件。

single bank相比dual bank可以节省很多flash空间，在系统资源比较紧张的时候推荐single bank。不管是single bank还是dual bank，在升级过程中出现问题后都可以进行二次升级。dual bank在升级过程中出现问题或者新固件有问题，还可以继续使用老固件，single bank则只能一直停留在bootloader中等待二次或多次升级，设备无法正常工作。

**dual bank flash布局**

![image-20230415114233175](E:\databases\note\image-20230415114233175.png)

在flash中开辟一个Free区域，将新固件下载到Free区域中，如果下载完成校验OK，然后再替旧固件Application。

**single bank flash布局**

![image-20230415114611956](E:\databases\note\image-20230415114611956.png)

程序烧录过程中直接擦除旧固件Application，将新固件烧录进来。

bootloader和SoftDevice只能使用dual bank模式，因为使用single bank模式一旦烧录过程出现问题或者固件有问题，设备就无法启动了，只能使用flash工具重新烧写。Application可以使用dual bank或者single bank。

**DFU dual bank升级流程**

1.烧录bootloader程序后，设备会进入DFU模式。设备上电后会先运行bootloader，bootloader会检查bank0是否有应用程序，如果没有也会进入DFU模式否则会执行应用程序。

2.bootloader进入DFU模式会擦除Bank1区域，新固件校验成功才会擦除Bank0区域。

3.将接收到的数据写入Bank1

4.接收完成并校验成功，擦除Bank0，将Bank1的数据拷贝到Bank0.

5.拷贝完成后运行Bank0应用程序，Bank1中的数据不会被擦除，需要等下次进入bootloader DFU模式才擦除。

6.如果设置了将旧应用程序的数据保留，新的应用程序会将其数据在原有数据存储空间上叠加存储，不会覆盖。

**非按键式(Buttonless)DFU OTA升级**

参考内容：https://devzone.nordicsemi.com/guides/short-range-guides/b/software-development-kit/posts/nrf5-sdk-v17-1-0-secure-dfu-hands-on-tutorial

1.window下载nRF Connect for Desktop，安装好之后安装Programmer工具。

2.安卓下载nRF Connect APP.

3.安卓下载nRF Toolbox APP

4.安装MinGW

![image-20230416125125497](E:\databases\note\image-20230416125125497.png)

点击installation>apply changes.

安装完成双击C:\MinGW\msys\1.0\msys.bat，切换到工程目录nRF5_SDK_17.1.0_ddde560\external\micro-ecc\nrf52hf_keil\armgcc下执行make编译生成micro_ecc_lib_nrf52.lib。

从github上下载[pc-nrfutil](https://github.com/NordicSemiconductor/pc-nrfutil), 用命令行进入pc-nrfutil文件夹执行命令python setup.py install.安装nrfutil。安装参考[教程](https://blog.csdn.net/kangweijian/article/details/129414340)如下:

1.下载python3.7.3版本

2.安装python之后运行命令更新pip版本

```python
python -m pip install --upgrade pip
```

3.运行命令将pip源更换为国内，否则直接运行python setup.py install安装nrfutil可能会出现安装时间太久甚至有些包无法找到下载安装。

```python
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

4.更换为国内源之后，运行命令安装nrfutil

```python
python setup.py install
```

安装完成运行命令nrfutil出现如下画面，正面安装成功，如果过程出现安装失败的情况需要多运行几次python setup.py install命令。

![image-20230419013141753](E:\databases\note\image-20230419013141753.png)

5.运行命令生成private key，生成的private.key必须要保存起来

```python
nrfutil.exe keys generate E:\databases\blueTooth\key\private.key
```

6.运行命令生成public key

```python
nrfutil keys display --key pk --format code E:\databases\blueTooth\key\private.key --out_file E:\databases\blueTooth\key\public_key.c
```



查看协议栈FWID参考这里https://devzone.nordicsemi.com/f/nordic-q-a/1171/how-do-i-access-softdevice-version-string。

使用命令行打开nrfjprog，用命令擦除全部

```python
nrfjprog -e
```

使用命令烧录协议栈

```python
nrfjprog --program E:\keil5_projects\DeviceDownload\nRF5_SDK_17.1.0_ddde560\components\softdevice\s132\hex\s132_nrf52_7.2.0_softdevice.hex --verify
```

使用命令读取协议栈版本ID，读取回来低16bits就是协议栈版本ID，例如协议栈s132_nrf52_7.2.0_softdevice.hex，读取回来就是0x0000300C: FFFF0101,其中ID=0x101

```python
nrfjprog --family NRF52 --memrd 0x0000300C
```

接下来使用命令生成.zip压缩包

```python
nrfutil pkg generate --hw-version 52 --application-version 1 --application app.hex --sd-req 0x101 --key-file private.key test_Dfu17.zip
```

hw-version 52: 这是硬件版本，指的是NRF52系列，如果烧录的是NRF51系列，这里要改成51。

application-version 1:这个是应用版本，由用户自定义。

--sd-req 0x101: 这是协议栈版本ID。不同的协议栈需要烧录不同的ID

其中boot.hex从nRF5_SDK_17.1.0_ddde560\examples\dfu\secure_bootloader\pca10040_s132_ble工程中编译生成。

app.hex从nRF5_SDK_17.1.0_ddde560\examples\ble_peripheral\ble_app_buttonless_dfu\pca10040\s132工程中编译生成。

生成test_Dfu17.zip之后。使用命令擦除重新烧录

```python
nrfjprog -e && nrfjprog --program s132_nrf52_7.2.0_softdevice.hex && nrfjprog --program boot.hex && nrfjprog --program app.hex && nrfjprog -r
```

烧录后用nRF Connect APP搜索DfuTarg设备并连接。此时设备处于bootloader模式。

连接后点DFU，选择刚刚生成的zip文件升级

![image-20230419210606564](E:\databases\note\image-20230419210606564.png)

升级完成后会自动断开连接，再次搜索会出现Nordic_Buttonless，说明OTA升级成功。进入application模式。

![image-20230419210805952](E:\databases\note\image-20230419210805952.png)

如果要重新进入bootloader模式，只需要点击CONNECT重新连接设备，然后使能指示并发送命令。重新扫描发现设备名称又变回DfuTarg，说明成功回到bootloader模式。

![image-20230419211654125](E:\databases\note\image-20230419211654125.png)

**hex的烧录与合并setting文件生成与使用**

setting文件的目的是在批量生成的时候，下载后就可以直接运行到application，而 不是和上面的那样先进入bootloader然后再OTA一次才能进入application。

使用命令生成app_setting,hex.

```python
nrfutil settings generate --family NRF52 --application app.hex --application-version 1 --bootloader-version 1 --bl-settings-version 1 app_setting.hex
#其中--application-version是application版本号，由用户自定义
#--bootloader-version是bootloader版本号，由用户自定义
#--bl-settings-version是setting版本号，由用户自定义
```

如果出现错误：

```python
ERROR: JLinkARM DLL reported an error. Try again. If error condition
ERROR: persists, run the same command again with argument --log, contact Nordic
ERROR: Semiconductor and provide the generated log.log file to them.
```

可能原因是板子接触不良，需要重新插拔几次烧录线。

烧录需要按以下步骤进行：

```python
1.擦除flash
nrfjprog -e
2.烧录协议栈
nrfjprog --program s132_nrf52_7.2.0_softdevice.hex
3.烧录setting
nrfjprog --program app_setting.hex
4.烧录bootloader
nrfjprog --program boot.hex
5.烧录application
nrfjprog --program app.hex
```

为了进一步简化生产步骤，我们可以把多个hex合并为一个hex，使用nrf5x command line tool工具里的mergehex指令。该指令一次最多可以合并3个hex，4个hex需要分两次合并。

1.合并协议栈hex，boot hex，应用hex，使用命令

```python
mergehex --merge s132_nrf52_7.2.0_softdevice.hex boot.hex app.hex --output output3tol.hex

mergehex --merge output3tol.hex app_setting.hex --output output4tol.hex
```

合并后直接使用命令烧录

```python
nrfjprog --program output4tol.hex
nrfjprog -r
```

**DFU移植**

1.使能DFU服务

![image-20230420004859977](E:\databases\note\image-20230420004859977.png)

2.添加绑定功能

![image-20230420005224890](E:\databases\note\image-20230420005224890.png)

3.添加FDS和CRC功能

![image-20230420005409765](E:\databases\note\image-20230420005409765.png)

4.更改协议栈初始化参数

![image-20230420005708555](E:\databases\note\image-20230420005708555.png)

5.添加.c文件

![image-20230420010035983](E:\databases\note\image-20230420010035983.png)



![image-20230420010455807](E:\databases\note\image-20230420010455807.png)



![image-20230420010644131](E:\databases\note\image-20230420010644131.png)

![image-20230420011005999](E:\databases\note\image-20230420011005999.png)

如果出现错误，需要在keil添加宏

```c
..\..\..\..\..\..\components\ble\ble_services\ble_dfu\ble_dfu_bonded.c(63): error:  #20: identifier "nrf_dfu_set_peer_data_svci_async_t" is undefined
```

```c
NRF_DFU_TRANSPORT_BLE=1 BL_SETTINGS_ACCESS_ONLY
```





# 6.AutoCAD学习笔记

## 6.1画线

CAD画线快捷键是L+空格

![image-20220923002433384](E:\databases\note\image-20220923002433384.png)

输入坐标20,30。其中x=20，y=30

![image-20220923002636309](E:\databases\note\image-20220923002636309.png)

相对于上次坐标的坐标偏移设置，相当于x=20+20=40，y=30+30=60

![image-20220923002845050](E:\databases\note\image-20220923002845050.png)

20<30。20表示该点到坐标原点的距离，30表示该点与原点连线和X轴正向夹角为30°

![image-20220923003007832](E:\databases\note\image-20220923003007832.png)

@20<60。20表示该点与前一点距离为20，60表示该点与前一点连线和X轴正向夹角为60°

![image-20220923004708844](E:\databases\note\image-20220923004708844.png)

## 6.2图形单位设置

设置图形单位快捷键UN+空格

![image-20220924001703817](E:\databases\note\image-20220924001703817.png)

## 6.3设置图形界面

A3图形大小：420x297

A4图形大小：297x210

设置A4图形界面：

输入LIMITS+空格，输入图形左下点坐标+空格，输入图形右上角+空格

## 6.4设置图层

点击图层特性，打开图层设置

![image-20220924003544415](E:\databases\note\image-20220924003544415.png)

点击图标添加图层

![image-20220924003733095](E:\databases\note\image-20220924003733095.png)

## 6.5设置样板图

设置样板图步骤：

1.设置单位（UN+Space）

2.设置图形界面（LIMITS+Space）

3.添加图层

4.保存文件为.dwt格式



# 7.USB学习笔记

USB接口类型主要分为三类：TYPE A, TYPE B, TYPE C

USB传输速度：低速1.5M/bps, 全速12M/bps, 高速480M/bps，低速上拉电阻加在D-线上，高速和全速上拉电阻加在D+线上。

USB的Hub最多可带127个外设

![img](https://www.usbzh.com/uploadimg/202202/232526132916.jpg)

![img](https://www.usbzh.com/uploadimg/202202/232239921302.jpg)

bInterfaceClass的典型代码为1，2，3，6，7，8，9，10，11，255。分别代表意思为
1－audio：表示一个音频设备。
2－communication device：通讯设备，如电话，moden等等。
3－[HID](https://www.usbzh.com/article/detail-76.html)：人机交互设备，如键盘，鼠标等。
6－image图象设备，如扫描仪，摄像头等，有时数码相 机也可归到这一类。
7－打印机类。如单向，双向打印机等。
8－mass storage海量存储类。所有带有一定存储功能的都可以归到这一类。如数码相机大多数都归这一类。
9－hub类, [集线器](https://www.usbzh.com/article/detail-25.html)。
11－chip card/smart card。
255－vendor specific.厂家的自定义类，主要用于一些特殊的设备。如接口转接卡等。

## 7.1USB设备的枚举过程

1.USB设备插入USB接口后，主机检测D+/D-线上的电压，确认有设备连接，USB[集线器](https://www.usbzh.com/article/detail-25.html)通过中断[IN](https://www.usbzh.com/article/detail-450.html)通道，向主机报告有USB设备连接

2.主机接到通知后，通过[集线器](https://www.usbzh.com/article/detail-25.html)设备类请求GetPortStatus获取更多的信息。然后主机等待100ms等待设备稳定，然后发送[集线器](https://www.usbzh.com/article/detail-25.html)设备类请求SetPortStatus,对USB设备进行复位，复位后USB设备的地址为0，这样主机就可以使用地址0与USB设备进行通信,复位后的设备可以从USB总线上获取小于100mA的电流，用于使用默认地址对管道0控制[事务](https://www.usbzh.com/article/detail-691.html)响应。

3.主机向地址为0（即刚插入的USB设备）的设备端点0（默认端点）发送获取设备描述符的标准请求GetDescriptor。

4.USB设备收到请求后，将其预设的设备描述符返回给主机。

5.主机收到设备描述符后，返回一个0长度的数据确认包。

6.主机对设备再次复位，复位后主机对地址为0的设备端点0发送一个设置地址SetAddress请求（新的设备地址在数据包中）。

7.主机发送请求状态返回，设备返回0长度的状态数据包。

8.主机收到状态数据包后，发送应答包ACK给设备，设备收到ACK后，启用新的设备地址。

9.主机再次使新的地址获取设备描述符GetDescriptor，设备返回设备描述符。

10.主机获取第一次配置描述符有前18个字节，设备返回配置描述符的前18个字节，其数据包中含有配置描述符的总长度。

11.主机根据配置描述符的总长度再次获取配置描述符，设备返回全总的配置描述符。

12.如果还有字符串描述符，系统还会获取字符串描述符。像HID设备还有报告描述符，它也需要单独获取。

## 7.2USB设备的断开

USB设备从USB总线断开时，包括以下几个步骤：

1.USB设备从集线器下行端口断开时，集线器禁止该端口，并通过中断IN通道向USB主机报告其端口变化。

2.主机收到端口变化后发送GetPortStatus获取详细信息，并做处理断开操作。

3.系统调用USB驱动程序的断开回调函数，释放该设备占用的所有系统资源。

参考资料：

https://www.usbzh.com/article/detail-110.html

windows系统中设备描述符的结构体定义如下：

```c
struct _DEVICE_DESCRIPTOR_STRUCT 
{ 
    BYTE bLength;           //设备描述符的字节数大小，为0x12 
    BYTE bDescriptorType;   //描述符类型编号，为0x01 
    WORD bcdUSB;            //USB版本号 
    BYTE bDeviceClass;      //USB分配的设备类代码，0x01~0xfe为标准设备类，0xff为厂商自定义类型 
                            //0x00不是在设备描述符中定义的，如HID 
    BYTE bDeviceSubClass;   //usb分配的子类代码，同上，值由USB规定和分配的 
    BYTE bDeviceProtocol;   //USB分配的设备协议代码，同上 
    BYTE bMaxPacketSize0;   //端点0的最大包的大小 
    WORD idVendor;          //厂商编号 
    WORD idProduct;         //产品编号 
    WORD bcdDevice;         //设备出厂编号 
    BYTE iManufacturer;     //描述厂商字符串的索引 
    BYTE iProduct;          //描述产品字符串的索引 
    BYTE iSerialNumber;     //描述设备序列号字符串的索引 
    BYTE bNumConfiguration; //可能的配置数量 
}
```

设备描述符含义：

- bLength : 描述符大小．固定为0x12．
- bDescriptorType : 设备描述符类型．固定为0x01．
- bcdUSB : USB 规范发布号．表示了本设备能适用于那种协议，如2.0=0200，1.1=0110等．
- bDeviceClass : 类型代码（由USB指定）。当它的值是0时，表示所有接口在[配置描述符](https://www.usbzh.com/article/detail-67.html)里，并且所有接口是独立的。当它的值是1到FEH时，表示不同的接口关联的。当它的值是FFH时，它是厂商自己定义的．
- bDeviceSubClass : 子类型代码（由USB分配）．如果bDeviceClass值是0，一定要设置为0．其它情况就跟据USB-IF组织定义的编码．
- bDeviceProtocol : 协议代码（由USB分配）．如果使用USB-IF组织定义的协议，就需要设置这里的值，否则直接设置为0。如果厂商自己定义的可以设置为FFH．
- bMaxPacketSize0 : 端点０最大分组大小（只有8,16,32,64有效）．
- [idVendor](https://www.usbzh.com/article/detail-953.html) : 供应商ID（由USB分配）．
- idProduct : 产品ID（由厂商分配）．由供应商ID和产品ID，就可以让操作系统加载不同的驱动程序．
- bcdDevice : 设备出产编码．由厂家自行设置．
- iManufacturer : 厂商描述符字符串索引．索引到对应的[字符串描述符](https://www.usbzh.com/article/detail-53.html)． 为０则表示没有．
- iProduct : :产品描述符字符串索引．同上．
- iSerialNumber : 设备序列号字符串索引．同上．
- bNumConfigurations : 可能的配置数．定义设备以当前速度支持的配置数量

配置描述符定义：

```c
struct _CONFIGURATION_DESCRIPTOR_STRUCT 
{ 
  BYTE bLength;           //配置描述符的字节数大小，固定为9字节
  BYTE bDescriptorType;   //描述符类型编号，为0x02 
  WORD wTotalLength;     //配置所返回的所有数量的大小 
  BYTE bNumInterface;     //此配置所支持的接口数量 
  BYTE bConfigurationVale;   //Set_Configuration命令需要的参数值 
  BYTE iConfiguration;       //描述该配置的字符串的索引值 
  BYTE bmAttribute;           //供电模式的选择 
  BYTE MaxPower;             //设备从总线提取的最大电流 
}CONFIGURATION_DESCRIPTOR_STRUCT
```

- bLength : 描述符大小．固定为0x09．

- bDescriptorType : 配置描述符类型．固定为0x02．

- wTotalLength : 返回整个数据的长度．指此配置返回的配置描述符，[接口描述符](https://www.usbzh.com/article/detail-64.html)以及[端点描述符](https://www.usbzh.com/article/detail-56.html)的全部大小．

- bNumInterfaces : 配置所支持的接口数．指该配置配备的接口数量，也表示该配置下接口描述符数量．

- bConfigurationValue : 作为Set Configuration的一个参数选择配置值．

- iConfiguration : 用于描述该配置[字符串描述符](https://www.usbzh.com/article/detail-53.html)的索引．

- bmAttributes : 供电模式选择．Bit4-0保留，D7:总线供电，D6:自供电，D5:远程唤醒．

- MaxPower : 总线供电的USB设备的最大消耗电流．以2mA为单位．

- 接口描述符：接口描述符说明了接口所提供的配置，一个配置所拥有的接口数量通过配置描述符的bNumInterfaces决定。

  接口描述符定义：

  ```c
  struct _INTERFACE_DESCRIPTOR_STRUCT 
  { 
      BYTE bLength;           //设备描述符的字节数大小，为0x09 
      BYTE bDescriptorType;   //描述符类型编号，为0x04
      BYTE bInterfaceNumber; //接口的编号 
      BYTE bAlternateSetting;//备用的接口描述符编号 
      BYTE bNumEndpoints;     //该接口使用端点数，不包括端点0 
      BYTE bInterfaceClass;   //接口类型 
      BYTE bInterfaceSubClass;//接口子类型 
      BYTE bInterfaceProtocol;//接口所遵循的协议 
      BYTE iInterface;         //描述该接口的字符串索引值 
  }INTERFACE_DESCRIPTOR_STRUCT
  ```

  - bLength : 描述符大小．固定为0x09．

  - bDescriptorType : 接口描述符类型．固定为0x04．

  - bInterfaceNumber: 该接口的编号．

  - bAlternateSetting : 用于为上一个字段选择可供替换的位置．即备用的接口描述符标号．

  - bNumEndpoint : 使用的端点数目．端点０除外．

  - bInterfaceClass : 类型代码（由USB分配）．

  - bInterfaceSubClass : 子类型代码（由USB分配）．

  - bInterfaceProtocol : 协议代码（由USB分配）．

  - iInterface : [字符串描述符](https://www.usbzh.com/article/detail-53.html)的索引

    接口关联描述符定义：

    ```c
    typedef struct _USB_INTERFACE_ASSOCIATION_DESCRIPTOR {
        UCHAR   bLength;            //长度为8
        UCHAR   bDescriptorType;    //USB_INTERFACE_ASSOCIATION_DESCRIPTOR_TYPE，值为0x0b
        UCHAR   bFirstInterface;    //第一个接口编号
        UCHAR   bInterfaceCount;    //接口总数量
        UCHAR   bFunctionClass;        //视频接口类代码CC_VIDEO，值0x0E
        UCHAR   bFunctionSubClass;    //视频子类接口代码 SC_VIDEO_INTERFACE_COLLECTION,值为0x03
        UCHAR   bFunctionProtocol;     //未用，必须为PC_PROTOCOL_UNDEFINED，值为0x00
        UCHAR   iFunction;            //字符串描述符索引
    } USB_INTERFACE_ASSOCIATION_DESCRIPTOR, *PUSB_INTERFACE_ASSOCIATION_DESCRIPTOR;
    ```

    端点描述符定义：

    ```c
    struct _ENDPOIN_DESCRIPTOR_STRUCT 
    { 
        BYTE bLength;           //设备描述符的字节数大小，为0x7 
        BYTE bDescriptorType;   //描述符类型编号，为0x05
        BYTE bEndpointAddress; //端点地址及输入输出属性 
        BYTE bmAttribute;       //端点的传输类型属性 
        WORD wMaxPacketSize;   //端点收、发的最大包的大小 
        BYTE bInterval;         //主机查询端点的时间间隔 
    } ENDPOIN_DESCRIPTOR_STRUCT ；
    ```

    - bLength : 描述符大小．固定为0x07．

    - bDescriptorType : [接口描述符](https://www.usbzh.com/article/detail-64.html)类型．固定为0x05．

    - bEndpointAddress : USB设备的端点地址．Bit7，方向，对于控制端点可以忽略，1/0:[IN](https://www.usbzh.com/article/detail-450.html)/[OUT](https://www.usbzh.com/article/detail-449.html)．Bit6-4，保留．BIt3-0：端点号．

    - bmAttributes : 端点属性．Bit7-2，保留（同步有定义）．BIt1-0：00控制，01同步，02批量，03中断．

      当为同步传输时，bEndpointType的bit3-2的值不同代表的含义不同：

      00：无同步
      01：异步
      10：适配
      11：同步
      BIT5:4
      00: 表示数据端点
      01：表示反馈端点Feedback endpoint
      10：表示隐式反馈数据端点 Implicit feedback Data endpoint
      11:保留

      wMaxPacketSize : 本端点接收或发送的最大信息包大小．

      USB2.0时：

      对于同步端点，此值用于指示主机在调度中保留的总线时间，这是每(微)帧数据有效负载所需的时间，有效负载时间就是发送一帧数据需要占用的总线时间，在实际数据传输过程中，管道实际使用的带宽可能比保留的带宽少，大家想想，如果实际使用的带宽比保留的还多，那就丢数了；
      对于其类型的端点，bit10~bit0指定最大数据包大小(以字节为单位)；
      bit12~bit11对于[高速](https://www.usbzh.com/article/detail-852.html)传输的同步和中断端点有效：bit12~bit11可指定每个微帧的额外通信次数，这里大家一定要知道是在[高速](https://www.usbzh.com/article/detail-852.html)传输中，当一个[事务](https://www.usbzh.com/article/detail-691.html)超时时，在一个微帧时间内重传的次数，如果设置为00b（None），则表示在一个微帧内只传输一个[事务](https://www.usbzh.com/article/detail-691.html)，不进行额外的超时重传，如果设置为01b，则表示在一个微帧内可以传输两次[事务](https://www.usbzh.com/article/detail-691.html)，有一次额外的重传机会，从下面可以看出，一个微帧最多可以有两次重传事务的机会，如果微帧结束了还是失败，就需要等到下一个微帧继续发送该事务；

      USB3.0时：

      wMaxPacketSize表示包的大小。对于bulk为1024，而对于[同步传输](https://www.usbzh.com/article/detail-118.html)，可以为0~1024或 1024。

      [bInterval](https://www.usbzh.com/article/detail-637.html) : 轮询数据传送端点的时间间隔．对于批量传送和控制传送的端点忽略．对于同步传送的端点，必须为１，对于中断传送的端点，范围为1-255．

      对于[全速](https://www.usbzh.com/article/detail-851.html)/[高速](https://www.usbzh.com/article/detail-852.html)同步端点，此值必须在1到16之间。[bInterval](https://www.usbzh.com/article/detail-637.html)值用作2的指数，例如bInterval为4，表示周期为8个单位；
      对于[全速](https://www.usbzh.com/article/detail-851.html)/低速中断端点，该字段的值可以是1到255，也就是主机多少ms给设备发一次数据请求；
      对于高速中断端点，使用bInterval值作为2的指数，例如bInterval为4表示周期为8。这个值必须在1到16之间；
      对于高速批量/控制输出端点，bInterval必须指定端点的最大[NAK](https://www.usbzh.com/article/detail-453.html)速率。值0表示端点永不[NAK](https://www.usbzh.com/article/detail-453.html)。其它值表示每个微帧的bInterval*125us时间最多1个[NAK](https://www.usbzh.com/article/detail-453.html)。这个值的范围必须在0到255之间；
      00 = None (1 transaction per microframe)
      01 = 1 additional (2 per microframe)
      10 = 2 additional (3 per microframe)
      11 = Reserved
      其它位默认为0，
      对于[全速](https://www.usbzh.com/article/detail-851.html)/低速批量/控制输出端点，此值无意义，可以任意指定。





















面试要点：

1.C语言基础

变量类型用法，字节对齐，变量类型大小，函数类型



函数指针：void (\*pfun)(int),

 typedef void (*led_write_handler_t)(uint16_t conn_handle, user_led_key_t *p_led, uint8_t new_state);

led_write_handler_t led_write_handler;

指针函数：void *pfun(int)

常量指针：char *const ptr，指向字符串的指针，并且指针初始化后不可修改

指针常量：char const *ptr等价于const char *ptr，指向常量字符串，字符串的内容不可修改，但指针指向地址可修改

在32位内核处理器中

struct dteststr
{
	int idt;
	short sdt;
	char *pstr;
	char app;
};

struct dtestst2
{
	int idt;
	char *pstr;
	char app;
	short sdt;
};

char *pstr;

char ch;

short sh;

int idt;

long ldt;

由于需要4字节对齐，所以sizeof(struct dteststr)=16, sizeof(dtestst2)=12, sizeof(pstr)=4, sizeof(ch)=1,sizeof(short)=2,sizeof(int)=4,sizeof(long)=4.



2.单模双模概念

单模是指蓝牙仅支持BLE，双模指的是既支持经典蓝牙Basic Rate(BR)和增强速率EDR也支持最新的低功耗LE标准

以下商标只有SMART是单模，SMART READY是双模

![image-20230413212637069](E:\databases\note\image-20230413212637069.png)



蓝牙Basic Rate（BR）是蓝牙传输技术中的一种传输模式，也称为蓝牙基本速率模式。它是蓝牙1.0和1.1版本中使用的传输模式，传输速率为1Mbps。BR模式采用的是高频率跳频技术，将传输信道分成多个子信道，并在不同的子信道之间进行跳跃，以减少干扰和提高传输稳定性。

由于BR模式传输速率较低，适用于传输较少的数据量，如语音通话、简单文本消息等。随着蓝牙技术的发展，后续版本的蓝牙标准引入了更高速的传输模式，如高速模式（Enhanced Data Rate，简称EDR）和低能耗模式（Low Energy，简称LE），以满足数据传输速率和低功耗的需求。



蓝牙EDR（Enhanced Data Rate）是指蓝牙传输技术中的一种高速传输模式。它是在蓝牙2.0版本中引入的，传输速率可达到3Mbps。相比于蓝牙BR（Basic Rate）模式，EDR模式采用更高效的调制方式和更短的包时隙，可以实现更高的传输速率和更好的传输质量。

EDR模式的引入使得蓝牙技术不仅可以支持低速率的语音通话和简单数据传输，还能够支持更高速率的数据传输，如音频流和视频流的传输等。此外，EDR模式还具有更好的功耗控制和更广泛的应用范围，可以应用于个人电脑、智能手机、音频设备、汽车电子等领域。

USB通话使用什么协议？

USB通话使用UAC协议

蓝讯，BK使用那个版本的蓝牙

BK：RWBT_SW_VERSION_MAJOR，使用蓝牙5.1版本

蓝讯使用蓝牙5.1版本

什么是DRC?

DRC(Dynamic Range Control),通常用来调整音频信号的动态范围，保证信号不至于过大或过小。原理是根据输入信号的大小，对其施加一个增益，大信号施加负增益，小信号施加正增益。使用DRC是为了平衡音量，避免过于嘈杂过于安静，可以防止扬声器损坏保护人们的耳朵，改善音质。

蓝讯，BK音量增益计算

蓝讯：

![image-20230414012709398](E:\databases\note\image-20230414012709398.png)

3.USB HID功能

以STM32为例：

准备抓包工具Bus Hound，USBTreeView。

下载运行STM32 HID例程之后，根据usbd_desc.h中的VID, PID找到USB设备。更改端点0的最大包长CUSTOM_HID_EPIN_SIZE为0x40，最好在usbd_conf.h重新定义。在usbd_custom_hid_if.c里更改报告描述符。CUSTOM_HID_ReportDesc_FS。

USB获取描述符，第一次是为了获取端点0的最大包长度，为8字节。第二次获取设备描述符全部功能。

UCOSIII移植最少需要4K RAM才行。

蓝牙配对过程：

1.host端会通过hci指令发送create connection的命令给到controller，这个命令里面包含指定蓝牙设备地址，控制层会通过这个地址执行paging操作。

2.第二部发送获取对方蓝牙设备特性信息，了解蓝牙设备属性等，例如是否支持OOB配对，也就是通过别的途径交换配对信息，例如NFC蓝牙设备等。

获取完特性后，host端就可以发送LMP_HOST_CONNECTION_REQ PDU，这个是必选步骤，对端蓝牙收到这个请求后，会有三种响应方式：

1. 拒绝连接；
2. 接受连接；
3. 接受连接但是请求自己为master；

4.设备回应，可能有3种情况

1.连接被拒绝。

2.连接同意

3.连接同意，但是请求更换角色

5.AHF自适应跳频

在蓝牙设备接受连接请求后，会交换特性，之后AFH会被使用，host端根据干扰情况自动跳到下一个频段，会发送LMP_SET_AFH 和 LMP_CHANNEL_CLASSIFICATION_REQ PDU

6.进行身份认证请求，整个过程就是获取Link Key的过程。Link Key在后续数据传输时使用。

当两个设备事第一次进行连接时，由于双方都没有保存link key,所以需要进行授权验证，控制器向host发送link key请求，如果host回复的是negative,接下来就进入配对过程。如果host返回positive，那双方就不需要进入配对过程。



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