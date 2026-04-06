---
permalink: /about/
title: "中文介绍"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

中南大学计算机科学与技术硕士，师从[李敏](http://bioinformatics.csu.edu.cn/limin/)教授，曾在深圳[情感智能与普适计算研究中心](https://ai.smbu.edu.cn/yjzz/qgznypsjsyjzx/zxjj.htm)实习。过往研究主要集中在多模态数据驱动的抑郁情绪识别和多模态动作理解，目前在探索面向 VR 场景的具身与交互智能体，关注多模态感知、工具调用与仿真交互。

## 专业技能经历

* **机器学习/深度学习**： PyTorch、OpenCV、Transformers
* **全栈Web**：Vue3、Vant、Gradio、Spring Boot、MyBatis Plus、MySQL
* **3D图形**：Unity、UE、Blender、OpenGL
* **其他**：Linux、Docker、Qt、Android(Java)、ESP32

## 科研经历

### 1. MoChat: 基于关节分组的时空定位动作理解大语言模型（2023.08-2025.08）

已发表于 [IEEE Journal of Biomedical and Health Informatics](https://ieeexplore.ieee.org/document/11237042)（[arXiv PDF](https://arxiv.org/abs/2410.11404)，[GitHub](https://github.com/CSUBioGroup/MoChat)）

* 负责骨架格式（SMPL、Human3.6M、COCO）和编码器选型；
* 负责 NTU RGBD 数据集视频抽帧，使用 CogVLM 生成对应注释；
* 改进骨架编码器，引入时间回归模块，实现模型对骨架运动序列的理解以及对动作发生的时间和身体部位进行定位和描述功能；
* 使用 8 x A800 进行训练，大多数测试指标达到同期领先水平；

### 2. [基于 EEG 脑电与语音融合的抑郁症识别](/files/基于EEG脑电与语音融合的抑郁症识别方法.pdf)（2021.09-2022.06）
* 使用 MATLAB 和 OpenSMILE 预处理兰州大学 MODMA 数据集；
* 训练多种机器学习分类器，包括 KNN、 SVM、 MLP、高斯过程、高斯朴素贝叶斯、随机森林等；
* 使用动态分类器选择算法进行抑郁症识别，取得最优97.6%的准确率；

## 工程实践

* 动作分析平台（2023.08-2024.08）：使用 Plotly 实现骨架和点云序列的可视化及动作极值分析，使用 Gradio 实现多模态大模型对话界面；
* Android健康助手（2023.05）：Unity + GLM4V，一键拍照生成健康建议；
* 多模态数据采集管理平台（2021.09-2022.06）：使用 Vant、 Vue3、 Spring boot、 Mybatis-Plus、 MySQL 开发了用于多模态数据采集管理的平台；

## 教育经历

<table>
  <tbody>
    <tr>
      <td>中南大学</td>
      <td>2022.09~2025.06</td>
      <td>计算机科学与技术-学术型硕士</td>
    </tr>
    <tr>
      <td>中南大学</td>
      <td>2019.09~2022.06</td>
      <td>计算机科学与技术-本科</td>
    </tr>
    <tr>
      <td>中南大学</td>
      <td>2018.09~2019.07</td>
      <td>地球物理学-本科</td>
    </tr>
  </tbody>
</table>
