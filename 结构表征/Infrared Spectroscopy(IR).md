---
Date: 2025-11-23
tags:
  - 材料学
aliases:
---
## 1. 为什么要有IR？
XRF, XPS and AES not enough for identifiy the compound
- Allotropes 同素异形体

![[Pasted image 20251123162146.png]]

## 2. IR的主要原理
### 2.1 分子弹簧模型——振动从何而来？
键是什么？
- A chemical bond is an attraction force between atoms or molecules and allows the formation of chemical compounds, which contain two or more atoms.

键长是什么？
- Bond length or bond distance is the **average distance** between nuclei molecule

键可以看做一个**弹簧**，挤压要比拉伸要难。如果过度拉伸会导致断键（Dissociation）
如果撞击这个分子，他会震动，复杂的震动是**多个normal振动模的叠加**
分子震动 携带化学键的信息

### 2.2 自由度 Degree of freedom——振动有多少种？
![[Pasted image 20251123165219.png]]

N 个质点组成的体系要有3N个坐标来描述。如果存在m个完整约束，那么系统自由度为 S=3N-m

线性分子：
- 平移自由度 3
- 转动自由度 2
- 振动自由度 3N-5

非线性分子
- 平移自由度 3
- 转动自由度 3
- 振动自由度 3N-6

根据自由度进行能量的分析：
$$
E=E_0+E_t+E_r+E_v+E_e
$$
E0 零点能，Et 平移动能，Er 转动动能，Ev振动动能，Ee 分子内电子转移能

每个能量都有对应的能级，当电磁波激发这个样品，能够反映样品的信息。红外光谱仪，近红外、远红外光谱仪都是分子运动相关的。所以他们也被称作分子质谱仪（**molecular spectrometry**）
![[Pasted image 20251123170326.png]]

### 2.3 简正模 Normal Vibration 简正振动——振动分析的方法/建模？
#### 2.3.1 双原子模型建模（简谐振子）
双原子模型，在轴向方向震动

$$
\sigma = \frac{1}{2\pi c}\sqrt{\frac{k}{\mu}}
$$
k: Elastic force constants between molecules μ: reduced mass
1/μ = 1/m1 + 1/m2
#### 2.3.2 双原子模型建模（非简谐振子）
![[Pasted image 20251123170950.png]]

绿色为简谐振子
莫尔斯函数很好地描述了非简谐振子。 Morse Function 
### 2.4 转动和振动的结合 Combination of vibration and rotation ——红外光谱的源头
#### 2.4.1 转动震动结合后的能量形式
同时激发转动和震动模是可行的。转动和震动的总能量
![[Pasted image 20251123181225.png]]
l为住转动能级，n为震动能级
（只是展示一下量子化的式子
#### 2.4.2 转动振动光谱 Spectra 

> [!NOTE] 能级图
> ![[Pasted image 20251123181653.png]]
> - 如图可见，转动能级所需的跃迁能量低，因此电磁波谱会到远红外区和微波区
> - 分子的转动能量主要来源于分子形状质量
> - 转动能级只对气体有意义。液体固体会因为分子作用力影响转动
> - 转动能量Er是量子化的

#### 2.4.3 双原子系统的转动建模（围绕质心转动）
![[Pasted image 20251123181956.png]]
对于转动能量的双原子模型建模（刚性Rigid）：以质心为转动轴
$$\begin{split}
I_c &= r_1r_2(m_1+m_2) \\
r_1 &= \frac{m_2r}{m_1+m_2} \\
r_2 &= \frac{m_1r}{m_1+m_2} \\
I_c &= \frac{m_1m_2r^2}{m_1+m_2}=\mu r^2 \\
\mu &= \frac{m_1m_2}{m_1+m_2}\\
\mu &\ is \ the \ reduced \ mass
\end{split}$$
转动能级公式：v为波数（$1/ \lambda$），B的单位是cm-1，知道B可以知道Ic，从而知道键长。
$$\begin{split}
v &= \Delta E/hc \\
E_J &= \frac{\hbar^2}{2I} J(J+1) = B J(J+1) \\
B &= \frac{h}{8 \pi^2 I_c}
\end{split}$$
#### 2.4.4 转动、振动、电子态能级图
- 这幅图展示了转动能级、振动能级的嵌套关系（电子能级>振动能级>转动能级）
- 这幅图有电子能级，原理如下：
	- 电子的状态决定了分子的几何性质和形状，因此能后大范围地改变其能量状态
