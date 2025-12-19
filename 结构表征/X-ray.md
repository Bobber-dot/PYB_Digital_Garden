---
Date: 2025-09-19
tags:
  - 材料学
aliases:
---
# Nature of X-rays
![[Pasted image 20250919145931.png]]

X-ray: Electro-magnetic wave/radiation with **wave-particle dualism** 波粒二象性

**Wave Nature**: Propagated with a certain frequency and wavelength (10 to $10^{-3}$ nm)
- Motion continuity, interference and diffraction
- Intensity: I∝A^2 

**Particle Nature**: Composed of numerous discontinued particles
- Interaction Between matter and interchange of energe.
- Intensity: 
- Energy: $E = h \mu = hc/ \lambda$
- Momentum: $p=mv=h/\lambda$

# Production of X-rays
![[Pasted image 20250919150911.png]]

1. When a **high voltage** with several tens of kV is applied between two electrodes, the high-speed electrons with ==sufficient kinetic energy==, drawn out from the cathode, collide with the anode.
2. The electrons rapidly slow down and lose kinetic energy (~99%).
3. X-rays generated (<1%).

## X-ray tubes
![[Pasted image 20250919151116.png]]

![[Pasted image 20250919151103.png]]

The shape and size of beam focus is a significant characteristic of X rays 
-  Smaller focus with higher resolution 
-  Stronger intensity with shorter exposure time

![[Pasted image 20250919151319.png]]


> [!tip] 引子
> 不同的电压会产生不同的X射线分布，引出接下来的X射线激发理论


## Continuous X-rays 连续X射线

![[Pasted image 20250919152411.png]]
### Principle:

1. e- collide with anode 
2. e- slow down and lose kinetic energy 
3. Different e- lose different energy 
4. Continuous X-rays with various wavelengths are generated

### Parameters: $λ_{SWL}$, $λ_m$

When an electrons **loses all its energy in a single collision**, the generated X-ray has the maximum energy/shortest wavelength $λ_{SWL}$

Two parameters of continuous X-rays (white X-rays): 
- the ==Shortest Wavelength Limit== $λ_{SWL}=\frac{c}{v_{max}}$ 
- the wavelength corresponding to the maximum intensity, $λm$

The total X-ray intensity is equivalent to ==the area under the curve==: 

$$
I_{cont} ∝ iZV^2
$$

Higher accelerating voltage ⟹ higher intensity and smaller $λ_{SWL}$ , $λ_m$

### Excitation voltage 激励电压—— Characteristic X-ray 特征X射线

^8d4011

1. Excitation voltage : Increasing the applied voltage, if the ==electrons has sufficient kinetic energy to eject an inner-shell electron==, the atom becomes excited with a hole in the electron shell. （如果电子厉害到打飞内层电子，会使原子激发（外层电子会激发更强的））
2. When such a hole is filled by an outer shell electron, the atom regains its stable state.
3. As the energy released in this process is a value specific to the target metal and related electron shell, it is called **Characteristic X-ray**

![[Pasted image 20250919153244.png]]

随着n值的增加，即按K、L、M、N、O… 电子层逐渐向外

特征X射线的频率有迹可循的，遵从以下公式

##### Mosley's law

$$
\sqrt{\frac{1}{\lambda}} = k \cdot (z-\sigma)
$$
- The wavelength of characteristic X-ray depends on the atomic number Z of the target material.
- Increase the applied voltage and current, the intensity of characteristic X-ray increases.

**Application**

![[Pasted image 20250923165751.png]]
X-ray energy disperdion spectronmetry (EDS)

![[Pasted image 20250923165800.png]]
X-ray wavelength dispersion spectrometry (WDS)

![[Pasted image 20250923165927.png]]

### Absorption of X-rays & Secondary characteristic X-ray(Fluorescence X-ray)

^273934

When the X-ray with intensity $I_0$ enters a sample, it would be scattered by electrons in various different directions.

The intensity I after transmitting through distance x is given by

$$
I_x = I_0 e^{-\mu x}=I_0 e^{-\mu_{m} \rho x} \quad \mu \approx k \lambda^3 Z^3
$$

- $\mu$ is called linear absorption coefficient(depend on  Wavelength of X-rays).
- $\rho$ the physical state or density of the substance.
- $\mu_m = \mu / \rho$ is the mass absorption coefficient, Z si the atomic number

**Absorption limit $\lambda_k$**

![[Pasted image 20250923171203.png]]

- $\mu_m$ is not continuous varied with $\lambda$
- Sudden reduction at Abeorption Limit $\lambda_k$
- $\lambda_k$ reveals the atomic shell structure (Z) 

这说明瞬间下降的原因是原子层和X光的相互作用。突然的吸收减弱。
接下来引出了光电吸收，代表着X光强到一定程度后就会使得吸收率上升，储存起来变成荧光。

#### Photoelectric absorption
If the incident X-ray energy is large enough to promote an K-shell electron released, it becomes photoelectron. ==And then outershell electron jump into K-shell, X-rays gernerate at this process==, called ==secondary characteristic X-ray (Fluorescence X-ray)==
The energy of the photoelectron Eej = hʋ-EB (hʋ = energy of incidence X-rays, EB = binding energy for electrons of the corresponding shell)

Such specific energy (wavelength) is called absorption edge (EB).

![[Pasted image 20250923172106.png]]

#### Application of absorption edge: Filter
To obtain a monochromatic beam（单色光）, we filter the unwanted X-ray lines by using a foil of a suitabe mtal whose absorption edge for X-rays lies between the Ka and Kb components of the spectrum

