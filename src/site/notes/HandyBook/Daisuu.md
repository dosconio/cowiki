---
{"dg-publish":true,"permalink":"/handy-book/daisuu/","noteIcon":""}
---

%parent:[[COTLAB\|COTLAB]]; #Datura/COTLAB/Handy 

代数学公式

### 初等函数

#### 三角函数

- $\partial^2\ sin=\partial\ cos=-sin$

- 降幂公式 $sin^2(\theta)=\frac 1 2 \cdot (1-cos(2\cdot \theta))$

- 相变公式，符号看象限 $sin(\alpha-\frac\pi 2+\frac\pi 2)=cos(\alpha-\frac\pi 2)$

- 和积互转公式
	- $sin(A)cos(B)=\frac 1 2 \cdot (sin\delta+sin\sigma)$
	- $cos(A)cos(B)=\frac 1 2 \cdot (cos\delta+cos\sigma)$
	- $sin(A)sin(B)=\frac 1 2 \cdot (cos\delta-cos\sigma)$

#### 反三角函数

### 双曲函数

#### 双曲正弦

$sh(x)=\frac{e^x-e^{-x} }2$

- $sh(x+y)=sh(x)ch(y)+ch(x)sh(y)$

- $i \cdot sin(y)=sh(i \cdot y)$ 

#### 双曲余弦

$ch(x)=\frac{e^x+e^{-x} }2$

- $ch(x+y)=ch(x)ch(y)+sh(x)sh(y)$

- $cos(y)=ch(i \cdot y)$ 

- $\partial^2\ sh=\partial\ ch=sh$

- $ch^2 - sh^2 = 1$

- $sh(2 \cdot x)=2 \cdot sh \cdot ch$

- $ch(2 \cdot x)=ch^2+sh^2$

#### 双曲正切

- $th(x)=\frac {sh(x)} {ch(x)}$

- $\partial\ th(x) = \frac 1 { {ch}^2(x)}$

#### 双曲余切

- $coth(x)=\frac {ch(x)} {sh(x)}$

- $\partial\ coth(x) = \frac 1 { {sh}^2(2)}$

#### 反双曲函数

适用于复数：

- $arsh(x)=ln(x+\sqrt{x^2+1})$

- $arch(x)=ln(x+\sqrt{x^2-1})$

- $arth(x)=\frac 1 2 \cdot ln \frac{1+x}{1-x}$

### 复数公式

- $A + j \cdot B = \sqrt{A^2+B^2}\cdot\angle sym(arccos \frac A {\sqrt{A^2+B^2} })$



### .Reference

未示出的推导过程见旧版H.N.。符号定义亦基本沿用于此。
错误、检举等请联系服主唷~

- [[DATURA/Fucntion/Function\|Function]]
