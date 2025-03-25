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

### Multiplication

If $A=\begin{bmatrix}a_{ij}\end{bmatrix}\in\boldsymbol{M}_{m\times r}$, and $B=\begin{bmatrix}b_{ij}\end{bmatrix}\in\boldsymbol{M}_{r\times n}$,, then the $(i, j)$ entry of the product $AB=\begin{bmatrix}c_{ij}\end{bmatrix}\in M_{m\times n}$ is

如果$A=\begin{bmatrix}a_{ij}\end{bmatrix}\in\boldsymbol{M}_{m\times r}$,而$B=\begin{bmatrix}b_{ij}\end{bmatrix}\in\boldsymbol{M}_{r\times n}$,那么乘积$AB=\begin{bmatrix}c_{ij}\end{bmatrix}\in M_{m\times n}$位于$(i,j)$处的元素是
$$
c_{ij}=\sum_{k=1}^ra_{ik}b_{kj},
$$
then

又$$AB=
\begin{bmatrix}
A\boldsymbol{b}_1 & A\boldsymbol{b}_2 & \cdots A\boldsymbol{b}_n
\end{bmatrix}.$$
$A,B\in M_n$ commute if $AB=BA$.

如果$AB=BA$，$A,B\in M_n$,可交换(commute).
$$
\begin{aligned}
 & (a)A(BC)=(AB)C. \\
 & (\mathrm{b})A(B+C)=AB+AC. \\
 & (c)(A+B)C=AC+BC. \\
 & (d)(cA)B=c(AB)=A(cB).
\end{aligned}
$$
### Identity Matrices

The matrix

矩阵
$$I_n=
\begin{bmatrix}
1 & 0 & 0 & \cdots & 0 \\
0 & 1 & 0 & \cdots & 0 \\
0 & 0 & 1 & \cdots & 0 \\
\vdots & \vdots & \vdots & & \vdots \\
0 & 0 & 0 & \cdots & 1
\end{bmatrix}\in\boldsymbol{M}_n$$
is the n × n identity matrix. That is, $I_n=\left[\delta_{ij}\right]$, in which the Kronecker delta is

是$n\times n$单位阵(identity matrix).也就是说$I_n=\left[\delta_{ij}\right]$，上下文已知记为$I$，其中Kronecker符号(Kroneckerdelta)是
$$\delta_{ij}=
\begin{cases}
1 & \text{if }i=j \\
0 & \text{if }i\neq j & & 
\end{cases}$$

### Triangular Matrices

Let $A=\begin{bmatrix}a_{ij}\end{bmatrix}\in\boldsymbol{M}_{n}$.

设 $A=\begin{bmatrix}a_{ij}\end{bmatrix}\in\boldsymbol{M}_{n}$,

A is upper triangular if $a_{ij}=0$ whenever $i>j$;

A是上三角的(upper triangular),如果对$i>j$有$a_{ij}=0$;

lower triangular if $a_{ij}=0$ whenever $i<j$; 

A是下三角的(lower triangular),如果对$i<j$有$a_{ij}=0$;

strictly upper triangular if $a_{ij}=0$0 whenever $i≥j$;

A为严格上三角的(strictly upper triangular),如果对$i≥j$有$a_{ij}=0$;

strictly lower triangular if $a_{ij}=0$ whenever $i\leq j$

A为严格下三角的(strictly lower triangular),如果对$i\leq j$有$a_{ij}=0$.

A is triangular if it is either upper triangular or lower triangular.

A是三角的(triangular),如果它既是上三角的,又是下三角的.