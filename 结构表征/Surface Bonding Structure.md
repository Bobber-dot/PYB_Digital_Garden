---
Date: 2025-11-07
tags:
  - 材料学
aliases:
---
探测表面成键结构的目标是
- Elemental composition
	- species of atoms on surface 
	- Concentration of surface atoms 
	- Vertical distribution
		- on surface
		- near surface
- Mocular state of adsorbates
- Oxidation state of surface species

有四种检测方式：
- Secondary ion mass spectrometry (SIMS)
	- very high **sensitivity and analysis of H and He** as well as **isotopes, microanalysis and organic chemical analysis**.
- Ion scattering  spectrum (ISS)
- X-ray Photoelectron Spectroscopy (XPS)
	- obtain **abundant chemical information**, and the **damage** to the sample surface is the **least**, so the **quantitative analysis** is better
- Auger Electron Spectroscopy (AES)
	- very good **spatial resolution**, has very high **capability of micro-region analysis**, and can carry out **image of element surface distribution**.
are four widely used surface analysis techniques.

![[Pasted image 20251107144146.png]]

### ISS(Ion scattering spectrum)
用Inert gas ions（能量低于一些KeV） 去轰击表层，得到的scattered ions 可以使用双粒子弹性碰撞去近似

优势：
- 检测深度被控制在表层一层粒子
- 单层灵敏度在$10^{-2} -> 10^{-3}$  除了氢以外都可以检测
- 同位素可以检测

缺点：
- The scattering cross section and ion neutralization cross section are not well understood, so ISS can only be quantified after calibration with standard samples or other technologies.
- 没有任何化学信息
- 结构破坏
- 水平分辨率（100μm）
- 对重元素，水平分辨率低下

> 灵敏度用ppm或者ppb
> 能检测到杂质或元素的最低浓度

> 灵敏度用单层分数（Monolayer fraction）
> 10^-6 表面覆盖率

### SIMS(Secondary ion mass spectometry)
检测被打出来的离子

优势：
- 对某些元素非常敏感(10^-6 monolayer)
- 静态模式下，探测器深度仅限最表层
- 所有元素都可以检测，包括H和同位素
- 分辨率更高，1μm
- 在动态模式下进行同步深入分析。
- 

> 静态模式和动态模式，这是基于不同原子束参数而进行的操作模式
> 静态SIMS 低离子剂量、表面无损、作用于最表面
> 动态SIMS 高离子剂量，深度剥离，连续分析
> In-depth analysis 动态持续溅射，逐层剥离表面，分析不同深度的化学成分

劣势：
- 破坏表面
- 过程建模没有很好的解释其固有的复杂性
- 物理化学环境对SIMS的影响极大，使分析变得困难

### AES(Auger Electron Spectroscopy)
检测俄歇电子 

优势：
- 高分辨率的Monolayer-sensitive surface analysis
- 表面元素分布图
- 具有均匀灵敏度的元素深度剖析
- 对轻元素的灵敏度高

劣势：
- Surface Sensitivity: < 1 nm.
- Lateral Resolution: < 50 nm.
- Analytical Volume: 10-18cm3.
- Insulators are difficult to study due to surface charging.
- Surface may be damaged by the incident electron beam.


### XPS(X-ray Photoelectron Spectroscopy) Analysis
![[Pasted image 20251107152827.png]]

光电子分析

这个是指Electron spectroscopy 的化学分析应用 (ESCA)
- 光电子会让原子离子化
- 光电子的能量取决于X光光子的能量
- 每一个元素都有不同的电子排布（不测量氢原子）
- 样品的元素分析

### 四种方法的比较
![[Pasted image 20251107153258.png]]
![[Pasted image 20251107153305.png]]
![[Pasted image 20251107153321.png]]



# 光电子检测原理详解
![[Pasted image 20251111164028.png]]
![[Pasted image 20251111164047.png]]
光电子检测器内部结构

## 原理 光电效应
![[Pasted image 20251111164205.png]]