![[Pasted image 20251123185203.png]]

#### 2.4.5 多原子体系中的简正振动态 Normal Vibration of Polyatomic
Normal vibration: the molecular centroid remains unchanged during vibration.
- Normal Vibration
	- Stretching(Along the axis)
		- Symmetrical Stretching Vibration 对称拉伸
		- Asymmetric Stretching Vibration 非对称拉伸
	- Bending(Change in the bond Angle)
		- Out-of-place Bending Vibration 非共面弯曲 
			- Wagging 前后摇摆
			- Twisting 前后交错
		- In-place Bending Vibration 共面弯曲
			- Scissoring 剪刀式
			- Rocking 左右摇摆

![[屏幕录制 2025-12-17 175802.mp4]]
#### 2.4.6 简正振动 Vibration Modes 的特征能量 Specific Energy
![[Pasted image 20251123202417.png]]
- 不同的简正态的吸收特征波数不同
- Each vibration, called a **fundamental mode**, has a specific energy (or frequency) which depends on the atoms involved in the motion (i.e., mass of the weights), the type of motion, and the bond strengths (i.e., the strength of the “spring”).  In this case, the carbon-hydrogen stretching appears in the higher energy region of the spectrum (about 2800-2900 cm-1), with the **asymmetric stretching**  being slightly **higher in energy than** the **symmetric mode**.  The **bending or scissoring mode** appears at about 1470 cm-1.  The **twisting mode** appears at about 1300 cm-1 and the **rocking mode** absorbs at a  much at a much lower energy of about 720 cm-1.
#### 2.4.7 以$CH_2$为例，IR spectrum长啥样？
- 就比如![[Pasted image 20251217180437.png]]
	- 波数越大能量越高，可见==拉伸吸收能量要大于弯曲能量的==
- ![[Pasted image 20251217181024.png]]
	- 对于聚苯乙烯。A polymer with CH2 and benzene groups. For interpretation purposes, we can describe **what are called functional groups** which always occur **at similar positions in the spectrum**（在光谱中的稳定存在——官能团，官能团定义的由来）: OH vibrations, CH2 vibrations, Aromatic vibrations.  These vibrations are spread over the entire spectrum, and most of them are pretty well known.  However, the region between 1500 and 900 cm-1 is basically built up from **very specific complicated vibrations of the entire molecule**（**"Fingerprint zone"**）.  Therefore, this region is different for every molecule, and like a fingerprint, no two molecules have the same fingerprint region.  We can use this part of the spectrum for the final identification...

#### 2.4.8 典型的FTIR图，看看位置大小关系
![[Pasted image 20251217181808.png]]

### 2.5 IR吸收的原理 Principle of IR Absorption
#### 2.5.1 吸收的原理——共振
1. 用连续的红外光束对样品进行激发
2. 某一频率的，与分子的振动、转动能量**相等**的能量会被分子吸收
3. 分子会从低能量态跃迁到高能量态，产生 Molecular Energy Level Transition
4. 红外分子吸收光谱显现
5. 吸收带的强度取决于**偶极矩（Dipole Moment）**
#### 2.5.2 红外吸收光谱的选择性 Selection Law of Infrared Absorption Spectrum
1. In the vibration process, only the vibration mode in which the **dipole moment** changes can absorb infrared. The absorption band appears in the infrared spectrum. It means this vibrarion mode becomes infrared actives; 就是会吸收动量改变偶极子的能级
2. The transition law of vibration spectrum. 
   $$\Delta v ±1,±2$$

