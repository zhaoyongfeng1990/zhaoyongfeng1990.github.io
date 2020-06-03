---
layout: page
title: 代码
lang: cn
lang-ref: codes
permalink: /cn/codes/
---

这里是我在过去的工作中曾经用到的代码。

-

[谱方法求解二维圆内非线性反应-扩散方程的程序](https://github.com/zhaoyongfeng1990/spectral_solver)

求解形如

$$\partial_t f_i=\sum_{k=1}^N\nabla\cdot(h_{ik}\nabla f_k)+g_i(f_1,f_2,\cdots,f_N)$$

的非线性反应-扩散方程。不过边界的发散问题尚未解决。

-

[二维格点上的无相互作用run-and-tumble粒子，使用连续时间的Gillespie算法](https://github.com/zhaoyongfeng1990/2d_on_lattice)

另外还有[高效地加入格点上的逻辑斯蒂群体动力学的版本](https://github.com/zhaoyongfeng1990/2d_on_lattice_with_growth)，和[使用CUDA的版本](https://github.com/zhaoyongfeng1990/2d_on_lattice_CUDA)。

-

[差分动态显微技术](https://github.com/zhaoyongfeng1990/DDM)

从对粒子拍摄的高速影片数据中提取粒子的运动信息，基于对模型的数值拉普拉斯逆变换。参见我的[博士毕业论文]({{site.url}}/assets/Thesis_YongfengZhao.pdf)。

-

[有相互作用的活力粒子的分子动力学模拟](https://github.com/zhaoyongfeng1990/simMIPS)

-

[无相互作用的活力布朗粒子模拟](https://github.com/zhaoyongfeng1990/non_interacting_ABPs)