### 从哪里开始？费米能级
未占领的电子轨道能量是0，占据后成为$\varepsilon$。两种不同能量之间的吉布斯自由能为
$$
\zeta=1+\lambda e^{\frac{-\varepsilon}{T}} \qquad \lambda=e^{\mu/T}
$$
Fermi-Dirac distribution function
$$
f(E)=\frac{1}{exp(\frac{E-Ef}{kT})+1}
$$
> 展示了电子在能量状态下的概率分布，E_f就是费米能级（也是化学势），为两种能级分布50%概率的能级，也就是等效为电子占用的虚拟能级。
> 在一个系统中，所有电子都会占用同一个虚拟能级，这是一个期望值的能级，这个期望值被称为费米能级

我们假设表面是存在的，一般来讲，我们将零势能的表面定义为无穷远（Vaccum），但是更切实际的想法是把势垒的宽度定义得有限。我们把这部分势能定义为$\Phi$， 也就是说，从费米能级蹦跶一个$\Phi$ 我们就可以蹦出去了。
![[Pasted image 20251111170013.png]]
如图所示，即可知道$\Phi=(-\varepsilon-\mu)$ ，$\varepsilon$ 为电子在真空中的能量

>功函数是什么？
>将一个电子从原子逸出释放最小的能量。
>在光电效应中，光量子能量大于这个能量就可以产生光电效应。超过的能量就会成为动能

### 动能

![[Pasted image 20251111170638.png]]

> 俄歇电子也会有峰，不过这个峰和光子能量无关

### 结合能
结合能以元素的最终电子排布为准

#### 导体
![[Pasted image 20251111170824.png]]
费米能级没有变化，变化的只是从化学势到真空的损耗能量。

#### 绝缘体
![[Pasted image 20251111171059.png]]
非导体会有介电效应，导致表面积累电荷，导致了表面电荷能，由于这源于材料内部的电场，导致费米能级的移动

![[Pasted image 20251111171457.png]]

### X-ray行为，影响结果
#### Attenuation
吸收、穿过物质会损失X-ray的能量。此乃指数过程，因此，光强度永不为零。

两种方式使得射线衰减
- 康普顿散射
- 光电子效应

测量
- 半衰距离
- 线性衰减参数
- 质量衰减参数

- ### 行为
- ![[Pasted image 20251111172606.png]]
- 其中光电子是这一项：![[Pasted image 20251111172626.png]]
- 电子发生非弹性碰撞的平均自由路径：如果这个路径比较短（5-10埃对于50~100eV），那么表面敏感度高。
- 广泛的，这个自由路径在各种元素中都相同，只取决于能量
- ![[Pasted image 20251111173344.png]]
最终会得到非弹性的背景
- 越深的电子，越少的动能
- 极深的电子无法逃逸
- 展现出阶梯状的能量-数量分布
- ![[Pasted image 20251111174243.png]]

##### 康普顿效应
- 光子撞上了自由电子、比较不稳定结合的电子、外层电子
- 电子吸收少量能量，转向飞走
- 光子失去了一些能量，转向、散射。

![[Pasted image 20251111172205.png]]

又称为非相干散射，因为光子能量的改变不一致，不总是有规律。光子能量的改变主要取决于散射角度，而不是散射介质。

光子能量越强：光子保留的能量越弱，电子能量越强，光子散射角度更大

##### 探测深度
探测深度和表面敏感度
- 探测深度被X射线与样品平面法线的夹角影响。角度越大，深度越小。
- 探测深度主要被接收器和样品平面的夹角影响，角度越大，电子在此方向越难逸出，导致表面敏感度提升。
- ![[Pasted image 20251113193042.png]]

主要是因为电子被提取的方向固定，主要看电子逃逸了。

### 分析处理原理
#### X射线
![[Pasted image 20251113194309.png]]
常常使用这些元素来发射单色X射线

![[Pasted image 20251113194355.png]]
用Monochromator来进行单色滤镜，以此来减少信噪比，让峰宽变窄，无卫星峰、幽灵蜂

#### 探测器
电子倍增器，多次计数得到倍增后的结果。

