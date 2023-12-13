[TOC]

### 4.3 空间曲面和空间曲线

#### 空间曲面与空间曲线的方程

空间曲面$S$的方程: $F(x,y,z) = 0$

空间曲线$C$的一般式方程: $\begin{equation}
\left\{\begin{aligned}
  &\text{$F(x,y,z) = 0$,} \\
  &\text{$G(x,y,z) = 0$.}
\end{aligned}\right.\end{equation}$

#### 柱面

- 直线$L$(**母线**)绕定曲线$C$(**准线**)进行平移后所形成的轨迹即为**柱面**

##### 圆柱面/椭圆柱面/抛物柱面/双曲柱面

- 没有谁母线平行谁
  $$
  \frac{x^2}{a^2} + \frac{y^2}{a^2} = 1
  \space / \space
  \frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
  \space / \space \\
  y = ax^2
  \space / \space
  \frac{x^2}{a^2} - \frac{y^2}{b^2} = 1
  $$









#### 旋转曲面

- 某个平面上的一条连续曲线$C$绕该平面上的一条定直线$L$选择一周生成的曲面称为**旋转曲面**. 这条定直线称为**旋转轴**, 曲线$C$称为旋转曲面的**生成曲线**.

  - 注意: 是**同一平面內**的曲线和旋转轴.

- $xOy$平面上的曲线$C:\begin{equation}
  \left\{\begin{aligned}
    &\text{$f(x,y) = 0$,} \\
    &\text{$z = 0$.}
  \end{aligned}\right.\end{equation}$ 绕$x$轴旋转一周生成的旋转曲面方程为
  $$
  f(x,\pm\sqrt{y^2+z^2}) = 0.
  $$
  - 即绕哪个轴哪个不变.

##### 球面

- 球面方程为:
  $$
  (x-x_0)^2+(y-y_0)^2+(z-z_0)^2=R^2
  $$
  

  - 一般形式为

  $$
  x^2+y^2+z^2+2b_1x+2b_2y+2b_3z+c=0
  $$

  

##### 旋转椭球面

- 椭圆 $\begin{equation}
  \left\{\begin{aligned}
    &\text{$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$,} \\
    &\text{$z = 0$}
  \end{aligned}\right.\end{equation}$ 
  - 绕$y$轴旋转一周的方程为
    $$
    \frac{x^2+z^2}{a^2} + \frac{y^2}{b^2} = 1
    $$
  - 绕$x$轴旋转一周的方程为
    $$
    \frac{x^2}{a^2} + \frac{y^2+z^2}{b^2} = 1
    $$
- ( 若$x^2,y^2,z^2$系数互不相等则称曲面为椭球面, 但不能由曲线旋转得来, 也不是旋转曲面. )

##### 圆锥面

- 直线$L$绕与之相交的直线$L'$旋转一周所得曲面

  - 交点: 顶点 

  -  夹角$\alpha$: 半顶角

  -  方程: 
  $$
    \frac{x^2}{a^2} + \frac{y^2}{a^2} = z^2
  $$
  
  - 椭圆锥面( 非旋转曲面 ):
    $$
    \frac{x^2}{a^2} + \frac{y^2}{b^2} = z^2
    $$

##### 旋转抛物面

- 将$xOy$平面上的抛物线: $\begin{equation}
  \left\{\begin{aligned}
    &\text{$y^2 = 2x$,} \\
    &\text{$z = 0$}
  \end{aligned}\right.\end{equation}$ 绕$x$轴旋转一周的旋转抛物面, 其方程为:
  $$
  y^2+z^2 = 2x
  $$

- 椭圆抛物面( 非旋转曲面 ): 
  $$
  \frac{y^2}{a^2} + \frac{z^2}{b^2} = x
  $$

##### 旋转单/双叶曲面

- 将$yOz$平面上的双曲线: $\begin{equation}
  \left\{\begin{aligned}
    &\text{$\frac{y^2}{b^2} - \frac{z^2}{c^2} = 1$,} \\
    &\text{$x = 0$}
  \end{aligned}\right.\end{equation}$ 分别绕$z$轴和$y$轴旋转一周所得的旋转曲面分别为**旋转单叶双曲面** (两正一负), **旋转双叶双曲面** (两负一正), 其方程分别为: 
  $$
  \frac{x^2+y^2}{b^2} - \frac{z^2}{c^2} = 1
   \space和\space
   \frac{y^2}{b^2} - \frac{x^2+z^2}{c^2} = 1
  $$
  

#### 二次曲面

1. 截痕法
2. 伸缩变换
   谁乘$\frac{a}{b}$, 谁就伸缩$\frac{b}{a}$倍.

##### 双曲抛物面 (马鞍面) 

$$
\frac{x^2}{a^2} - \frac{y^2}{b^2} = z
$$

#### 空间曲线方程

- 空间直线的方程: 一般式, 对称式, 参数式

- 空间曲线的一般式方程: (一般式方程不唯一)
  $$
  \begin{equation}
  \left
  \{\begin{aligned}
    &\text{$F(x,y,z) = 0$} \\
    &\text{$G(x,y,z) = 0$}
  \end{aligned}
  \right.
  \end{equation}
  $$
  
- 空间曲线的参数方程: 
  $$
  \begin{equation}
  \left
  \{\begin{aligned}
    &\text{$x = x(t)$} \\
    &\text{$y = y(t)$}  \\ 
    &\text{$z = z(t)$}
  \end{aligned}
  \right.
  \end{equation}
  \space t \in [\alpha,\beta]
  $$

  - 螺旋线的参数方程
    $$
    \begin{equation}
    \left
    \{\begin{aligned}
      &\text{$x = acos\theta$} \\
      &\text{$y = bsin\theta$}  \\ 
      &\text{$z = b\theta \space (b = \frac{v}{\omega})$}
    \end{aligned}
    \right.
    \end{equation}
    \space \theta \in R
    $$

##### 空间曲线在坐标面上的投影

- 对空间曲线 $C:\begin{equation}
  \left
  \{\begin{aligned}
    &\text{$F(x,y,z) = 0$} \\
    &\text{$G(x,y,z) = 0$}
  \end{aligned}
  \right.
  \end{equation}$ 的方程式消去变量$z$后得到的方程$h(x,y)=0$称为曲线$C$到$xOy$平面的**投影柱面**, 而投影柱面与$xOy$平面的交线 $\begin{equation}
  \left\{\begin{aligned}
    &\text{$h(x,y)=0$,} \\
    &\text{$z = 0$}
  \end{aligned}\right.\end{equation}$ 就是空间曲线$C$在$xOy$平面上的**投影曲线** (或称**投影**), 同理可得在其他平面上投影.

