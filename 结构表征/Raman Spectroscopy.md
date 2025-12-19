---
Date: 2025-11-24
tags:
  - 材料学
aliases:
---
# 1. 拉曼散射 Raman Scattering 
## 1.1 瑞利散射以及拉曼散射 Rayleigh and Raman Scattering 分别是什么？
- 只有大小在1-1.5λ能够散射 EM radiation（分子）
- Rayleigh Scattering 瑞利散射
	- occurs when incident EM radiation induces an oscillating dipole in a molecule, which is re-radiated at the same frequency
	- 简单来说就是分子会反射一个完全相同频率的光。
- Raman Scattering
	- occurs when monochromatic light is scattered by a molecule, and the scatteredlight has been weakly modulated by the characteristic frequencies of molecule
	- 简单来说就是可以产生由单色光产生的，散射出来的，被被照射分子的固有频率影响后的光。
## 1.2 拉曼光谱测量什么？
- 拉曼光谱测量入射辐射**Incident Radiation**和散射辐射**Scattered Radiation**的差异
# 2. 拉曼效应以及光谱仪 Raman Effect and Spectroscopy
## 2.1 什么是拉曼效应？（拉曼散射的原理）
入射光将分子激发到了“虚态”（Virtual States），这种状态是在散射过程中短时间存在的。虚态指的是扭曲态或者极化态

> 拉曼效应 **Raman Effect**：光子射入分子中电子时发生非弹性散射
> 光子和分子交换能量的过程
> 虚态 **Virtual States**：散射中短暂存在的中间过渡态，是分子被瞬时极化的体现，入射的光电场诱导分子产生了振荡偶极矩。这个极化过程恰恰是链接瑞利散射（原路返回）和拉曼散射（非弹性）两种散射通道。
![[Pasted image 20251124141818.png]]
  >这张图展示了自发的拉曼效应 
  >- 斯托克斯线：当发生非弹性散射时，光子会将部分能量传递给分子（斯托克斯过程）。随后可以通过实验检测到能量较低的散射光子
  >- 反斯托克斯线：光子也可以从分子中获得能量（反斯托克斯过程）
  >- 拉曼选择定律主要依据分子的**可极化率**

## 2.2 拉曼效应的产生源头：可变的极化率
### 2.2.1 极化率和偶极矩
- # **Polarizability 极化率** 
- **Dipole（偶极子）**：偶极子是一个向量，它有大小和方向。偶极矩是一个数学计算，取决于化合物中电荷的不均匀分布程度。换句话说，化合物的偶极矩越高，该化合物就越极性。
- **Polarizability（极化率）**：
	- 极化率是一个描述分子在外部电场作用下*形成偶极子的倾向*的度量。极化率表示电子（因此电荷）在施加电场时重新排列的程度。当一个可极化的分子体验到任何类型的静电作用时，都会产生诱导偶极矩。
	- 或者这么理解：the “deformability” of a bond or a molecule in response **to an applied electric field**. Closely related to the concept of **“hardness ”** in acid/base chemistry. 分子响应电场产生的化学键的容易变形的程度，和酸碱的硬度很相似。
		- 体积小，正电荷数高，可极化性低 的中心原子称作硬酸; 体积大，正电荷数低，可极化性高 心原子称作软酸。
		- 将电负性高，极化性低难被氧化的配位原子 的中 称为硬碱，反之为软碱。硬酸和硬碱以库仑力 作为主 要的作用力；
		- 软酸和软碱以共价键为主要相互作用力。
	- 电场强度提升，可极化率下降
	- $\sigma$键和π健，单键和多键，前者更加稳定，后者范围更广，更不稳定，极化率高。
- **Polarize**（极化）
	- 极化就是材料响应外界电场，分子构型取向形状改变来构建内电场![[Pasted image 20251218112104.png]]
- 固有偶极矩 **Permanent Dipole** 和诱导偶极矩 **Induced Dipole**
- ![[Pasted image 20251124145109.png]]
### 2.2.2红外和拉曼光谱的本质

| 光谱类型     | 活性判据         | 物理本质               | 典型例子     |
| :------- | :----------- | :----------------- | :------- |
| **红外光谱** | (∂μ/∂Q)₀ ≠ 0 | 振动必须引起**偶极矩(μ)变化** | H₂O伸缩振动  |
| **拉曼光谱** | (∂α/∂Q)₀ ≠ 0 | 振动必须引起**极化率(α)变化** | N₂、O₂的振动 |
 - **Q**指的是简正坐标，简正坐标（**normal coordinate**），代表特定的分子振动模式的核位移（给定一个震动模式Qk，其值是随时间变化的。Qk​(t)=Qk0​cos(ωk​t+ϕ)）
 - ==活性判据的内涵==：振动过程中，振动几何特征Q能不能改变$\mu$？如果能改变意味着，分子在震动中能够发射电磁波，自然也能吸收电磁波。振动几何特征能不能改变$\alpha$？如果能意味着在电场中，产生的诱导极化偶极矩会随着Q变化，从而在也能吸收发射电磁波。
 