#### 核外电子结合能
![[Pasted image 20251113195610.png]]
![[Pasted image 20251113195853.png]]
![[Pasted image 20251113195923.png]]
磁量子数轨道会有能量分级，原因是自旋会被自身原子的雌场耦合影响。

## 应用
### 样品的准备
1. 固态样品
	1. 样品量得限制
	2. 真空隔离需要使用转棒技术
	3. 注意表面成分状态的防护
2. 粉状样品
	1. 双面胶固定
	2. 板压法的动态分析要求——加入，表面放映，表面处理等
3. 特殊样品的预处理
	1. 含有易挥发物质的样品：用加热或者溶剂清洗
	2. 表面具有有机污染的样品：用有机溶剂清洗
	3. 弱磁性样品：去除磁性操作，磁力样品不能进入分析室（电子会偏转）
4. 绝缘体样品或低导电率样品
	1. 必须测量电量

- 测量分析木乃伊的成分
- 高分子材料
- 自组装分子层

和EDS的区别：EDS利用二次X射线，表面灵敏度不高
![[Pasted image 20251113202719.png]]

## XPS光电子能谱的分析
在实际实验结果中，XPS检测峰、背景的来源？影响因素？图怎么看？
![[Pasted image 20251113203407.png]]
### XPS光电子能谱的元素
- 峰位置：取决于元素、轨道、化学态
- 峰强度：和元素的丰度和灵敏度成正比
- 对称性：非对称性，产生于在费米能级附近的低能量电子-空穴激发的金属峰，从价态能级到未占据的导电能级。
- Peak full width at half maximum (FWHM) 峰值半高宽
	- ![[Pasted image 20251114141047.png]]包含元素的自然宽度和入射x射线的宽度，设备的设定和样品的状态。正常来讲，第一峰有0.3-1.7eV的FWHM
	- 

#### 光子能量的影响
![[Pasted image 20251114142035.png]]

根据公式，能量越高，动能整体右移，结合能不变

#### 背景的来源
由于能量损失，测得结合能会偏高，动能会偏低，形成阶梯状的背景图像。
![[Pasted image 20251114142231.png]]

- # **Background Correction**
- 选择合适的用于减除的能量区间
- 用较高的KE线，作为基准线
- ![[Pasted image 20251114142719.png]]
#### 峰的来源
- 峰的强度测量元素的丰度
- 峰的位置决定元素的组成
- FWHM峰值半高宽表征化学态变化和物理影响
- 峰形状的改变可以表征：化学键数量的变化，样品状态的变化
- ![[Pasted image 20251114143638.png]]
### 结合能如何改变？
> 模型假设
> 假设光电子所在的轨道，在光电子发射前后的能量不变。（称为 Frozen-orbital approximation）在这种假设之下，XPS实验测量的值为： **negative Hartree-Fock orbital energy**

$$
E_{B,K} \approx -\varepsilon_{B,K}
$$

> [!NOTE] 实际上的结合能
> 会表示为N-1电荷的重新调整后的最小能量
> $$E_B=E_{f}^{N-1}-E_i^{N} $$

#### Binding Energy Shifts
X射线光电子能谱（XPS）中的**结合能位移**（Binding Energy Shifts）是分析材料化学状态和电子结构的核心依据。
- 化学位移：源自于原子价态的变化
- 物理位移：弛豫效应（周围电子屏蔽了光电子发射后产生的电场）、荷电效应（绝缘体表面积累了正电荷）、表面偶极层（分子取向以及吸附产生的真空能级变化）

##### 纯元素情况
点电荷模型：
![[Pasted image 20251114150334.png]]
其他方法：通过观察电子的作用变化来推测结合能的变化


- ## **不同原子序数的不同轨道的结合能**
![[Pasted image 20251114151845.png]]
- ## **结合能的灵敏度**
![[Pasted image 20251114151852.png]]
- ## **不同元素能量不同**
![[Pasted image 20251114152129.png]]

