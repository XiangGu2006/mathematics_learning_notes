<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
# 1.可测性的概念
## 定义可测映射
### 1.1a **连续的定义**
$X$,$Y$均为**拓扑空间**
原文：$f$ is continuous: $f^{-1}(V)$ is a ==open== set in $X$  for every open set $V$ in $Y$.
理解：拓扑空间里随便取（开集）投回去，在拓扑空间里可以对应上（开集），则是连续映射。

### 1.1b **可测的定义**
 $X$: **可测空间**  $Y$: **拓扑空间**
 原文：$f$ is measurable: $f^{-1}(V)$ is a ==measurable== set in $X$  for every open set $V$ in $Y$.
理解：拓扑空间里随便取（开集）投回去，在可测空间里可以对应上（可测集），则是可测映射.
### 1.2 **推论**
$X$,$Y$均为**拓扑空间**，映射$f$（$f:X \to Y$ ）连续等价于$f$在$X$上每一点都连续.
### 1.3 **复合函数的定理**
$Y$,$Z$均为拓扑空间，$g: Y \to Z$连续
(a) $X$拓扑空间，$f: X \to Y$连续，则连续外 ，套个连续还是连续.
(b) $X$可测空间，$f: X \to Y$可测，则可测外，套个连续还是可测.
### 1.4 **复合函数定理的小应用**
对于$x\in X$，$u$和$v$是可测空间$X$上的实==可测函数==，于是可以产生平面$(u(x),v(x))$，$\Phi$是个==连续映射==，把平面映射到拓扑空间$Y$， 即$$h(x)=\Phi(u(x),v(x))$$那么$h: X\to Y$是个==可测映射==.

***可测外，套个连续还是可测！***
### 1.5 **1.3和1.4的应用**





<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYyODc2Nzc0XX0=
-->
