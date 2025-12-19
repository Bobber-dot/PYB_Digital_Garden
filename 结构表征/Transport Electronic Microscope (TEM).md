---
Date: 2025-12-19
tags:
  - 材料学
aliases:
---
# Transport Electronic Microscope (TEM)
![[Pasted image 20251028160841.png]]

成像模式和衍射模式的区别
![[Pasted image 20251028160955.png]]
用Aperture取用特定方向的光线，可以径向轴向移动
- 成像模式：只允许特定衍射束通过，突出特定取向的晶粒、缺陷，比如只让（000）通过
- 衍射模式：该区域外的**透射电子**、**弹性散射电子**、**非弹性散射电子**，不筛选衍射束
两种模式只是选取了不同的信息平面，不同平面有助于得到不同信息（实空间和倒一空间），本质上是用中间镜调整了像的位置 

## 衍射模式
典型的电子衍射图像：
- 单晶 Single crystal 
	- Regular arrayed spots
- 多晶 Polycrystal （由于很多晶体取向，每个方向都有）
	- Concentric Rings
- 准晶体 Quasicrystal （没有平移对称性，有多重轴对称性）
	- Quasi regular arrayed spots
- 非晶体 Amorphous matter （无晶体结构）
	- Concentric boarder rings without speckles（很宽的晕环（长程有序，短程无序））

### 倒易空间
详细见[[Reciprocal Space]]

我们通过倒易空间推得，位于Ewald 球上的满足布拉格定律 ，同时是晶体的倒易空间。

同时根据晶带理论得到，位于同晶带的多个晶面，对应到倒易空间中，为一个面里的点阵。

同时由于电子能量很高，Ewald球半径很大，得到的透射点一般都是同一个面上的。

![[Pasted image 20251028163022.png]]

能量很高，不用过高。

### 计算

#### 参数矫正
![[Pasted image 20251028162514.png]]
矫正一下R和G之间的差异。

![[Pasted image 20251028163337.png]]

#### 参数确定
此时出现几种情况。我们想要知道得到的是正确的斑点之间（或者是环之间）的距离。

需要知道晶体结构与相机的参数。

#### 环（多晶）测量方法
环产生的原因
![[Pasted image 20251028163957.png]]
多晶体测量距离即可
![[Pasted image 20251028164209.png]]
如果知晓晶体参数
![[Pasted image 20251028164222.png]]
或者使用PDF卡片

#### 单晶测量方法
1. 矫正R
2. 确定是哪个Bravais lattice 和g的值
3. 确定晶体的晶带。(Zone axis)
4. 计算晶体参数

- #### 如果知道晶体结构
1. 矫正R
2. 确定d1 d2 d3
3. 检查PDF卡片，确定d1 d2 d3 对应的hkl
4. 计算晶带
5. 反过来检查G的方向和值
6. 角度计算公式
	1. 角度计算方法![[Pasted image 20251028171052.png]]
7. 用Weiss zone law检查向量的可加性
8. 计算zone axis 和电子入射方向
9. 再检查

![[Pasted image 20251028171236.png]]

![[Pasted image 20251028171242.png]]

##### 课堂小测
![[Pasted image 20251028172700.png]]


- #### 如果不知晓晶体结构（不知道abc）
- 选取P1P2P3，里中心最近的三个点，形成平行四边形
- 测量距离，角度
- rd=Lλ，从而得到平面距离

> 用多种方法缩小结构可能种类

- r方的比值得到d方分之一的比值，即可以开始晶格分析，确认晶格
- 假设平面，验证角度，得到晶格参数
- 叉乘计算晶带

### 可能出现的复杂情况
- 不可确认的误差
	- ![[Pasted image 20251028171250.png]]
- 晶带平行
	- ![[Pasted image 20251109143103.png]]![[Pasted image 20251109143953.png]]
在实空间中，就是保证得有一个晶带平行，还有一个平面确认平行才行

 > 如何在测量时就自动对准低指数晶带轴？
 > 这是一个**高度经验依赖但可系统学习**的手工技艺。核心是利用**菊池线（Kikuchi lines）作为"晶体罗盘"进行导航*
 
- 二次衍射
	- 经过一个晶体的衍射束又被另一个晶体衍射
	- ![[Pasted image 20251109144557.png]]

## 成像模式
### Contrast 衬度
Contrast (C): the difference in intensity (ΔI) between two adjacent areas 
- Human’s eyes can hardly detect contrast < 5-10 %
- $$C=\frac{I_2-I_1}{I_1}$$
- TEM contrast 的形成来自于电子束和样品之间的相互作用
- ![[Pasted image 20251109145654.png]]
#### Mass-Thickness Contrast
Mass-thickness contrast arises from **incoherent elastic scattering** of electrons, which is a strong function of the atomic number **Z** and the thickness **t** of the specimen
$$
C=\frac{\pi N_0 e^2}{V^2\theta ^2}(\frac{Z^2_2 \rho_2 t_2}{A_2}-\frac{Z^2_1 \rho_1 t_1}{A_1})
$$
- 如果电子低角度散射（小于5°），那么mass-thickness衬度就会占主要，当然也会和衍射衬度竞争
- 如果角度大于5°，布拉格衍射衬度几乎小时，得到低密度的散射束
- 重元素、厚度高会导致暗，反之就是暗场的特性
- 小光阑、小加速电压会使得衬度提升。（电子变少，能量变低能加深对比度）