##### 化合物中的情况
轨道电子的能级对原子的化学环境十分敏感
- Core level：核心能级电子是指主量子数 **n 较小** 的内层轨道电子（如1s, 2s, 2p, 3d等）
	- 在气态，核心电子的电离能差异是很明显的
	- 在固态，该原子的所有核心能级大约都移动了相同的量（<10 eV）
- 原子的总体电荷的变化和Chemical Shifts相关
	- 取代基的个数
	- 取代基的电负性
	- 氧化态（不可靠，取决于成键的离子性和共价性）

Chemical shift analysis is powerful tool for **chemical composition**, **functional group** and **oxidation state** analysis.

- ## Electronegativity Effects
- ![[Pasted image 20251116195642.png]]
- 当价态电子被拉走，核心层的电子会被拉向原子核，导致结合能上升

- ## Spin-Orbit Coupling

> Spin-Orbit splitting
> 具有自旋的粒子（如电子、核子）在运动时，其**内禀自旋磁矩**与因轨道运动产生的**等效磁场**发生相互作用，从而导致不同总角动量状态的粒子具有不同的能量这种效应会消除能级的简并性，使单个能级分裂为多个子能级。
> 这个角动量需要轨道角动量和自旋角动量两者一起作用，没有轨道角动量（1s）轨道，电子云呈现完美球形，自旋不被磁场影响。


> 复习：
> 主量子数n，角量子数l，磁量子数m，自旋量子数ms
> n 电子所在的层级
> l 电子的亚层或能级 （0~n-1）
> m **磁量子数 m**（通常记作 `m_l`）的物理本质是**角动量在z轴方向上的投影**（0，±1，±2，...，±l） 一共（2l+1）个取值
> 自旋量子数 ms=±1/2

例如，2p轨道，就有l=1，总角动量是总角动量 **J** 是 **L** 和 **S** 的矢量和，其量子数j的取值为
$$j=l±s=1±\frac{1}{2}$$
- 每个能级有2j+1个状态（简并度Degeneracy）
- s轨道一般没有spin-split effet
- p，d，f ...轨道有double peaks，j值越小说明结合能越高。
- The level of spin-split effect increases with Z. Z越大这个效应越强
- The **spin-split effect** will decrease with the increase of the **distance** between the orbital and the atomic nucleus.

- ## Shake-up/Shake-off 振激/振离
- 结果来自最终态构型弛豫中释放的能量（由于经历光电子发射的核心电子失去了屏蔽效应）。
- 单极跃迁 Monopole transition：只有主量子数发生变化。自旋和角动量不变。
- Shake-up：用于将价电子激发到**束缚态**的弛豫能量（单极激发）。（分立）
- Shake-down：用于将价电子激发到**非束缚态**的弛豫能量（单极电离）。（连续）

>处于**Bound State  束缚态**的电子虽然能量升高，但仍在库仑势阱中，有确定的量子数（n, l, m），轨道半径更大但仍是局域化的。
> **Continuum States** **连续态** 的电子电离到自由电子态了

- ![[Pasted image 20251116223359.png]]![[Pasted image 20251116225137.png]]
- #### **本质上是光子能量部分分配给了价电子产生的现象，形成卫星峰。在弛豫效应中产生的能量分配给了价电子**

- ## Electron Scattering Effects
- ![[Pasted image 20251116230449.png]]光电子传播过程中和其他电子作用
- 当足够多的电子通过固体时，它们会使自由电子整体振动。振动频率取决于材料的类型。因此，这种振动所需的激发能量是不同的。体材料振荡激发源的基频为 ωb，能量损失是量子化的，为 ђωb。对于同一种元素，会出现一系列间隔相同的峰，并且随着结合能的增加，强度逐渐减弱。
- ![[Pasted image 20251116230746.png]]
### Principles of XPS Quantitative Analyses
$$\begin{split}
I &= NsDJLlAT \\
where:\ N &= atoms/cm3 \\
s &= photoelectric\ cross-section/cm2\\
D &= detector\ efficiency\\
J &= X-ray flux,\ photon/cm2-sec\\
L &= orbital\ symmetry\ factor\\
\lambda &= inelastic\ electron\ mean-free\ path\ cm\\
A &= analysis\ area\ cm2\\
T &= analyzer\ transmission\ efficiency\\
Let\ denominator =\ &elemental\ sensitivity\ factor\ S\\
N &= I/S\\
\end{split} $$
![[Pasted image 20251116231615.png]]
![[Pasted image 20251116232607.png]]
![[Pasted image 20251116232702.png]]