In most modern X-ray diffractometers a monochromatic beam is obtained by using a crystal monochromator.Cu Kα is the most common radiation we used.

![[Pasted image 20250923173359.png]]


看这个图可以知道，晶体可以在一定程度上吸收X-ray，但是如果X光恰好接近Ka,Kb 那吸收效率会低很多，因为Ka，Kb会撞击出电子，导致出现 Characteristic X-ray. 导致强度会有叠加，而其他频率的电子会被消耗掉。这样就形成了被过滤的X-ray图像。

![[Pasted image 20250923173822.png]]

#### Auger effect

^a945d2

![[051b1e0f-cfc0-4853-98eb-ef4ccd050ffc.png]]

The excited atom can return to its ground state by filling the hole with an electron from an outer shell and emitting another electron, this non-radiative transition process is called Auger process and the emission electron is called Auger electron.

# Scattering and Diffraction

## 1. Scattering by a single electron

![[Pasted image 20250926150052.png]]
$$
Polarization factor:\frac{1+cos^22\theta}{2}
$$
$$
I_e = I_0 \frac{K}{r^2} (\frac{1+cos^22\theta}{2})
$$
- Assuming the electron is isolated.
- Assuming the X-ray beam is non-polarized.

- K －square of electron radius $r_e$.
- r － **distance of test point** from electron.
- 2θ－ diffraction angle.

## 2. Scattering by a single stom

由于有多束光线，考虑进行光的相干性区分 

### Classification of Scattering & Atomic Scattering Factor

1. Coherent scattering
	1. Interaction between X-rays and **electrons bound by nucleus tightly**.
	2. Scattered rays **exhibit the same phase and wavelength**.
	3. Diffraction.
2. Incoherent scattering
	1. Interaction between X-rays and **electrons bound by nucleus ==untightly.==**
	2. Scattered rays exhibit ==different phase and wavelength==.
	3. Cannout ==produce any interference effect==.

![[Pasted image 20250926151841.png]]

- XX' direction 波程一样
- YY' direction 波程不同，非整数波

The scattering intendity of an atom should equal to the sum of the scattering intensity of all electrons in atom. Due to the synthesis wave intensity loss
$$
I_a<ZI_e
$$
$$
Atomic \ Scattering \ Fector \ f = \frac{Amplitude \ of \ wave \ scattered \ by \ an \ atom}{Amplitude \ \cdots \ by \ an \ electron}=\frac{A_a}{A_e}=(\frac{I_a}{I_e})^{1/2} 
$$
$$
f \ increases \ with \ decreasing \ of \ sinθ/λ
$$

### Laue conditions
![[ca729404-f05a-4eba-b2be-4dfff79bf8bb.png]]

when the wave path difference is the integer multiples of $\lambda$ , then coherent scattering is generated.

Three dimensional expression:
$$\begin{split}
a(cos\alpha - cos\alpha_0) &= h\lambda \\
b(cos\beta - cos\beta_0) &= k\lambda \\
c(cos\gamma - cos\gamma_0) &= l\lambda
\end{split}$$
(叠加态为laue condition)

### Bragg's Law
![[d1c0be06-82e0-4eb4-8fc3-5e1bdf2af2d3.png]]

- The wavelength of the beam should be in the same range as the values of the interplanar distances.

- X光和可见光反射行为的区别
	- Participated atoms
	- The reflection angle 
	- Efficiency

#### 晶面间距计算公式
各种晶格类型的晶面间距d（hkl）为Miller式

![[Pasted image 20250930161541.png]]

衍射得到的图像最终就会得到（不同的几何参数得到不同的theta-强度分布）

![[Pasted image 20250930162117.png]]

### Unit Cell Scattering 散射
#### Structure Factor
1. Assuming the Bragg’s law is satisfied.
2. Only consider the coherent scattering. 
3. Adding all the waves scattered by the individual atoms within a unit cell together
$$\begin{split}
&F=\frac{A_b}{A_e} = \sum^{m}_{j=1}f_je^{i\phi_j} \\
&F_{hkl} \ is \ defined \ as \ Structure\ Factor \\
&F = \frac{Amplitude \ of \ the \ wave \ scattered \ by \ all \ the \ atoms \ of \ a \ unit\ cell }{Amplitude\ of\ the\ wave\ scattered\ by\ one\ electron}\\
&\phi = 2 \pi (Hu+Kv+Lw)\\
&(HKL):Miller \ indices \\
&[uvw]:Fractional \ coordinates \ 分数坐标 \\
&m : 原子个数\\
\end{split}$$
![[Pasted image 20250930163225.png]]

The phase of diffraction wave depends on the diffraction planes and position of atoms:
(HKL) planes 是平面参数的miller表示


**Simple lattice points**
![[Pasted image 20250930164147.png]]
**Body centered lattice**
![[Pasted image 20250930164209.png]]
**Face centered lattice**
![[Pasted image 20250930164322.png]]
**Base centered lattice**
![[Pasted image 20250930164340.png]]

![[Pasted image 20250930164403.png]]

**Examples**
![[Pasted image 20250930170025.png]]
#### Angle Factor
- Angle factor is the function of $\theta$
- Diffraction intensity changing eith $\theta$

![[Pasted image 20250930170242.png]]

#### Mutiplicity Factor
![[Pasted image 20250930170300.png]]

![[11dc01f3-9267-4c23-8996-9a6ed442f402.png]]
#### Absorption Factor
![[Pasted image 20250930170555.png]]

#### Temperature Factor
![[Pasted image 20250930170617.png]]

#### Integral intensity of polycrystal
![[Pasted image 20250930171441.png]]