#### Diffraction Contrast
- 一种特殊的振幅衬度，当达到布拉格角度时显现
- 产生于相干弹性散射 **Coherent elastic scattering** 
- 两束条件：只有一个强衍射斑点，和一个透射束斑点，其余衍射斑点全接近零
- 要想得到好的衬度，不必要达到两束条件，但是这样确实简化了图像的可解释性

- ### ***明场像和暗场像***
- 为了让电子散射图像转化为可解释的振幅对比，选择Direct Beam来形成明场像（Bright Field Images），用Dffracted Beam形成暗场像（Dark Field Images）
- ![[Pasted image 20251109152643.png]]

#### Phase Contrast
- 如果样品过于薄（小于20nm），则振幅衬度太小
- 但是不同透射光的相差是可以转变为强度差异，从而成为衬度
- 考虑相差衬度的TEM往往是High-resolution TEM，事实上绝大多数在放大倍数低的TEM下也能出现相差衬度
![[Pasted image 20251109160324.png]]
得到原子尺度的不同面的光亮信息？

- ### 晶格条纹（Lattice Fringe）
- 晶格条纹是指在晶体材料中，由于原子排列的规律性而形成的条纹状图案。这些条纹可以通过高分辨率透射电子显微镜（HRTEM）观察到，反映了材料的晶体结构和晶格间距等信息。晶格条纹的分析对于理解材料的物理和化学性质至关重要。

- ### **Fringe的本质：相位干涉图样**
晶格条纹是**相位衬度**的结果，而非直接的"原子投影阴影"：
- **形成**：电子波穿过晶格，被周期性势场调制相位，通过**离焦干涉**形成条纹
- **间距**：条纹间距**等于**晶面间距d（这是准确的）
- **位置**：但**相位波**的极大值/极小值位置，**不一定**对应原子列的真实空间坐标
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
Delocalization**离域效应**: the location of a fringe does not necessarily correspond to the location of a lattice plane 

晶格条纹并不是真实的结构，只是给晶格的空间、取向信息

#### Z Contrast
- 给出超高精细度 High-Resolution (Atomic), Mass-Thickness (Z) image contrast
- 用High angle annular DF 高角度环形衍射暗场 detector
- Z contrast images are also named HAADF images
- Z衬度不被物镜的失焦和样品厚度影响。
![[Pasted image 20251109162043.png]]
![[Pasted image 20251109162543.png]]

#### Kinematics of Diffraction Contrast
Kinematics 在广义上来讲是运动学，只考虑几何效应，而Kinetics考虑运动与力。
在这一章节，我们讲Kinematics定义为不考虑吸收效应进行建模。Kinetics更加复杂和精细，考虑复杂的光束能量的交换。

建模假设
![[Pasted image 20251109164834.png]]

- #### Howie-Whelan Equation
- ![[Pasted image 20251109165005.png]]![[Pasted image 20251109165110.png]]Extinction distance $\xi_g$ 是消光距离、特征长度，电子束进入晶体后，能量在透射和衍射之间周期性交换，每传播一个消光距离，就交换一次。完全就是数学定义。。。
  Deviation Parameter s **偏离参量** **晶体取向相对于布拉格条件的偏离程度**的核心参数。
- foundation of diffraction-contrast images,and the discussion limits to two beam conditions, the direct beam and Bragg diffracted beam.


##### Thickness and Bending Effects
- 衍射衬度也会被样品的厚度影响
	- 厚度的变化
	- 样品很薄，很容易发生弹性弯曲，也容易被defects影响
	- t厚度，描述厚度变化
	- s偏离参量，描述弯曲轮廓

Thickness fringe：当样品的厚度并不唯一，直射和衍射的能量交换周期便显现出来
![[Pasted image 20251109174833.png]]
Bend Contours：弯曲使得有些平面穿过布拉格条件，形成不同的衍射斑点
- 属于 Amplitude contrast 而不是相衬度
- 十分好用，因为把s分布展现出来
![[Pasted image 20251109174842.png]]

#### Contrast of defects 缺陷
界面：
- Translation Boundary RB：只有平移
- Grain Boundary, Phase Boundary：平移，旋转皆有
- Surface：另一相为真空或者气体

![[Pasted image 20251109175816.png]]

#### Contrast of Dislocations
![[Pasted image 20251109175907.png]]
![[Pasted image 20251109175923.png]]