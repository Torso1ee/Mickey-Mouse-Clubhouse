## 0.1 Functions and Sets

Let $\mathscr{X}$ and $\mathscr{Y}$ be sets. The notation $f: \mathscr{X} \rightarrow \mathscr{Y}$ indicates that $f$ is a function whose domain is $\mathscr{X}$ and codomain is $\mathscr{Y}$.

设$\mathscr{X}$与$\mathscr{Y}$是集合.记号$f: \mathscr{X} \rightarrow \mathscr{Y}$表明$f$是定义域(domain)为$\mathscr{X}$而上域(codomain)为$\mathscr{Y}$
的函数(function).

The range of $f: \mathscr{X} \rightarrow \mathscr{Y}$ is $\text { ran } f=\{f(x): x \in \mathscr{X}\}=\{y \in \mathscr{Y}: y=f(x) \text{ for some }x\in\mathscr{X}\}$, which is a subset of $\mathscr{Y}$.

$f: \mathscr{X} \rightarrow \mathscr{Y}$的值域(range)是$\text { ran } f=\{f(x): x \in \mathscr{X}\}=\{y \in \mathscr{Y}: y=f(x) \text { ，对某个 } x \in \mathscr{X}\}$，是$\mathscr{Y}$的一个子集.

A function $f: \mathscr{X} \rightarrow \mathscr{Y}$ is onto if $\text { ran } f =  \mathscr{Y}$, that is, if the range and codomain of f are equal. A function   $f: \mathscr{X} \rightarrow \mathscr{Y}$  is one to one if $f(x_1)=f(x_2)$ implies that $x_1=x_2$.

$\text { ran } f =  \mathscr{Y}$称$f$为映上的，$f(x_1)=f(x_2)$蕴含$x_1=x_2$称$f$为一对一的.

![[Pasted image 20250325210305.png]]
## 0.2 Scalars

We denote the real numbers by $\mathbb{R}$ and the complex numbers by $\mathbb{C}$.

我们用$\mathbb{R}$记实数,而用$\mathbb{C}$记复数,实数或者复数都称为纯量(scalar).

## 0.3 Matrices

An $m\times n$ matrix is a rectangular array of real or complex numbers.

一个$m\times n$矩阵(*matrix*)指的是由实数或者复数组成的一个矩形的阵列
$$
A=
\begin{bmatrix}
a_{ij}
\end{bmatrix}=
\begin{bmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{bmatrix}.
$$
The set of all  $m\times n$ matrices with complex entries is denoted by $M_{m\times n}(\mathbb{C})$ , or by $M_n(\mathbb{C})$  if $m = n$. The set of  $m\times n$ matrices with real entries is denoted by $M_{m\times n}(\mathbb{R})$, or by $M_n(\mathbb{R})$  if  $m = n$.

$M_{m\times n}(\mathbb{C})$ 元素为复数的所有$m\times n$矩阵集合，$M_n(\mathbb{C})$ 元素为复数的所有$n\times n$矩阵集合，记${M}_{m\times n}(\mathbb{R})$ ，$M_n(\mathbb{C})=M_n$，换成$\mathbb{R}$则代表实数矩阵.

### Rows and Columns

the matrix  as a $1\times n$ array of columns

矩阵的阵列形式 $A=\begin{bmatrix}a_1 & a_2 & \cdots & a_n\end{bmatrix}.$

### Addition and Scalar Multiplication

A zero matrix is an $m\times n$ matrix whose entries are all zero. Such a matrix is denoted by 0.

零矩阵(zero matrix)是元素全为零的$mn$矩阵.我们用0来表示零矩阵.

$$
\begin{aligned}
 & (a)A+B=B+A. \\
 & (\mathrm{b})A+(B+C)=(A+B)+C. \\
 & (c)A+0=A=0+A. \\
 & (\mathrm{d})c(A+B)=cA+cB.\\
  & (\mathrm{e})c(dA)=(cd)A=d(cA). \\
 & (\mathrm{f})(c+d)A=cA+dA.
\end{aligned}
$$