> [!NOTE] 总结
> **红外和拉曼光谱的吸收本质都是偶极矩的变化:** 
> 								*因为只有偶极矩才能发生电磁场嘛*
> - 红外产生自分子固有偶极矩（permanent dipole）的变化
> - 拉曼是诱导偶极矩（induced dipole）的变化。当光(电场)照射在分子上，促使分子的偶极矩拉伸或压缩，吸收能量(吸收光)。
> > [!tip] 自己想的发生前提
> > 事实上，分子对电场的响应和分子自己的惯性是相互制约的，我认为拉曼光谱发生的前提是分子内电子分布和分子构型对电场的响应速度是远远快于分子本身的振动的引起的电荷分布改变的惯性的
> > - 就相当于一个人能在旋转的情况下保持平衡跳一支舞

这里简单展示一下，从计算角度分析，哪些是哪些的因子
![[Pasted image 20251124143028.png]]
展示可极化性（polarizability）的变化，产生的能级变化

### 2.2.3 拉曼位移——拉曼效应的效果
> [!NOTE] 材料与光的相互作用
> ![[Pasted image 20251124143848.png]]
其中就有：前后波长不变的，前后波长改变的。波长改变的自然就是拉曼效应的结果。而拉曼位移，是拉曼效应的特性，产生的效果。

- ## 拉曼位移 **Raman Shift**
- **非弹性光散射机理**
- 拉曼位移可以是让波长更长、更短
	- 更长-Loses Energy- Predominant Raman Shift 
	- 更短-Gains Energy- Subordinate Raman Shift 
	- 下面这个b图啥意思？hΩ代表着势能（我这么认为的），被储存起来作为振动能，或者被放出来用，于是产生了能量的位移（Raman Shift）。c图就是展示这个位移在拉曼光谱图中看起来是什么样子。![[Pasted image 20251124143923.png]]
- 斯托克斯线的光强度可以用这个式子表示![[Pasted image 20251124144427.png]]
  分布规律符合麦克斯韦玻尔兹曼规律（也就是满足势能能量概率分布）
  
- **Independent of Laser Excitation**：而拉曼位移有个特性，那就是无所谓激光的波长。在一定范围内，入射激光的波长是和拉曼位移无关的。因为拉曼位移量（hΩ）的本质是只和物质本身的振动能级相关。

### 2.2.4 拉曼活性——啥时候拉曼效应出现？什么时候最强？
- ## **Raman Active 拉曼活性**
- ### Symmetric 对称性
- 这个很经验性，对称的振动会让电荷中心不变、但是会让构型改变->极化率变化。不对称的振动会让电荷中心改变，直接可以与电磁波相互作用了。![[Pasted image 20251124144938.png]]
	- 就比如这个二氧化碳，事实上非对称不一定意味着没有拉曼活性，只是活性很弱。![[Pasted image 20251218192845.png]]

### 2.2.5 拉曼光谱仪实操
#### 2.2.5.1 如何对光谱谱线强度放大？（拉曼光谱强度本来就低）
- 拉曼光谱的共振增强![[Pasted image 20251124145835.png]] ^4905a4
#### 2.2.5.2 拉曼光谱还能检测到：荧光
怎么产生的？？这激光把电子直接打出来了，然后外层电子弛豫产生荧光。
- ## **Fluorescence**
- 荧光以背底形式出现。因此如果要更好地观察拉曼光谱，得进行荧光漂白
- ![[Pasted image 20251124150324.png]]

拉曼光谱能够记录的光子行为：
![[Pasted image 20251124150113.png]]
几个行为的分布区间![[Pasted image 20251218200550.png]]
#### 2.2.5.3 Summary
1. 拉曼光谱是一种类似于红外的振动光谱——适合进行指纹识别、探测分子对称性。
	常规能量/频率范围：200 - 4000 cm–1。
2. 基于散射，而不是透射/反射，这意味着无需复杂的样品制备……气体、液体或固体均可。
	几乎总是使用斯托克斯线，因为信号/强度较强。
	选择规则决定了探测到的分子振动类型。
3. 你需要选择激发能量（激光谱线）：
	785 nm：荧光较不易发生；拉曼信号较低。
	514 nm：荧光更可能；共振更可能；信号更高。

