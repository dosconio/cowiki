---
{"dg-publish":true,"permalink":"/handy-book/denji/","noteIcon":""}
---

%parent:[[COTLAB\|COTLAB]]; #Datura/COTLAB/Handy 

### 电磁学数学基础

右旋叉乘恒等式:

- $\vec a \times (\vec b \times \vec c) = \vec c \cdot \vec a \cdot \vec b - \vec a \cdot \vec b \cdot \vec c$ (难点)

算子算式:

- $\nabla f = d_i \cdot \vec e_i \cdot f$

- $\nabla \cdot \vec f = d_i \cdot f_i$

- $\nabla \times \vec f = ε \cdot d_i \cdot f_j \cdot \vec e_k$

- $∆f = (d_i)^2 f$

分裂公式:

- $\partial(\vec a \cdot \vec b) = \vec a \cdot \partial \vec b + \partial \vec a \cdot \vec b$

- $\partial(\vec a \times \vec b) = \vec a \times \partial \vec b + \partial \vec a \times \vec b$

- $\nabla(f \cdot g) = f \cdot \nabla g + \nabla f \cdot g$

- $\nabla(\vec a \cdot \vec b) = (\vec a \cdot \nabla)\cdot \vec b + (\vec b \cdot \nabla)\cdot \vec a + \vec a \times(\nabla\times\vec b) + \vec b \times(\nabla\times\vec a)$

函数分解通式:

- $\nabla*\vec F (\varphi(t)) = \nabla \varphi(t)*\frac{\partial \vec F}{\partial \varphi}$ (难点)

双重算子公式:

- $\nabla \times(\nabla \cdot \vec f) = 0$

- $\nabla \times(\nabla f) = 0$

- $\nabla \cdot(\nabla \times \vec f) = 0$

- $(\Delta\times)^2\vec f = \nabla \times(\nabla \times \vec f) = \nabla(\nabla\cdot\vec f)-\Delta\vec f$

其他公式:

- $\nabla\cdot(f \cdot\vec F) = f \cdot(\nabla\cdot\vec F) + \vec F\cdot\nabla f$

- $\nabla\times(f \cdot\vec F) = \nabla f \times\vec{F} + f\cdot(\nabla\times\vec{F})$
	- $\int_S{f\cdot(\nabla\times\vec{F})\cdot d\vec a}=\int_S{\vec{F}\times(\nabla f)\cdot d\vec a}+\oint_l{(f \cdot\vec F)\cdot d\vec l}$

- $\nabla\cdot(\vec a \times\vec b) = \vec b \cdot(\nabla\times\vec a) - \vec a\cdot(\nabla\times\vec b)$
	- $\int_V{\vec b \cdot(\nabla\times\vec a)\cdot d\tau}=\int_V{\vec a\cdot(\nabla\times\vec b)\cdot d\tau}+\oint_S{(\vec a \times\vec b)\cdot d\vec a}$

- $\nabla\times(\vec a \times\vec b) = \vec a \cdot(\nabla\cdot\vec b) - \vec b\cdot(\nabla\cdot\vec a)+ (\vec b \cdot\nabla)\cdot\vec a - (\vec a \cdot\nabla)\cdot\vec b$

狄拉克公式:

- $\int^\forall δ^{(n)}(t-t_0) \cdot f(t) \cdot dt = (-1)^n \cdot f^{(n)}(t_0)$

- $δ(z=x^2-1)=\frac 1 2 \cdot δ(x+1) + \frac 1 2\cdot δ(x-1)$

- $\delta(z = k(x-x_0))=\frac{1}{|k|}\delta(x-x_0)$

冲击偶:

- $x \cdot δ'(x) = -δ(x)$

- $f(t) \cdot δ'(t-t_0) = f(t_0)δ'(t) - f'(t_0)δ(t)$

- 尺度变换 $δ'(a t)=\frac 1 {a\cdot\left|a\right|} \cdot δ'(t)$

抽样函数:

- $Sa(x)=\frac {sin(x)} x$

### .Reference
未示出的推导过程见旧版H.N.。符号定义亦基本沿用于此。
错误、检举等请联系服主唷~
- [[DATURA/Differential\|Differential]]
- [[DATURA/Operator/Dirac\|Dirac]]



