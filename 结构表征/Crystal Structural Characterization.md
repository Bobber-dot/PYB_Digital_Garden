---
Date: 2025-09-19
tags:
  - 材料学
aliases:
---
# 晶系Crystal system & Lattice system
![[19155775-c5d9-4cbf-a2ee-5f6c383a35b1.png]]
## Crystal system——七大晶系分类
依据晶胞参数与对称性的不同，分属7大晶系
1. **Crystal system（晶系）**  
    把 14 种格子按==“最高旋转轴”==再打包成 7 盒：三斜、单斜、正交、四方、三方、六方、立方。  
    → 仍然只看点阵对称，不管原子。
    根据**对称性、几何角度和参数**共同划分
	1. Cubic 立方 
	2. Tetragonal 正方晶系  
	3. Orthohombic 斜方晶系 
	4. Trigonal 三方晶系 
		1. Rhombohedral 菱面体 
	5. Hexagonal 六方晶系 
	6. Monoclinic 单斜晶系 
	7. Triclinic 三斜晶系 
2. **Crystal family（晶族）**  
    国际晶体学表把 7 个晶系进一步合并成 6 个“family”：
    
    - 三斜
        
    - 单斜
        
    - 正交
        
    - 四方
        
    - 六方 **（把三方并进来）**
        
    - 立方  
        所以“三方”在 system 层独立，在 family 层被六方“收养”。

## Dot Matrix——四大点阵分类
简单点阵 Simple
体心点阵 Body-centered
面心点阵 Face-centered
底心点阵 Base-centered

## Lattice system——基于纯数学的布拉维格子
“14 晶格”就是晶体学里常说的 **14 种布拉维格子（Bravais lattice）**。它不是实验测出来的，而是 1855 年法国晶体学家奥古斯特·布拉维（Auguste Bravais）用**群论+几何**“算”出来的：

为什么有十四种刚刚好？
_There are only seven different groups of dots for the lattice of crystals. The seven major crystal systems are: monoclinic crystal system, triclinic crystal system, triangular crystal system, tetragonal crystal system, orthorhombic crystal system, hexagonal crystal system, and cubic crystal system, these fourteen Bravais unit cells are divided according to the symmetry of the crystal. (2) That is, the unit cell as a lattice unit must reflect the symmetry of the entire crystal lattice, and other division methods other than these fourteen can be recombined and divided into one of the fourteen kinds, and the crystal lattice remains unchanged. So there are only fourteen crystal lattices. (4)_

_For example, the based-centered tetragonal can be redivided into a simple tetragonal; The faced-centered tetragonal can be redivided into the body-centered tetragonal._
就是说，十四晶格是数学对称性已经决定的类型。其他类型不论怎么分类，都是由这十四种晶格重新组合形成的，举个例子展示不同的分类是怎么等同的。

![[Pasted image 20250926143517.png]]

| 晶系  | 格子符号       | 阵点/晶胞      |
| --- | ---------- | ---------- |
| 三斜  | P          | 1          |
| 单斜  | P, C       | 1, 2       |
| 正交  | P, C, I, F | 1, 2, 2, 4 |
| 四方  | P, I       | 1, 2       |
| 三方  | R（菱面体）     | 1          |
| 六方  | P          | 1          |
| 立方  | P, I, F    | 1, 2, 4    |


![[c9ec4fcb-040b-4164-bf63-5c18361e440b.png]]

![[Pasted image 20250926144251.png]]
Trigonal R = Rhombohadral 菱形
菱形本质上还是六方或者三角晶系
# Crystallographic Directions/Planes
重点就是Miller指数——hkl
- 晶带[],<>
- 晶面(),{}