> [!tip]  Transition Law of Vibration Spectrum
> - 主要情况
> 	- 这个规则仅在谐振子近似下严格成立，即势能曲线是完美的抛物线。
> 	- 在红外吸收/发射过程中，分子只能在相邻的振动能级之间跃迁，不能"跳过"中间能级。
> - 例外情况
> 	- 真实分子有**非谐性**（势能曲线不是完美抛物线），所以也存在：
> 	- **Δv = ±2, ±3...** 的**弱跃迁**（称为**泛音** overtone）但强度仅为基频的~1%或更弱

#### 2.5.3 偶极矩决定性作用
Vibration -> Dipole moment changes -> infrared absorption 
震动会改变**偶极矩**，从而吸收能量
但是：
- 非极性同核双原子分子的偶极矩在振动过程中不发生变化，也就是说不能观察到振动光谱，例如 O2 和 N2 不产生红外吸收光谱。
- 大气中的水蒸气和二氧化碳会产生红外吸收光谱，特别是水蒸气具有更宽的红外吸收光谱，对样品的干扰更大


> [!NOTE] 频率和强度
> - 分子振动的频率是由分子成键的力系数决定的，主要由分子的平均偶极矩决定。
> - 因此偶极矩和频率是有一定关系的。
> - 然而，如果说在震动的过程中改变了偶极矩，这个改变决定了吸收的消光系数，即决定着吸收带的强度。
> 总结来看，==分子的偶极矩决定着分子振动的频率，分子偶极矩的变化决定着消光系数。偶极矩确定了消光在图上的位置==，可以说相当重要。
> ---

#### 2.5.4 偶极矩的公式
$$
\mu = qd
$$
这是一个矢量，其方向定义为从正中心指向负中心。
![[Pasted image 20251123194906.png]]

#### 2.5.5 FTIR的吸收性
- Beer-Lambert Law
- $$\begin{split} A&=\varepsilon lc \\ A&= absorbance \\ \varepsilon &= absorptivity \\ l&=path\ length \\ c &= concentration \end{split}$$
- 不同的原子分子吸收不同
- 同一种原子分子，吸收相同的波长
- 辐射吸收的不同程度，与分子原子的不同浓度相对应

## 3. 红外仪器 IR Intrument and Factors
### 3.1 红外电磁光谱仪——按光带位置区分
![[Pasted image 20251217200803.png]]
- Point out the low and high energy ends of the electromagnetic spectrum, from long wavelengths of light at 10-5 cm-1 (radio waves) to 109 cm-1 (x-ray energy).
- Note from our chart that a molecule behaves differently when exposed to these different energy levels. 分子在不同的频率光行为不同，比如X射线会打出中子，而紫外线打出电子。
- 单位习惯用波数（Wavenumber）因为用这种方法可以避免超大的数字，只需要200-5000就可以记录了
- Our FT spectrometers allow us to measure transitions from the visible (25,000 cm-1) through the far-IR (50 cm-1) spectral range. These regions yield specific information regarding functional groups, their associations and relative quantity. These regions may be examined with **three types of spectrometers**; 
	- **Filter Spectrometers** that provide narrow bandwidths (and little, but specific information such as single gas analyzers), and Dispersive and **Fourier Transform spectrometers** that provide broad spectral bandwidths (information rich, both non-specific and specific).

### 3.2 红外电磁光谱仪——按原理区分（演变）
#### 3.2.1 传统的 IR Spectroscopy
色散光谱（也叫光栅、扫描光谱）
每次就只能做一个波长的
#### 3.2.2 改良款 Development of IR Spectrometers
Development
- Prism type --- The first generation infrared spectrometer; 棱镜型 
	- ![[Pasted image 20251123195858.png]]
- Grating type --- The second generation infrared spectrometer; 光栅型 
	- ![[Pasted image 20251123195850.png]]
- Fourier Transform Type --- The third generation of Infrared spectrometer (FTIR, Fourier Transform Infrared Spectroscopy).
![[Pasted image 20251123201133.png]]


![[Pasted image 20251123190358.png]]


