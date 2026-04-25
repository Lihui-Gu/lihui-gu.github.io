---
permalink: /
title: "Lihui Gu (顾立辉)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Education / 教育经历

* **M.S. in Software Engineering / 软件工程硕士**, Zhejiang University / 浙江大学, 2023 - 2026 (Expected / 预计)
  * National Key Laboratory of Computer Aided Design and Computer Graphics / 计算机辅助设计与图形学国家重点实验室
  * Advisor / 导师: 王闻箫

* **B.S. in Computer Science and Technology / 计算机科学与技术学士**, Zhejiang University of Technology / 浙江工业大学, 2019 - 2023
  * School of Computer Science and Technology / 计算机科学与技术学院
  * Double Major / 双学位: Computer Science and Technology; Minor / 辅修: Intelligent Science and Technology
  * GPA: 4.23/5, Major Ranking / 专业排名: 1/23


## Work Experience / 工作经历

* **AI Search ML Infra Engineer / AI 搜索 ML 基础设施工程师**, ByteDance / 字节跳动, Beijing / 北京, 01/2026 - Present / 至今
  * 多模态 LLM 投机解码训练：基于 EAGLE3 方案为多模态搜索场景设计和训练 draft 模型，实现端到端推理加速，显著降低在线服务延迟。
  * RL 后训练全异步重构：主导基于 verl 框架的全异步后训练流水线架构设计与实现，消除生成-训练串行瓶颈，将系统训练效率 SMA 从 19% 提升至 35%。

* **Large Model Inference Optimization Intern / 大模型推理优化实习生**, Kuaishou - Keling Technology Department / 快手 - 可灵技术部, Beijing / 北京, 06/2025 - 12/2025
  * DiT 模型特征缓存复用优化：利用相邻去噪时间步特征的相似性，优化特征缓存复用策略。在开源模型（30B/235B 规模）上经过大量实验验证，该方法在相同加速比下超越 TaylorSeer/EasyCache 等 SOTA 方案，在 Wan2.1/Hunyuan 视频生成模型上实现 2.5 倍端到端加速，在 Flux 图像生成模型上实现 3.0 倍加速。
  * 在未经蒸馏的可灵 i2v 模型上实现近无损的 1.4 倍端到端加速，相关工作被 ICLR 2026 (CCF-A) 接收。

* **Navigation Group Algorithm Intern / 导航组算法实习生**, Hangzhou Feibu Technology / 杭州飞步科技, Zhejiang / 浙江, 09/2024 - 04/2025
  * 预测-交互一体化建模：设计端到端数据驱动模型替代基于规则的策略，增强复杂场景下的决策能力。
  * 强化学习优化：基于 PPO 算法实现模型迭代，持续提升港口路口通行效率并降低碰撞风险。
  * 工程落地：在 1000+ 仿真场景中将平均路口通行时间降低 0.5 秒，完成模型实车部署，实习期间获得 S 级绩效评价。


## Publications / 论文发表

* **SCALINGCACHE: Extreme Acceleration of DiTs Through Difference Scaling and Dynamic Interval Caching**
  * Lihui Gu, et al., ICLR 2026 (CCF-A)


## Open Source / 开源贡献

* [SafeAILab/EAGLE](https://github.com/SafeAILab/EAGLE): Speculative decoding framework / 投机解码框架. Contributed [bug fixes](https://github.com/SafeAILab/EAGLE/pull/226) / 提交 bug 修复.


## Skills / 专业技能

* **深度学习与推理优化 / Deep Learning & Inference Optimization**:
  * 熟悉多模态 LLM 投机解码（EAGLE3 方案）完整训练流程，具备 draft 模型训练与推理部署的端到端经验。
  * 熟悉 RL 后训练全异步流水线设计与优化，具备 verl 框架训练效率调优经验。
  * 熟悉 DiT/LLM 推理优化技术、主流推理框架（vLLM、xDiT）核心功能及多卡分布式推理技术。
  * 精通投机解码底层实现，可结合 FP8 量化、通信优化、张量并行、CUDA Graph 等技术。
  * 了解高性能融合算子 Megakernel 实现细节。


## Honors & Awards / 荣誉奖项

* 全国一等奖 / National First Prize, Mathorcup 全国大学生数学建模竞赛（自动驾驶泊车研究）, 2022
* 省政府奖学金 / Provincial Government Scholarship（本科期间连续三年）, 2022
* 校一等奖学金（前 3%）/ First-class University Scholarship, 浙江工业大学 / Zhejiang University of Technology, 2022
* 三等奖 / Third Prize, APMCM 亚太地区大学生数学建模竞赛, 2021
* 二等奖 / Second Prize, 全国大学生数学建模竞赛（浙江赛区）, 2021


## Experience / 实习与求学经历

<head>
  <style>
    table, th, td {
      border: 0;
    }
  </style>
</head>

<table style="width:100%;border:0;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
    <tbody>
        <tr>
            <td  style="padding:20px;width:40%;vertical-align:middle">
                <img width="750" src="/images/kuaishou-logo.png">
            </td>
            <td style="margin-left:20px;width:60%;vertical-align:middle">
                <div >
                    Kling AI / 可灵 AI, Kuaishou / 快手
                </div>
                2025.06 - 2025.12 <br>
                Mentor Leader / mentor 负责人: 赫景彬, 何康<br>
                Interests / 研究方向: Controllable Video Generation / 可控视频生成
            </td>
        </tr>
        <tr>
            <td  style="padding:20px;width:40%;vertical-align:middle">
                <img width="750" src="/images/zju-logo.jpg">
            </td>
            <td style="margin-left:20px;width:60%;vertical-align:middle">
                <div >
                    M.S. / 硕士, Zhejiang University / 浙江大学
                </div>
                2023.09 - Present / 至今 <br>
                Advisor / 导师: 王闻箫<br>
            </td>
        </tr>
    </tbody>
</table>
