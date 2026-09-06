<h1 align="center">NeoSDK</h1>

<p align="center"><strong>面向白盒重建的显式几何工具集</strong></p>

<p align="center">
  <a href="https://neoworldproject.github.io/Studio/"><img src="assets/project-page.svg" alt="项目主页与演示"></a>
  <a href="https://github.com/NeoWorldProject/NeoWorldStudio"><img src="assets/studio.svg" alt="NeoWorld Studio 项目"></a>
  <img src="assets/code-soon.svg" alt="代码：即将发布">
</p>

<p align="center"><a href="README.md">English</a> · <strong>简体中文</strong></p>

> **研究预览。** 本仓库目前提供工具集介绍。NeoSDK 代码计划从 **2026 年 9 月底**起陆续开放。

## 核心思路

NeoSDK 是面向**白盒重建**的几何构建与优化工具集，通过显式、可检查的操作构建可编辑三维几何，并根据视觉反馈持续优化，不依赖预训练的 3D 生成模型。

### 构建可编辑几何

几何构建工具为三维重建提供可编辑的初始结果。

### 根据视觉反馈优化

智能体对照渲染视图与原始观测，调用几何优化工具，逐步调整形状与结构。

### 服务于 NeoWorld Studio

[NeoWorld Studio](https://github.com/NeoWorldProject/NeoWorldStudio) 将物体初始重建、场景装配和迭代优化连接起来，NeoSDK 为这一流程提供几何操作能力。

### 构建与检查水密实体

NeoSDK 提供实体构建与适配工具，用于生成 watertight 的物理几何。该能力面向适用零件和经验证的实体结果，不代表任意视觉网格都自动具备水密性。

在 Studio 中，显式零件结构也支持配置关节运动与逐零件物理参数。**Physics-in-the-loop 优化及可交互、simulation-ready 场景**是基于这些能力继续推进的研究方向。

## 开放计划

- [x] 工具集介绍与项目链接
- [ ] NeoSDK 代码，计划从 2026 年 9 月底起陆续开放

## 相关项目

**App Store：即将发布。** NeoWorld Studio 计划推出应用，上架时间待定。

完整重建项目、[场景演示](https://neoworldproject.github.io/Studio/#demos)，以及用于场景重建的预训练视觉语言模型 **MATRIX-Preview** 的开放动态，请关注 [**NeoWorld Studio**](https://github.com/NeoWorldProject/NeoWorldStudio)。

---

<p align="center"><a href="https://neoworldproject.github.io/Studio/">项目主页</a> · <a href="https://github.com/NeoWorldProject/NeoWorldStudio">NeoWorld Studio</a> · <a href="README.md">English</a></p>