## 软件&XPS数据处理
### 数据处理以及画图步骤
![[Pasted image 20251116233443.png]]
1. 使用Excel打开原始数据，提取表格中的数据并将其分为全谱数据和各元素的单次扫描数据；
2. 选择待分析元素谱图对应的数据区域（例如宽谱下方的数据）；
3. 将数据复制到Origin软件中，以结合能（BE）为横坐标、强度（I）为纵坐标作图，得到全谱图；
4. 不同元素对应有特定的结合能，可与标准XPS谱图（NIST数据库）进行比对；
5. 识别始终存在的元素谱线，如C和O的谱线；
6. 识别样品中主要元素的强谱线及其相关的次强谱线；
7. 识别剩余的弱谱线，并推断它们可能是未知元素的最强谱线。
### 原子浓度
操作步骤：
1. 打开原始数据后，在Origin软件中以结合能（BE）为X轴，以强度列/透射值得到的有效强度I为纵坐标绘制谱图；
2. 根据谱图，对相应元素的峰面积进行积分得到I；元素灵敏度因子S可在表格中查找（见附录RSF）；
3. 使用公式ni/nj=(Ii/Si)/(Ij/Sj)，即可得到元素的浓度比。

### 峰处理
1. 对于半导体和绝缘体，在测量化学位移前应进行荷电校正。
2. 通常情况下，光电子谱的双峰间距保持不变，该间距可在标准谱图中查到。
3. p、d、f等能级（如p3/2与p1/2）的强度比是固定的：p3/2:p1/2=2:1；d5/2:d3/2=3:2；f7/2:f5/2=4:3。在分峰过程中应遵循此规则。例如，W 4f谱中相同价态的W 4f7/2与W 4f5/2峰面积比应为4:3。
4. 被测原子的氧化态越高，或与电负性更强的原子结合时，其电子结合能越大。
5. 应根据样品的实际情况进行分峰/谱峰分离分析。

### 电荷修正
I. 将C元素标准峰（284.8 eV）与实际测得的峰位进行比较，可得到偏差值Δ；
II. 将Δ值加到待评估的元素上，以获得正确的峰位。

### 使用软件“XPS Peak 4.1”进行峰分离
1. 步骤1：添加一对峰。先添加一个峰并选择峰形（基于元素的主峰）。
2. 步骤2：固定该峰的位置。
3. 步骤3：在配对峰中添加另一个峰。该峰与第一个峰之间的距离以及面积比可以固定。
4. 步骤4：依次添加第二对峰。
5. 步骤5：在设置好所选拟合峰的近似参数后，使用"Optimise All"进行拟合，可重复操作直至拟合后的总峰能基本与原始峰重合。
6. 步骤6：拟合完成后，点击XPS Peak Processing中Region Peaks下方的0、1、2和3可查看各峰的参数，在XPS Peaks中变红的峰即为所选中的峰。可根据拟合情况调整各峰参数，例如取消峰位固定、改变峰宽等，然后点击Optimise All进行拟合。
7. 步骤7：拟合完成后，最好将% lorentzian-gaussian参数固定在大约20%，这是一个合理的数值。
8. 步骤8：完成所有拟合后，点击"Save XPS"保存图形。下次点击"Open XPS"即可打开图形并继续处理。

#### Data output from XPS Peak:
(1) 数据 → 打印含峰参数的数据
可通过峰面积计算该元素在不同峰位的化学含量比。

(2) 数据 → 导出到剪贴板，将图形和数据一同复制到剪贴板，直接粘贴到文档中。

(3) 数据 → 导出（谱图），可将拟合数据保存为“.Dat”格式文件，然后从Origin的多列数据栏中打开，即可获得多列数据并在Origin中绘制拟合图形。