---
Date: 2025-12-19
tags:
  - 材料学
aliases:
---
# Scanning Electron Microscope（SEM）
morphology, atomic number, chemical composition, structure or orientation.
![[27957486-f45b-4ff4-9df6-8a1169ff5435.png]]
- **聚光镜（Condenser Lens）**：初步聚焦电子束，控制束流强度（1 pA–100 nA），平衡分辨率与信噪比
- **物镜（Objective Lens）**：最关键的最终聚焦透镜，将电子束缩小至纳米级探针（约0.4-5 nm），直接决定仪器分辨率极限
- #### **扫描线圈（Scanning Coils）**
	- **作用**：精确控制电子束在样品表面的扫描轨迹。
	- 以**光栅扫描模式**（Raster Scan）逐行移动电子束
	- 扫描频率可调，扫描范围从几微米到几毫米
	- 与显示系统同步，实现"逐点采集、逐像素成像"
- **光阑（Aperture）**
	- **控制电子束电流**：通过物理阻挡，选择性地让中心区域的电子通过，从而调节到达样品的**束流强度**（1 pA–100 nA）
	- **改善信噪比**：阻挡散射电子和离轴电子，**提高图像质量**
	- **减少像差**：限制电子束的**发散角**，降低球差和色差
	- **提高分辨率**：小孔径光阑可产生**更细的电子束探针**（可达0.4 nm）

可以检测以下四个相：
![[Pasted image 20251114010531.png]]
## Secondary electron contrast
表面的角度和二次电子激发有直接关系$\delta_{SE} \propto 1/cos \theta$，角度越大，接触面积越大，二次电子越多。
1. 入射电子在表面 5–10 nm 逃逸深度内“走”过的有效路径长度随 1/cos θ 增加；θ 越大，路径越长，电离出的二次电子越多，产额 δ 几乎线性上涨，亮度直接跟着涨。

### 失效界面分析
- intergranular fracture 沿晶断裂
- Dimple fracture 韧窝断裂
- Cleavage fracture 解理断裂
- Fatigue fracture 疲劳断裂

### Morphology Observation
1. Sintered ceramics
2. Microstructure analysis
	1. Polished and Etched, deeper than optical microscopy(二次电子对角度很敏感，更适合观察表面起伏较大的样品)

## BSE Contrast
Also used in morphology observation
- 分辨率小于二次电子
- 加入背反射电子会使二次电子像更明亮一些，因为能量差异SE能量低，BSE能量高
- 对原子序数敏感，因为产生原理是和原子核相互作用
- 容易分析phase composition, morphology, size and distribution.

## Absorbing Electron Contrast

- 分辨率小于背反射电子
- 吸收电子数量与背反射电子数量递减关系

## Characteristc X-ray
见[[X-ray#^273934]]

### EDS
- 电子束照射到材料表面产生的X射线，会被Si（Li）drift  detector接受
- X-ray 能量会产生电子空穴对->电压，数个数来算能量
- 精度低，但是效率高
![[d5852275-0bb5-43a8-8eb7-79b3f388a830.png]]
### WDS
- 利用布拉格衍射，每一个theta对应一个波长，来测量每一个波长的强度
- 精度高，但是耗时长
![[Pasted image 20251024160048.png]]