- 用红外光束（连续波长）照射样品。
- 如果某个频率对应的能量等于分子的振动或旋转能量，它将被分子吸收。
- ΔE = E’’-E’ = hv = hc/λ 能级跃迁。
- 分子从低能态跃迁到高能态，产生分子能量。
- 出现红外分子吸收光谱。
- 吸收带的强度取决于偶极矩。
#### 3.2.3 傅里叶变换红外光谱——FTIR
##### 3.2.3.1 什么是FTIR？
- Light passes through an **interferometer**（干涉仪） and then transmitted through the sample and arrives at the detector. At this point a Fourier transform is performed on the **interferogram**（干涉图） to obtain usable data;
- 可以用于：
	- 识别未知材料
	- 检验样品的质量
	- 识别混合物的组成成分

原理上：红外光谱的 **强度h(δ)** 与形成该光的 **两束相干光的光程差δ** 之间有傅里叶变换的函数关系。FT可以将时域信息转换为随时间变化的频域信息。FT在无限的时间上识别信号，然后把其中的频率信息提取出来，并转换为有限的频率谱图。

FTIR的核心思想是：**不直接测量"强度 vs 波长"，而是测量"强度 vs 光程差"，再通过傅里叶变换计算出光谱**。
###### 核心部件：迈克尔逊干涉仪
```
光源 → [分束器] →  →  →  →  →  → 探测器
           ↓     ↓       ↓
        透射50%  反射50%  两束光返回叠加
           ↓     ↓
        固定镜   动镜（匀速移动）
```
**工作流程**：
1. 红外光打到**分束器**上，分成两束强度相等的光。
2. 一束射向**固定镜**（光程不变）。
3. 另一束射向**移动镜**（光程随时间线性变化）。
4. 两束光返回后重新组合，产生**干涉**。
5. 当动镜移动时，两束光的光程差（δ）连续变化，探测器记录到的信号 **不是光谱，而是干涉强度 vs 光程差** 的图。
6. 随后对这个图进行傅里叶变换即可。
##### 3.2.3.2 FTIR的优势
- 非常的快。FTIR一瞬间测量所有的频率
- 超高信噪比->更高灵敏度
- 只有一个移动的部件，非常简洁的结构
- 一般用He-Ne激光，在产品内部已经标定好了

![[Pasted image 20251123200854.png]]
#### 3.2.4 影响因子
##### 1. 样品的均质性
- 基体和分析物颗粒大小均匀 
- 颗粒在基体中分布均匀
	- 研磨固体样品以获得尽可能小的颗粒尺寸
		- 减少镜面反射 
		- 增强谱带强度
一些样品分析方法，尤其是针对液体样品设计的通过将液体沉积到粉状支撑基体上的方法，可能导致分析表面附近样品浓度较高。 
在这种情况下，可能会注意到相对峰强度的变化。特别是，较弱的吸收波长在样品浓度较高时通常会被衰减。

##### 2. 样品的浓度
稀释样品的方法
Uniformly mix analyte in a non absorbing matrix
- Alkali halide diluents 
	- KBr
	- KCl
	- Diamond powder
	- CsI
	- HDPE
可以通过将分析物混入红外透明基质（如卤化碱盐）来制备粉末样品。最常用的两种稀释剂是溴化钾和氯化钾。

可以用漫反射分析
注意折射率效应
##### 3. 样品的折射率
![[Pasted image 20251123211219.png]]
高折射率材料会出现负吸收峰，Restrahlen bands.余辉带
![[Pasted image 20251123211227.png]]
当稀释之后，余辉带就消失了，一个完全漫反射的数据得到了。

##### 4. 样品粒子大小
![[Pasted image 20251123210905.png]]
##### 5. 制样品的方法
![[Pasted image 20251123210920.png]]



## 4. 红外衰减全反射Attenuated Total Reflectance (ATR)
### 4.1 是个啥？！
- 衰减全反射就是一个红外采样的技术
- 它测量当红外光束发生全内反射（就是全反射）并接触样品时的变化。
- ATR允许对没有怎么准备的样品进行快速定量或者定性的分析。

### 4.2 优势
1. 无破坏性
2. 不需要怎么最准备样品
3. 强红外吸收材料适合做表面分析
4. 要避免界面有二氧化碳和氧气

