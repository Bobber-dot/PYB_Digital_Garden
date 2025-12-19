---
Date: 2025-09-19
tags:
  - 材料学
aliases:
---
# PANanalytical X'oert MPD Pro X射线衍射仪
![[Pasted image 20250919143136.png]]
## Specifications 主要技术指标
##### 光源Light :
- X射线发生器:最大输出功率3 kW
- 陶瓷X光管:Cu靶，最大功率2.2 kW
- 光管焦斑:0.4x12 mm

##### 探测器Detector:
- 充Xe正比探测器:最大计数率1,000,000 cps
- 半导体阵列探测器: 最大计数率>4,000,000 cps

##### 角度重现性:±0.0001

##### 样品台Stage holders :
- 常规样品台(Standard sample holder)
- 粉末样品台(Powder sample holder)
- 原位加热样品台(In-situ heating sample holder)

## Principle 工作原理
![[Pasted image 20250919144007.png]]

### [[X-ray]] tube

X-ray tube: X射线发生器
![[Pasted image 20250919144351.png]]

X射线发生器由X射线管、高压发生器、管压和管流稳定电路以及保护电路等组成。这里着重介绍X射线管。X射线管的实质是个真空二极管，其阴极是钨丝，阳极为金属片。

在阴极两端加上电流之后，钨丝发热，产生热辐射电子。这些电子在高压电场作用下被加速，轰击阳极(又称靶)，产生X射线(此过程产生大量热量，为了保护靶材，必须确保循环水系统工作正常)。

常见的阳极靶材有：Cr, Fe, Co, Ni, Cu, Mo, Ag, W,最常用的是Cu靶。




Beta Filter: 贝塔滤镜

![[Pasted image 20250919143958.png]]

# Determination of crystal structure

![[Pasted image 20251014160938.png]]

1. Crystal system
2. Bravais lattice type
3. Indices of diffraction planes
4. Lattice parameter

## 1. First step _Calibration of X-ray spectrum_
从图片是检验结果可以得到2$\theta$ 将实验结果整理成sin2θ后，
List: 
$$
sin^2\theta_1 : sin^2\theta_2 : sin^2\theta_3 :\cdots: sin^2\theta_n
$$
![[Pasted image 20251014161720.png]]

对于不同的晶胞，一个一个去尝试，其中最简单的

Cubic -> Tetragonal -> Hexagonal -> Rombohedral -> Orthorhombic -> ..

## 2. Second step _Lattice system_ 
### Cubic system
#### Simple lattce
![[Pasted image 20251014162906.png]]

推导结构因子 F(hkl)=Σf_j exp[2πi(hx_j+ky_j+lz_j)]，指出“峰是否存在由 F(hkl) 是否为零决定，与单张几何晶面是否有原子无关”。

这就是为什么即使晶面上没有原子，也可以有衍射峰值的原因。
#### Body-centered lattice
![[Pasted image 20251014162925.png]]

#### Face-centered lattice
![[Pasted image 20251014163005.png]]

#### Get lattice parameters
#### Table
![[Pasted image 20251014161506.png]]

#### 2.5. Extra Step _Multiplicity Factor_
The difference between **body-centered** and **simple lattice cubic** is whether there is **7** in the sin(θ)^2 series. (7 appears in the body-centered cubic, but not in the simple lattice) So there should be at least eight diffraction peaks when calibrating the spectrum of these two kinds of structures.

**When the number of diffraction peaks are less than eight**, we need to consider the influence of multiplicity factor. In X-ray spectrum, the first and second peaks of simple lattice are (100) and (110), whereas those of body-centered cubic is (110) and (200). Multiplicity factor of (100) and (200) is **P=6**，that of (110) is **P=12**.

**The intensity of second diffraction peak is higher than that of the first peak in simple cubic lattice**, but in body-centered cubic, its opposite.

### Tetragonal systems
![[Pasted image 20251014170938.png]]
![[Pasted image 20251014170950.png]]

