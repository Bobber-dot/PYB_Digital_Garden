---
Date: 2025-10-17
tags:
  - 材料学
aliases:
---
# Resolution (精度，分辨率)
![[Pasted image 20251017140757.png]]
## 光学透镜的原理
光学成像定律
$$\begin{split}
\frac{1}{u} + \frac{1}{v} = \frac{1}{f} \\
\end{split}$$
![[Pasted image 20251017151241.png]]


## 放大倍数
![[Pasted image 20251017140808.png]]
聚光镜（平行光）->物镜（物象放大）->目镜（二次放大）

> 一个透镜，我们关心他的放大率和分辨率

## 分辨率定义

### Airy Spot (艾里斑)
- alternately dark and bright rings surround the central bright, caused by diffraction of point source.
- 点状光形成的衍射光斑

![[Pasted image 20251017142017.png]]


### Rayleigh Criterion（瑞利判据）
when the spot center spacing $Δr_0$ equal to the radius of Ariy spot, the intensity difference of peak and valley value is 0.19$I_0$ and that is the smallest distance that can be distinguished.

人眼可以分辨 0.19倍的光强差距，此为瑞利判据。

### 分辨率定义
Resolution $\Delta r_0$： the smallest distance that can be resolved.
$$
\Delta r_0 = \frac{0.61 \lambda}{nsin\alpha} \approx \frac{1}{2} \lambda
$$
![[Pasted image 20251017142552.png]]
孔径角又称"镜口角"，是物镜光轴上的物体点与物镜前透镜的有效直径所形成的角度。

The resolution is proportion to $\lambda$. 

**Half-wavelength** ： the theoretical resolution of visible light lens - about 200 nm (the wavelength of visible light is 390-760 nm)

The focusable light wave with **short wavelength** is needed.

### 光学显微镜的局限性
![[Pasted image 20251017143646.png]]

对X光和γ光来说，所有材料几乎都为n=1，无法被聚焦。

# Electron Waves and Electron Lens 电子波和电子透镜
## Electron Waves 电子波
![[Pasted image 20251017143915.png]]
- **Wave nature:** reflects in the motion smoothness, interference and diffraction.
- **Particel nature:** reflects in the interaction of matter and interchange of energy.

$$\begin{split}
\lambda &= \frac{h}{mv} \qquad h:Plank’s \  constant \\
\lambda &= \frac{h}{\sqrt{2emU}} \qquad Accelerating \ voltage \ U \\
\lambda &= \frac{h}{\sqrt{2em_0U(1+\frac{eU}{2m_0c^2})}} \qquad Relativistic \ Corrections \\
\end{split}$$

![[Pasted image 20251017145152.png]]

## Electron lens 电子透镜
- Electron beam can be focused in rotational symmetrical electrostatic field or magnetic field.
- The focusing device of electron beam is **electron lens.**

![[Pasted image 20251017145249.png]]

- Electrostatic lens:
	- Focused electron beam with a cluster of rotational symmetric equipotential curves. It can be divided into two polepieces or three polepieces. 双极靴，三极靴形式。
	- 主要用于电子柱的发射。
	- Refraction of electron beam in equipotential plane
	  （电子在等电势平面上的折射）![[Pasted image 20251017145701.png]]
	- 三级靴![[Pasted image 20251017150434.png]] 
- Magnetic lens: 后者主要用于汇聚、成像和放大。
	- 由于洛伦兹力存在，电子呈现螺旋线前进。
	  The electron spirals through the lens field: a helical trajectory![[Pasted image 20251017150503.png]]
	- Magnetic lens is not sensitive to **accelerating voltage**, showing superiority over electrostatic lens, always used as electron focused lens. （磁透镜的汇聚效果不太被加速电子的速度影响，因此比静电透镜要好）
	- 磁透镜的成像原理
	- $$\begin{split} \frac{1}{f} &= \frac{1}{u} + \frac{1}{v} \\ M&=\frac{f}{u-f} \\ f &= \frac{16}{3 \pi^2}\frac{mRU}{e(NI)^2} \end{split}$$