### 4.3 原理
![[Pasted image 20251217220520.png]]
全反射发生的倏逝波与样品相互作用

### 4.4 过程
- Therefore it is important to obtain good contact between the crystal and the sample.
- This can be achieved by pressing the sample down on the crystal.
- If the substance under study is a liquid, it is simply dropped onto the crystal, thereby obtaining optimal contact.

### 4.5 FTIR采样系统
![[Pasted image 20251217220758.png]]
## 5. FTIR光谱的理解应用——How to analyze a FTIR 
![[Pasted image 20251218232319.png]]
此图展示大致的官能团分布

### 5.1 第一判断：两个方法
- 排除法（Exclusive Method）
	- 如果一定波数范围的光谱带（**spectral band**）正好对应某一常用的官能团的特征波数，则如果没有这个光谱带，则没有这个基团
- 包含法（Inclusive method）
	- 对于光谱上的强吸收带，可以参考数据库并确定它属于哪个官能团。
- ![[Pasted image 20251218233142.png]]
### 5.2 第二判断：三个特征
- 位置
	- 重要的表示官能团存在的特征
	- 不同的很多官能团吸收同一个频率区间
- 形状
	- 宽的**Broader**：氢键和离子官能团能够组成非常宽的红外光谱
	- 分裂的 **Spiltted**：分裂的谱带可以用于研究分子之间是否有关联，以及**Symmetry** 对称性、**Rotation Isomerism** 旋转异构、**Tautomerism** 互变异构
- 相对强度
	- 相同红外光谱的不同的谱带之间的比较，进行定量用
	- 特定官能团和元素的存在：
		- 比如当CH键和氯原子相邻时，其振动带的变形会让他从弱到强（强度）
	- 峰的强度和样品的厚度、含量以及状态有关。

### 5.3 第三判断：标准光谱图
标准光谱图在网上、数据库可以找到
- Sadtler Spectra 
	- 98%以上纯度的化合物红外光谱
	- 工业商品光谱图
	- 包括多达221600张红外谱图
- 赫梅尔(Hummel)和肖勒(Scholl) Spectra （Published paper-based data）
	- Volume 1. Polymer structure and infrared spectroscopy 
	- Volume 2: Infrared spectroscopy and identification methods for plastics, rubber, fibers and resins 
	- Volume 3: Infrared spectroscopy and identification methods of auxiliaries 

### 5.4 第四判断： 波峰频率定律
#### 5.4.1 定性比较
相同的官能团，大多数的拉伸振动吸收频率和强度要高一些，而弯曲（Bending）要低一些。
![[Pasted image 20251219160649.png]]
- 键强度越高，吸收频率越高
- 质量越轻，吸收频率越高

#### 5.4.2 峰位置的大致趋势，定量
1. 拉伸的频率高于相应的弯曲的频率，弯曲要比拉伸更简单
2. 非对称拉伸频率要基本高于对称拉伸频率
3. 连接氢的化学键的拉伸频率要高于连接其他重原子的
4. 普遍有，三键频率＞双键频率＞单键频率（连接氢的除外，这个太快了）
![[Pasted image 20251219161246.png]]
这个公式就是简谐振动的公式，约化质量μ、劲度系数k、波数v。

### 5.5 峰强度定律
- 价态键的振动产生的偶极矩变化越强，吸收峰越强
- w（weak），m（medium），s（strong）
- 其中一个影响强度的选择定律是偶极矩的改变必须发生在振动吸收红外光的前提下。
- 碳氢双键的拉伸吸收一般非常强，因为该模式下偶极矩的改变非常强。

### 5.6 峰个数定律
自由度计算振动自由度
![[Pasted image 20251219162254.png]]

### 5.7 第六判断：相邻官能团的影响
- 相邻官能团
	- 理论上：没有什么机械和电子的耦合（**Coupling**），振动频率是和计算一致的
	- 事实上：不同的官能团相互影响-> 能谱带的位移->根据谱带的位移，相邻的分子官能团可以知晓

