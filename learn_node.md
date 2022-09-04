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

![image-20220903001752523](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903001752523.png)

点击64-bit Git for Windows Setup.下载

![image-20220903001919412](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903001919412.png)

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

![image-20220903005736148](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903005736148.png)

在learnGit根目录下新建文件readme.txt，然后输入命令 `<span style="color:red">git status</span>查看仓库文件状态。

![image-20220903010139596](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903010139596.png)

此时文件名显示为红色，untracked表示文件未被git跟踪，可以输入命令`<span style="color:red">git add readme.txt</span>使该文件被git跟踪。此时再次运行<span style="color:red">git status</span>查看文件状态，发现文件名已变成绿色，说明该文件已被git跟踪

![image-20220903011121989](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903011121989.png)

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

![image-20220903012239435](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903012239435.png)

执行命令

```console
git commit -m "本次提交描述"
```

完成一次提交，再次执行

```console
git status
```

发现工作区已变干净，没有任何修改记录。

![image-20220903012537365](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903012537365.png)

执行命令

```console
git log
```

可以查看提交记录

![image-20220903012630721](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220903012630721.png)

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

GitHub 有一个十分详细的针对数十种项目及语言的 .gitignore 文件列表， 你可以在 https://github.com/github/gitignore 找到它。

### 4.3.6git添加远程库

**1.创建SSH Key。（如果用户主目录已经有.ssh目录，这一步跳过）**

```console
ssh-keygen -t rsa -C "youremail@example.com"
```

运行改命令后一路回车，最终会在主目录下生成一个.ssh目录，该目录的id_rsa和id_rsa.pub就是SSH Key的秘钥对，id_rsa是私钥，不能泄露，id_rsa.pub是公钥。可以告诉别人。

**2.登陆GitHub，打开“settings”，点击SSH and GPG keys，**

**然后，点“New SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容：**

![image-20220904153558831](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904153558831.png)

点击Add SSH key

![image-20220904154030328](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904154030328.png)

添加完成

![image-20220904154138996](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904154138996.png)

**3.点击your repositories, 点击New创建一个新仓库**。

![image-20220904154742389](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904154742389.png)

填好仓库信息，点击Create repository创建一个仓库。

![image-20220904155032160](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904155032160.png)

**4.执行命令添加远程仓库：**

```console
git remote add origin git@github.com:tlight20210429/learnGit.git
```

添加远程库后执行命令查看远程库，显示远程库已添加

```console
git remote -v
```

![image-20220904155654352](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904155654352.png)

**5.添加远程库之后还要拉取远程库分支到本地，拉取远程库到本地有两种方式，分别是git fetch 和 git pull.**

执行命令：

```console
git fetch origin main
```

将远程库origin的main分支抓取到本地，第一次执行该命令会得到一个警告，可以不用管它直接yes就行。

![image-20220904160955702](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904160955702.png)

抓取到本地后执行命令：

```console
git branch -a
```

可以看到远程分支已经抓取到本地了

![image-20220904161128973](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904161128973.png)

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

![image-20220904194533231](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904194533231.png)

查看冲突文件里会发现<<<<<<<HEAD 和||||||||bug，其中<<<<<<<HEAD是本分支的内容，||||||||bug是bug分支的内容，需要手动解决分支才行。

![image-20220904195326457](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904195326457.png)

这里我们保留bug分支的内容，去掉main分支内容。然后重现提交就可以顺利完成合并了。

![image-20220904195509522](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904195509522.png)

![image-20220904195642995](C:\Users\唐嘉全\AppData\Roaming\Typora\typora-user-images\image-20220904195642995.png)

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