# 3. 仪器配置 Fundamentals and Instrumentation
## 3.1 退偏振比 The Raman Depolarization Ratio ——拉曼光能获得的其他信息
表征分子对称性振动模式的高低
在多数吸收光谱中，基本只有两个基本参数，频率和强度。但是由于拉曼光谱的特殊性，光的偏振也会影响。 激光是线偏振光，各向异性的有机分子不同方向极化不同。即使完全自由取向的分子所散射出来的光也可能是偏振的。因此一般在拉曼光谱中用退偏振比表征分子对称性振动模式的高低。

## 3.2 拉曼散射系统 Raman Scattering System——就是给你看看配置的
![[Pasted image 20251130181050.png]]
- Sources: **Lasers** are generally the **only source** strong enough to scatter lots of light and lead to detectable Raman scattering.
- Lasers: He:Cd (441.6 nm), Ar ion (488.0 nm, 514.5 nm), He:Ne (632.8 nm), Diode (785 or 830 nm), Nd:YAG (1064 nm);
一般都是可见、近红外光（限制一波荧光）了，紫外光都是特殊应用的
![[Pasted image 20251130182404.png]]


## 3.3 激光和非线性光学 Lasers and Non-linear Optics——高强度激光会导致光与物质相互作用改变
![[Pasted image 20251130182427.png]]
## 3.4 傅里叶-拉曼 Interferometers for FT-IR and FT-Raman—— 就是简单的和FTIR类似的机器罢了
- Michelson interferometer
![[Pasted image 20251130181520.png]]


> [!NOTE] 还记得双峰干涉不？
> $$\Delta x=l/d*\lambda$$
> ![[Pasted image 20251130182052.png]]
> $$双缝干涉图像$$
> ![[Pasted image 20251130182127.png]]
> 迈克逊干涉仪图像，可以分光，测量振幅来得到光谱强度图


# 4. 如何有效利用和解读拉曼光谱？ Raman Spectra and Interpretations 
## 4.1 IR和Raman有何优劣？
- 拉曼比红外强的
	- 可以杜绝很多干扰（溶剂、细胞、制样方法）
	- 选择性更佳，峰更窄
	- 去偏振性可以研究了
	- 能探测IR-inactive modes
- 红外比拉曼强的
	- 拉曼产生的强光造成的荧光和分解非常之烦人（suffer）
	- 拉曼峰很弱，瑞利峰也要展示
	- 拉曼光谱仪更贵
	- IR光谱带宽更宽（um），拉曼很窄nm (20-50 nm)
- 总结：他俩互补的。（**Complementary**）

## 4.2 Raman有何应用上的问题、偏好？
- 拉曼可以用于水相样品的研究
	- IR被水振动模影响的很模糊，但是这个效应对于拉曼光谱却很小
	- 但是水能吸收拉曼光，降低灵敏度
- 拉曼的难题：
	- 慎重选择激光
	- 很容易被荧光影响
	- 高温的样品（高于250度），黑体辐射干扰非常吓人（同样对于IR）
	- 拉曼激光会加热黑色的样品，产生分解、黑体辐射

> 牛逼的应用
> 1. 生物学
> 2. 无机物
> 3. 其他的
> 4. 看看得了![[Pasted image 20251218204307.png]]

## 4.3 拉曼光谱的强度公式
拉曼光的强度有这个公式：
$$
I=Kl\alpha^2\omega^4
$$
- K consists of constants such as the speed of light,
- ι is the laser power,
- ω the frequency of the incident radiation
- α the polarizability of the electrons in the molecule.
Thus, two of the parameters which are variable are under the control of the spectroscopist, who can set the laser power and the frequency of the incident light.

## 4.4 Raman和IR的图谱比较
![[Pasted image 20251218204807.png]]
可见大多数的都可以显示，有一些是互补的。
- 活性比较
![[Pasted image 20251218232216.png]]
## 4.5 实用的波长对应官能团（这玩意很重要）
- 你就记吧
![[Pasted image 20251218204908.png]]
![[Pasted image 20251218204915.png]]
![[Pasted image 20251218205000.png]]


# 5. 高级拉曼光谱仪器和应用 Advanced Raman and Applications
## 5.1 现代的拉曼光谱仪
![[Pasted image 20251218205442.png]]
- **Confocal Raman Microscopy Instrumentation** 共聚焦拉曼显微镜
	- 把共聚焦显微镜和拉曼光谱仪结合着用——扫描呗![[Pasted image 20251218205726.png]]
- **UV Raman Spectroscopy** 紫外拉曼仪
	- 荧光是个问题，但是他拉曼相应确实强
	- **利用深紫外激光激发，让拉曼散射和荧光发射落在不同的波长区域，从而从源头避免荧光干扰。**