# Lens Aberrations 像散
**Def** 实际成像和理想光学成像之间的区别
- **Aberrations**
	- **Seidal Aberration**
		- **Spherical Aberration 球差** $\propto a^3$
			- The different refractive power of electron magnetic lens center and margin
			- 电子离轴越远，回到轴的趋势越强，因此会出现多个像。在不同的地方取用像，总是会有模糊的区域。球差是最重要的，因为这不利于TEM images的细节![[Pasted image 20251017152502.png]]
				- 引入球差因子 $C_s$: a constant (a length) for a particular lens called the spherical aberration coefficient.
				- 引入最小模糊圆半径（一个像最小的公共模糊区域）$R_s$
				- 有引入球差补偿（用磁场补偿）后的瑞利判据：$\Delta r_s=\frac{R_s}{M}$ 。M equals to the magnification
					- 如果两点距离小于两倍的$\Delta r_s$，则不可分辨。
				- 判据的另一个定义：
					- $\Delta r_s = \frac{1}{4}C_s \alpha^3$
						- Cs – spherical aberration coefficient, 1-3mm 
						- a – maximum collection angle
		- **Distortion**
			- Spherical aberration and magnetic rotation
		- **Astigmatism** **散光**
			- Asymmetry of magnetic field around lens. 不可能做成完美的圆柱形对称磁场
			- ![[Pasted image 20251017153858.png]]
			  $\Delta r_A=\frac{R_A}{M}=\Delta f_A \alpha$ 
			- ΔfA - maximum difference in focus induced by the astigmatism
			- 解决之道：Introduce a compensating field to balance the inhomogeneities causing the astigmatism
	- **Chromatic Aberration** **色差**
		- Chromatic aberration: the non-unity of incident beam energy
		- Non monochromatic of electron source (energy spread).电子不是单色的（能量不同）
		  Lens bends electrons of lower energy strongly and thus electrons from a point are blurred to form a disk. （电子慢的偏转强，因此形成一个disk）
		  ![[Pasted image 20251021160845.png]]![[Pasted image 20251021162000.png]]
			- Chromatic aberration gets worse for **thicker specimens** and is better for **thinner ones**
			- **Stabilize** the accelerating **voltage** and lens **current**
## 像散得到的分辨率
Diffraction effect and aberrations decide the resolution of electromagnetic lens.

- Diffraction effect
$$\begin{split}
Diffraction\ effect\ &\Delta r_0  \propto 1/ \alpha \\
\Delta r_0 = \frac{0.61 \lambda }{nsin \alpha} \\
\Delta r_0 = \frac{0.61 \lambda }{\alpha}
\end{split}$$

- Aberration $\Delta r_0 \propto \alpha$
	- ![[Pasted image 20251021161646.png]]
## 其他影响
- **Accelerating Voltage**
	- Intermediate voltage electron microscopes: 200/300 kV
	- Very High resolution 1MV
- **Spherical aberration and chromatic aberration** Correction方法
	- Thin specimen -> C_s correction
	- Thicker specimen -> C_c correction

## 景深Depth of field 焦深 Depth of Focus
### The Depth of Field, $D_{ob}$
refers to **the object plane**, is the distance along the axis on both sides of the object plane within which we can move the object without detectable loss of focus in the image
是指在一幅照片中，能够保持清晰的前景和背景之间的距离范围。简单来说，景深就是照片中清晰部分的深度。景深可以分为**浅景深**和**深景深**：
- **浅景深**：只有焦点部分清晰，背景模糊，常用于突出主体（如人像摄影）。
- **深景深**：前景和背景都清晰，适合拍摄风景或大范围的场景记录。

### The depth of Focus, $D_{im}$
refers to the image plane, is the distance along the axis on both sides of the image plane within which the image appears focused
指的是在保持影像清晰的前提下，**焦点（焦平面）沿着镜头光轴所允许移动的距离。** 焦深与镜头的光圈、焦距和物距有关，**光圈越小，焦深越大；物距越近，焦深越大**。焦深主要用于描述静态物体在不同传感器位置（包括倾斜）下的聚焦能力。

![[Pasted image 20251021163224.png]]

显微镜
![[Pasted image 20251021163348.png]]





# Scanning Probe Microscope（SPM）
- 在样品和针之间加上一个电压
	- 保持探针和样品表面距离不变，扫描改变电压
	- 保持电压不变，上下移动探针来检测高度变化

# Scanning Tunneling Microscope（STM）
- 利用量子隧穿效应，检测隧穿电子电流。
	- 利用势垒的宽度和电子隧穿效应的关系来检测形貌的变化。
	- $I \propto e^{-2kd}$
	- 设定电流恒定-> 很安全，不会撞上
	- 设定距离（高度）恒定 

- 可以做到原子级别的分辨率

# Atomic Force Microscope
- 检测原子和探针之间的相互作用力
	- 恒力模式
	- 恒高度模式

