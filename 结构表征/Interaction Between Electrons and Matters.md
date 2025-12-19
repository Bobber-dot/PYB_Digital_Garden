---
Date: 2025-12-19
tags:
  - 材料学
aliases:
---
# Interaction between electrons and matters 电子和样品相互作用

![[Pasted image 20251021163554.png]]

- 上边6种为 Thick 样品会发生的相互作用
	- Absorb electrons 在样品中电子动能逐渐下降，停止。
	- Visible light 反射出可见光
	- Auger electrons 见[[X-ray#^a945d2|Auger effect]]
	- Characteristic X-rays 见[[X-ray#^8d4011|Characteristic X-ray]]
	- Secondary electrons 见[[X-ray#^8d4011|Characteristic X-ray]]
	- Backscattered electrons 反向散射电子入射电子束与固体样品相互作用后反射回来的高能电子，可分为弹性和非弹性散射两类。
- 下边4种为 Thin 样品会发生的相互作用
	- Direct beam 直接透过
	- Elastically scattered electrons 弹性散射 不损失能量 方向改变
	- Inelastically scattered electrons 
	- Bremsstrahlung X-rays [轫致辐射](https://baike.baidu.com/item/%E8%BD%AB%E8%87%B4%E8%BE%90%E5%B0%84/3483973)入射电子束在原子核电磁场作用下，带电粒子的速度是连续变化的。X射线管中高电压加速电子所产生轫致辐射具有[连续谱](https://baike.baidu.com/item/%E8%BF%9E%E7%BB%AD%E8%B0%B1/0?fromModule=lemma_inlink)的性质。

## Scattering 散射
Scattering is fundamental to all electron microscopy 散射是所有电子透镜的基础
- 按粒子性质：**elastic** and **inelastic** scattering
- 按波动性质：**coherent** and **incoherent** scattering

### Elastic Scattering
> **Def** Scattering that results in no loss of energy

![[Pasted image 20251021165934.png]]

- Major source of contrast in TEM images
- Elastic scattering is usually coherent and occurs at relatively low angles (1~10 degree).
- Two principle forms: scattered by...
	- Single isolated atoms.
	- Many atoms together within the specimen.
	- --- 
	- electron-electron interactions result in relatively low angle.
	- electron-nucleus interactions cause higher-angle scattering.

#### The atomic scattering factor

$$
f(\theta)=\frac{(1+\frac{E_0}{m_0c^2})}{8 \pi^2 a_0}{(\frac{\lambda}{sin \frac{\theta}{2}}})^2(Z-f_x)
$$
- f($\theta$) amplitude of an electron wave
- |f($\theta$)|^2 is proportional to the scattered intensity 
- $\theta \ \lambda \ Z$

![[Pasted image 20251021171000.png]]


### Inelastic Scattering
![[Pasted image 20251021171132.png]]
Inelastic scattering is almost always incoherent and is very low angle (<1o) scattering
- X-ray emission
	- Characteristic X-rays
	- Bremsstrahlung X-rays
- Secondary electron emission
	- Secondary electrons
	- Auger electrons
- Electron-hole pairs and Cathodoluminescence
- Plasmons and Phonons
- Energy-loss electrons

### Characteristic X-ray
![[Pasted image 20251021171344.png]]

### Secondary Electrons
> Electrons generated as ionization products, with energies < 50eV

SEs are ejected from the conduction or valence bands of the atoms in the specimen.

*Surface morphology analysis-SEM/STEM*

### Auger Electrons
> Electrons generated as ionization products, with energies ~ 5eV

Auger electrons has a **characteristic energy** that is depend on the electronic structure of the ionized atom

*Surface morphology and composition analysis-SEM/STEM*

### Backscattered Electrons(BSE) 
> The reflection electrons of solid matter with high energy, include elastic BSE and inelastic BSE

Relate to atomic number and not sensitive to morphology

Generate diffraction, revealing crystal structure and **orientation information**

*Atomic contrast and diffraction-SEM/EBSD*

### Cathodoluminescence (CL) 阴极发光
![[Pasted image 20251021172141.png]]

- Emitted photon $E_G=hv$
- Recombine of electrons and holes
- Semiconductors and impurity effects

*Luminescence, impurity and defects-SEM-CL*

### Direct Beam
>The transmission electrons

Relates to: thickness, atomic number, loss of electrons 

*Morphology, structure, composition and orbital state-TEM-SAED-EELS*

### Plasmons and Phonons

>**Plasmons** are collective oscillations of free electrons that occur when a beam interacts with the **free electron gas** 等离子体振荡的量子化

>**Phonons** are collective oscillations of atoms in a solid that arise when the atomic lattice is struck by a beam electron 声子

### *Beam Damage*
> **Radiation damage**, which affects the structure and/or the chemistry of the specimen

切个小薄片不影响全部的材料
或者是：
Decrease damage: 
- High voltage  传递能量效率变低
- Avoid high intensity and small radius of beam 避免高强度的照射
- Thin specimen 薄片

### *Compton Effect*
散射光中除了有原波长λ0的x光外，还产生了波长λ≧λ0 的x光，其波长的增量随散射角的不同而变化。这种现象称为康普顿效应（Compton Effect）。