#### 5.7.1 诱导效应：The Inductive Effect
> 定义：
> In covalent bonds with a certain polarity, different degrees of electrostatic induction effect are generated with different electronegativity of substituents, resulting in the change of charge distribution in the molecule, thus changing the force constant of the bond and the vibration frequency.
> 诱导效应是指在有机分子中引入一原子或基团后，使分子中成键电子云密度分布发生变化，从而使化学键发生极化的现象，称为诱导效应。

举个例子
![[Pasted image 20251219162913.png]]
Acetone Componds 羰基， 如果连接Halogen卤素取代基会导致更高的振动频率，因为取代基的电负性提高，C=O键更缺电子、键长下降、K上升、频率上升。
![[Pasted image 20251219163112.png]]

#### 5.7.2 共轭效应：The Conjugation Effect
大π键效应，使得分子往低频率振动位移。
- Induced and conjugated effects often coexist in molecules, and the effect that **predominates** will determine the direction of the shift in the band. 诱导和共轭哪个更强往哪跑

![[Pasted image 20251219163429.png]]
分子轨道理论？轨道能级更多导致的？nm记住得了，。

#### 5.7.3 氢键效应： The H-bonding Effect
- H-Bonding
	- 分子间氢键
	- 分子内氢键：和溶剂无关，样品稀释后无法产生分子间氢键
- ONFSP等能形成氢键的原子（分子内氢键），会让X-H键变得：
	- 拉伸：氢键越强，带越宽，吸收峰越强，向低吸收频率移动
	- 弯曲：氢健越强，带越窄，向更高频率运动（环形约束让弯曲振动更快）

Plus： 氢键本身也可以被检测到。
![[Pasted image 20251219164945.png]]


#### 5.7.4 耦合效应： The Coupling Effect
定义：当两个相同或相似频率的官能团结合在一起时，就会发生耦合。原始频率的高频和低频两侧都会出现一个带宽。（Splitting）
![[Pasted image 20251219165725.png]]

#### 5.7.5 环张力效应： The Ring Strain Effect
![[Pasted image 20251219165854.png]]
张力越高，C=O键的键能提升，伸缩越困难，频率提升

### 5.8 第七判断：状态改变的效应
- 不同的聚集状态会使得同一种化合物有不同的频率和强度
- 某些聚合物的红外光谱的气态和液态大不相同
- 相比于气态，峰带的频率、数量、强度都会由于在液态中的络合或者氢键而大幅度改变

### 5.9 第八判断：溶剂效应
- 分子结构复杂难以计算
- 分子或者官能团的振动被周围的分子和官能团所影响
- 频率改变
	- 会使分子或官能团一 一对应于一个峰变难
	- 峰的位移被用于理解分子或基团和周围分子或基团的相互作用

例如不同的溶液中，IR的特征吸收峰不同
	- 溶剂分子的极性、介电性导致了溶质分子的振动频率不同
	- 非极性高度对称的溶剂常常用于消除这些影响

### 5.10 第九判断：其他效应
![[Pasted image 20251219170920.png]]


## 6. 红外光谱的典型例子

^69804d

### 6.1 烷烃 Alkanes
![[Pasted image 20251219171026.png]]

### 6.2 芳烃 Aromatics
![[Pasted image 20251219171101.png]]

### 6.3 醛和酮 Aldehydes and Ketones (Carbonyl 羰基)
![[Pasted image 20251219171133.png]]
![[Pasted image 20251219171555.png]]

![[Pasted image 20251219171601.png]]
### 6.4 羧酸 Carboxylic Acids
![[Pasted image 20251219171157.png]]
- 酯
![[Pasted image 20251219171204.png]]

### 6.5 醚 Ethers
![[Pasted image 20251219171332.png]]
### 6.6 醇 Alcohols
![[Pasted image 20251219171342.png]]
### 6.7 酚 Phenols
![[Pasted image 20251219171402.png]]

![[Pasted image 20251219171414.png]]

### 6.8 Summary
![[Pasted image 20251219171437.png]]

![[Pasted image 20251219171445.png]]

![[Pasted image 20251219171451.png]]