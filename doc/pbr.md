# PBR

PBR(Physically Based Rendering), 基于物理的渲染，用更符合物理学规律的方式来模拟光线，便得渲染效率比传统冯氏光照更真实一些。

美术可以直接以物理参数为依据来编写材质。

不管光照条件如何，这些材质看上去都会是正确的，而非PBR的渲染管线有些东西会不真实。

本教程的方案基于金属质地的工作流(Metallic Workflow)，这也是大多数游戏采用的方案。

1. 基于微平面的表面模型
2. 能量守恒
3. 应用基于物理的BRDF



## 微平面理论