- **Surface Enhanced Raman Spectroscopy (SERS)** 表面增强拉曼
	- 利用了这个机制![[Pasted image 20251218211018.png]]来超大幅度地增强拉曼信号，这个就是[[Raman Spectroscopy#^4905a4|点这里看共振原理]]
- **Coherent Anti-Stokes Raman Spectroscopy (CARS)** 反斯托克斯光谱
	- 是一种**三阶非线性光学过程**，它显著提升了拉曼信号强度并具备方向性发射，是超快光谱和显微成像的强大工具。
	- 需要三束激光：泵浦光（Pump），斯托克斯光，探测光（Probe）
	- 射入泵浦光（Pump），斯托克斯光，泵浦光纯激发，斯托克斯光利用受激拉曼散射（**就是利用1->2**）将这些分子的振动相干关联起来，再用探测光提取信息，一下子提取一群。
	- ωp​−ωs​=ωv![[Pasted image 20251218211623.png]]
	- ![[Pasted image 20251218211724.png]]
	- ![[Pasted image 20251218211905.png]]
- **Raman Optical Activity (ROA)**
	- 用来研究手性分子的，利用circularly polarized radiation分散圆偏振
	- ROA 有两种类型，散射圆偏振 (SCP) 和入射圆偏振 (ICP)
	- 同时使用直角和背散射配置 
	- 主要应用于手性分析和分子构象（包括生物分子）


> [!NOTE] 激光如何产生？
>  **激光产生的三大核心要素**
>  1. 受激辐射**（Stimulated Emission）**
>- 这是原子的一个特殊行为，当一个高能原子被光子激发时，这个原子会发射与这个光子一模一样的光子，从而把这两个光子“对齐”“克隆”
>	- 高能级原子 + 光子 → 低能级原子 + 2个光子
> - 新光子与**入射光子完全克隆**（同方向、同相位、同频率）
> - **概率** ∝ 入射光子数（光越强，越容易发生）
>  2. **粒子数反转（Population Inversion）**
> 打破平衡态（低能级原子远多于高能级），让**高能级原子占多数**。
>  3. **光学谐振腔（Optical Cavity）**
> 两面镜子之间来回反射，实现**正反馈**

#### 5.1 Summary 三种不同的叼应用
![[Pasted image 20251219174829.png]]
## 5.2 拉曼和IR比较实操
![[Pasted image 20251218205552.png]]
- 等着6. 章节看看，或者看看[[Infrared Spectroscopy(IR)#^69804d|点这里]]
# 6. 拉曼光谱读图
## 6.1 拉曼光谱的特征——分析方法
- 振动频率
	- 是化学键的特征，是振动模的特征
- 振动频率的位移
	- 对环境很敏感
- 相对强度
	- 可以得知键的取向，也可以得知一个物质的浓度

![[Pasted image 20251219172301.png]]

![[Pasted image 20251219172407.png]]

## 6.2 拉曼光谱能得到的特色信息
- 非极性键的。S-S, C=C, N=N, C≡C all have strong Raman peaks, with the intensity **S-S (single) < N=N (double) < C≡C (triple)**
- The peaks for stretching of **C≡N, C=S, and S-H** are strong, but weak in FTIR.（电负性对比较弱的，IR弱，在Raman就强一些）
- **Symmetrical vibration** of cyclic structures has strong Raman scattering.（对称的环结构有很强的拉曼活性）
- Stretching of **C-C** is strong band in Raman spectra.
- **Alcohol** (-OH) has similar Raman peaks with **alkanes**, because
	- I. C-O has a similar **force constant with C-C** 
	- II. the **mass** of hydroxyl group and methyl group is **almost the same** 
	- III. compare to C-H and N-H bands, **O-H is weak in Raman spectra**

## 6.3 拉曼光谱的应用
### 6.3.1 无机物和矿石
- 拉曼用于这个应用是非常好的，可以准确识别和表征元素原子和分子
- 拉曼光谱是唯一一种可以通过光谱中峰的形状和位置来明确识别和表征元素碳的分析技术。

**![[Pasted image 20251219173232.png]]**
### 6.3.2 无机物的多晶型
![[Pasted image 20251219173406.png]]

### 6.3.3 检测互变异构 Tautomerism
![[Pasted image 20251219173458.png]]

### 6.3.4 高分子和乳液
![[Pasted image 20251219173608.png]]
简单来讲就是用一种方法让高分子的表征更加容易了，用Folding Thin Films。然后强调高强度激光让样品分解改变、Raman光谱很牛逼可检测PP和PE的差距

### 6.3.5 氢键在燃料中的影响
![[Pasted image 20251219174015.png]]
简单来讲，就是氢键太多会影响IR结果，那我们用Raman就OK了，杂环、苯环裤裤表征。

### 6.3.6 CNMs 纤维素纳米材料
![[Pasted image 20251219174410.png]]
### 6.3.7 石墨烯和石墨的无序排列
![[Pasted image 20251219174503.png]]
![[Pasted image 20251219174514.png]]
用两种不同的振动模式的占比来说明石墨烯的排列混乱度