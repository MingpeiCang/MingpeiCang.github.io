---
title: Geometric characteristics analysis and design of bone-mimicking lattices
draft: false
date: 2024-06-01
tags:
  - 几何处理
  - 仿生点阵设计
  - 三维数据可视化
  - participating-project
---

本项目通过“计算几何分析 + 隐式建模”设计高性能骨仿生支架。我的主要工作是定量提取天然骨组织的关键拓扑特征，并在点阵结构中进行可控复现。

### 高级几何分析
- 处理骨组织高分辨率 µCT 数据，构建高保真三角网格。
- 基于 C++ 库 libigl 的多尺度拟合方法，计算顶点主曲率（κ1, κ2）与高斯曲率（K），量化局部形貌特征。
- 通过双变量 Kernel Density Estimation（KDE）构建 Interface Shape Distribution（ISD），形成仿生设计的定量基准；结果显示双曲面（鞍形）特征占优，是促成成骨行为的重要几何因素。

### 隐式建模与点阵设计
- 使用 MATLAB 程序化生成基于 Triply Periodic Minimal Surfaces（TPMS）的多孔结构（如 Gyroid、Diamond）。
- 通过调控隐式方程构建梯度与混合梯度（hybrid-G）点阵，模拟天然骨组织的空间异质性。
- 通过精确偏置隐式曲面，使模型平均孔隙率匹配目标值（70%）。

### 计算验证与可视化
在完整建模-仿真链路中完成几何质量评估、力学趋势验证与可视化表达，为后续功能化骨仿生材料设计提供了可复用工作流。

相关论文：
- 10.1016/j.mser.2024.100876

<!--more-->
