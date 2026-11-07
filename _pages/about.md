---
layout: about
title: 关于
permalink: /
subtitle: 资深算法工程师 · 大模型端侧能效 / 模型压缩与量化 / 芯片软硬件协同

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>📍 上海市杨浦区</p>
    <p>✉️ <a href="mailto:veyronmath@gmail.com">veyronmath@gmail.com</a></p>
    <p>🎓 南京大学 (硕士) · 矿大北京 (本科)</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

## 个人简介

你好！我是**李龙宇 (Longyu Li)**。

拥有 **6 年**模型压缩、高效推理与端侧能效研发经验，深耕 **大模型动态稀疏、端侧超低比特量化、知识蒸馏及 Agent 调优流水线**。曾先后任职于 **小米自研芯片部（玄戒）**、**华为诺亚方舟实验室** 与 **海思半导体**，主导多项大模型与视觉模型的小型化及千万级终端落地。

我具备从 **Megatron / ModelLink** 分布式训练调优到 **vDSP / NPU** 芯片底层部署的全栈能效优化能力，曾获华为“研发工程能力提升奖”。

---

## 核心技术方向

- **端侧大模型能效优化 & 动态稀疏**：深入 Transformer 推理中的访存带宽瓶颈（Memory-bound），研发基于激活稀疏的动态权重调整方案与定制算子优化，结合 PEFT 与分布式框架实现高效训练与推理。
- **超低比特量化与精度恢复 (PTQ / QAT)**：主导 INT8/INT16 混合精度搜索与自适应 Clipping/误差补偿算法，构建从模型分析、模拟量化到板端在环验证（HIL）的完整链路。
- **端侧部署与软硬件协同 (Co-design)**：精通 vDSP 定点化对齐、算子重组与向量化优化，构建由 Agent 驱动的逐层敏感度分析与策略搜索自动化调优闭环。
- **模型小型化基础设施**：通道对齐结构化剪枝（申请华为公司技术秘密）、非对称知识蒸馏（DKD/Logits/Feature）、重参数化网络设计。

---

## 工作经历

- **小米｜玄戒 - 多媒体算法**（2025.08 -- 至今）
  * 资深算法工程师，负责端侧视觉大模型/ISP算法低比特量化与 vDSP 底层部署、Agent 自动化调优流水线建设。
- **华为｜诺亚方舟实验室 - 小模型实验室**（2022.03 -- 2025.08）
  * 算法工程师，主导大模型动态稀疏方案研发与大规模分布式预训练、端侧高效推理与压缩基础设施。算法作为核心亮点亮相华为旗舰手机发布会。
- **华为｜海思半导体**（2020.09 -- 2022.03）
  * 软件/系统开发工程师，负责芯片系统架构重构（DCI/DSL）与系统级内存精简专项，获评海思“优秀新员工”及“芯星奖”。
- **南京大学**（2017.09 -- 2020.07）
  * 计算机技术硕士研究生，研发 BERT 中文命名实体识别与信息抽取模型，授权国家发明专利 1 项。

---

## 开源项目与简历

- **开源项目**：[BertNER (GitHub)](https://github.com/yumath/BertNER) — BERT 中文命名实体识别开源微调项目，结合 BiLSTM+CRF 结构，获得 450+ Stars 与 90+ Forks。
- **完整简历**：欢迎查阅 [在线 CV 页面](/cv/)，或直接 [下载 PDF 简历](/assets/pdf/resume.pdf)。
