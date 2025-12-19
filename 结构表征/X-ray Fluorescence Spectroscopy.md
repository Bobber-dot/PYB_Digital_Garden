---
Date: 2025-11-04
tags:
  - 材料学
aliases:
---
![[Pasted image 20251104161857.png]]
![[Pasted image 20251104162119.png]]
![[Pasted image 20251104162806.png]]

# X光和电子之间的相互作用
- 光电子
	- 跃迁 Excitation
- 俄歇电子
- 荧光x射线（或特征X射线）
	- 弛豫 Relaxation

# 原理
## 什么是二次X光射线？二次电子？
二次X光射线不出于实验仪器射出的X射线（Primary X-ray），而是出于材料本身，即电子跃迁产生的X光。
同样，二次电子也不出于实验仪器射出的电子，而是出于材料本身，光电效应出现的电子，或者俄歇电子。

## X光射线分析
每种元素的能级能量不同，荧光光谱不同。
用Kα和Kβ，能量高，强度高，概率也大，经常被使用。
the transition from L to K-edges is Kα, and from M to K-edgesis Kβ
![[Pasted image 20251104170451.png]]
- Each element has its characteristic X ray (c-XR) at a specific wavelength (or energy). By measuring the wavelength (or energy) of the c-XR in the sample, we can determine which element is present in the sample, that is, qualitative analysis of XRF spectrum. 定性分析，得到元素
- The intensity of the X-ray is proportional to the number of atoms (that is, the content) of the element in the sample.定量分析，得到元素丰度
![[Pasted image 20251104170926.png]]
![[Pasted image 20251104170934.png]]

## WDS(Wave Dispersive System)
![[Pasted image 20251104171451.png]]

It consistsof X-ray tube, filter, samplecup, spectroscopic (analyzing) crystal,detector,multichannel counting circuit analyzer and computer.

$$
I = \frac{K}{R^2}
$$
X 射线和距离有关，因此样本的位置对X射线的再发射能力有很大关系。

### 分光晶体 Analyzing crystals
利用布拉格定律反过来得到单一波长的X光。
![[Pasted image 20251104171829.png]]
- WDS 广泛使用的晶体有8种
- 平面间距d多样，可以用多种晶体取向
- 5种晶体被选择使用。
- ![[Pasted image 20251104172434.png]]
### 准直器 Collimators
- 准直器就是让X光平行的仪器，但是如果不用准直器，就用Rowland circle，光线会自动聚焦

- 如果用准直器
![[Pasted image 20251104172710.png]]

### 检测器 Detectors
![[Pasted image 20251104172746.png]]
将光量子信号转换成电脉冲

![[Pasted image 20251104172753.png]]
- 记录器：放大器 Amplifier，脉冲高度分析仪，显示器。三个探测器提供脉冲信号
- 脉冲高度分析仪：二次衍射线、杂质线、散射线的分离

### 利与弊
- WDS是无损检测方法，检测点小到只有几微米，检测精度达到10s个ppm( **"10s" = "tens of"** = **"几十"** ) ，最低只能检测到硼元素。正因为只能检测到硼，因此对地质学的帮助不大。 ^7d0cb2
- 用于多种材料
- 高空间精度不仅允许对小物相的定量分析，而且用于检测小范围的**化学环带（Chemical Zoning）**
	- 化学环带是指**固溶体矿物**从核部到边缘呈现化学成分系统性变化的结构特征，这种变化在显微镜下表现为颜色或消光角的差异，也就是晶体生长过程中，会随着温度压力变化而改变形态，而生长好的晶体会记忆这个形态，形成环状结构。尤其用于矿物
- WDS可以画出元素分布图
- WDS比EDS的检测元素精度高，对痕量元素的敏感性高
- 尽管元素峰精度高，但是依然会存在元素峰重叠，提升检测难度
- WDS比EDS慢，但是WDS的检测限高（ppm）
- WDS不能分辨元素的价态，必须得用其他方法（穆斯堡尔光谱）
- 同位素检测不了，必须得用元素质量检测仪。

### SEM-WDS和WDS
![[Pasted image 20251109105358.png]]

## EDS(Energy Dispersive System)
![[Pasted image 20251104173020.png]]

![[Pasted image 20251104173311.png]]
- 二次X射线会被转化成电压信号，然后被送往脉冲处理器（放大），度量能量信号，然后送往分析器
- 分析器把模拟信号转变成数字信号，和送来的脉冲能量成正比
- 电子信号再被多通道分析器、出现频率分类，最终将数据送往显示器、分析。

### EDS的检测限度
- 只从钠元素到铀元素
- 浓度范围从100%到ppm-level，对轻元素不准确，对不同的元素、不同的样品基质有不同的检测限。而一般来讲，重元素检测限好
- 最常用的检测仪器是冷却到液氮低温的Si（Li）detector，然而，较新的系统通常配备有带有佩尔帖冷却系统的硅漂移探测器（SDD）。

![[Pasted image 20251109111413.png]]

## WDS和EDS比较
![[Pasted image 20251109111454.png]]
![[Pasted image 20251109111504.png]]
![[Pasted image 20251109112113.png]]
