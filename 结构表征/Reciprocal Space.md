---
Date: 2025-10-11
tags:
  - 材料学
aliases:
---
# Definition
1. Assuming the (HKL)*(Miller)* lattice plane in real space is represented as a new lattice spot `[[HKL]]`，（平面映射到点）

2. 倒易空间中，对于任意的原点O ，OG（已经映射了的G）是沿着(HKL)平面的法线的，其长度$|\vec{g^*_{HKL}}|$是两平面间距的倒数即$\frac{1}{d_{HKL}}$。（定义完毕）(同时也是性质，和上边的定义是可以互相推的)

这些倒易点（Reciprocal spots） 组成了 倒易晶格 （Reciprocal lattice）

## Reciprocal Basis Vector
To efine a reciprocal lattice, three non-planar basis vectors are required.

$$
\vec{c^*}=\vec{r^*_{(001)}} \quad \vec{b^*}=\vec{r^*_{(010)}} \quad \vec{a^*}=\vec{r^*_{(100)}}
$$

矢量定义：（用叉乘良好定义了三个矢量的方向，就不管原本晶胞的角度，长度影响了）
$$
\vec{c^*} = \frac{\vec{a} \times \vec{b}}{V}, \quad
\vec{a^*} = \frac{\vec{b} \times \vec{c}}{V}, \quad
\vec{b^*} = \frac{\vec{c} \times \vec{a}}{V}, \quad
$$
$$
\vec{r^*_{(HKL)}}=H\vec{a^*}+K\vec{b^*}+L\vec{c^*}
$$
![[74ae68d3-db40-4345-a100-6300d5f184eb.png]]

![[42709a11-bb2b-48fb-9cbb-7b0ad80c6e4f.png]]

## WTF is Laue zones?
**电子束/光束沿某一晶带轴入射时，倒易点阵中那些“一层层”垂直于该轴的平面**——每层平面称为一个 **Laue zone**，它们按离原点（000）的远近编号为 0、±1、±2…。

## Lattice parameters of reciprocal space
![[2f0d0155-67fa-4836-8d94-f5432fdcf3e7.png]]

## Application
- Calculation of interplanar spacing (Orthogonal)
![[Pasted image 20251011190756.png]]
- Calculation of the interplanar included angle (Orthogonal)
![[Pasted image 20251011190806.png]]

# Weiss Zone Law（魏氏晶带定律）
Weiss Zone Law（魏氏晶带定律）是晶体学中一条最基础、却**适用于所有晶系**的几何判据：

>若晶向 [u v w] 位于晶面 (h k l) 内（或平行于该面），则
>$$uh+vk+wl=0 $$

Perpendicular to each other.

![[Pasted image 20251014160508.png]]

在倒易空间中，晶面变换成了点，晶带变换成了面，而点和面的关系不变。

## Application 
如果 两个平面都在同一个晶向的Zone内，那么，这个晶向就是两个平面的交线
![[Pasted image 20251011191451.png]]

![[Pasted image 20251014160637.png]]

上图表示 Lane n阶零空间和晶带的Miller系数点乘得到N

# The Ewald Sphere of Reflection
![[8beb0b221e57508f0ad9418c0bf0abd8.jpg]]

首先我们知道了布拉格定律，随后用布拉格定律推出了一个巧合，那就是恰好衍射点一定符合倒易空间定义，于是乎，ewald球体所经过的衍射班就一定是晶格倒易空间中的点。



