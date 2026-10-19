# Yang Lin · 杨林

**Sales Director @ [RoboParty](https://roboparty.cn) · Humanoid Robotics & Embodied AI**

技术型销售。站在客户需求和工程现实中间 —— 把工厂、实验室、教室里真正要解决的问题，翻译成一台能落地的机器人配置。

I work at the point where customer requirements meet engineering reality. My job is to understand the technical constraints well enough to say no when a spec won't work, and to understand the customer's business well enough to propose what will.

[roboparty.cn](https://roboparty.cn) · [Email](mailto:yanglin@roboparty.com)

---

## 我们做什么 · What RoboParty Builds

**上海萝博派对科技有限公司**，2025 年 2 月成立于上海，专注**全栈开源人形机器人**。第一款原型机 ROBOTO_ORIGIN 从启动到跑通只用了四个月，结构、电控、训练、部署全链路开源。

RoboParty is a Shanghai-based company building **fully open-source humanoid robots**. Our first prototype, ROBOTO_ORIGIN, went from zero to running in four months — with structures, electronics, training, and deployment all open-sourced.

| 产品线 | 说明 |
|---|---|
| **RPO / ROBOTO_ORIGIN** | 全开源人形机器人原型机，可自行采购与加工完成整机组装 |
| **RP1** | 人形机器人整机产品线 |
| **RP Hand** | 五指灵巧手，11 个机械自由度（含 6 个主动轴），蜗轮机构，CAN-FD 通信 |

### 开源模块 · Open-Source Modules

| 模块 | 内容 |
|---|---|
| `rpo_hardware` | 机械结构、CAD 图纸、PCB 设计、BOM |
| `roboparty_deploy` | ROS 2 部署框架、中间件、IMU / 电机驱动 |
| `roboparty_train` | 强化学习训练环境与配置，Sim2Sim 迁移至 MuJoCo |
| `rpo_description` | URDF / MJCF 运动学与动力学描述 |
| `roboparty_firmware` | 嵌入式固件、USB2CAN |
| `roboparty_navigation` | 导航与定位模块 |
| `roboparty_xr_teleop` | XR 遥操作应用 |

### 技术栈 · Stack

![ROS2](https://img.shields.io/badge/ROS_2-Humble-silver)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-4.5-silver)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-2.1-silver)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![C++](https://img.shields.io/badge/C++-17-blue)
![License](https://img.shields.io/badge/License-GPLv3-blue)

生态项目：[Party_OS](https://github.com/Roboparty/Party_OS) · [MimicLite](https://github.com/Roboparty/MimicLite) · [P-BFM](https://github.com/Roboparty/P-BFM)

👉 [github.com/Roboparty](https://github.com/Roboparty)

---

## 能做什么 · How I Can Help

| 方向 | 具体内容 |
|---|---|
| **需求梳理** | 从客户的实际使用场景出发，梳理真实需求与优先级 |
| **技术对齐** | 与客户方工程师逐条核对参数，明确能力边界与不承诺项 |
| **方案撰写** | 技术方案、招投标参数表、产品配置清单的编写与校验 |
| **生态对接** | 对接脑机接口、遥操作、灵巧手等周边方案，把单机设备串成完整技术路线 |
| **场景反馈** | 把一线使用中的痛点结构化地带回研发 |

> 说"能"的时候，是问过工程师的；说"不能"的时候，也是。

---

## 技术理解 · Technical Literacy

不是研发，但需要听懂、说清、写对：

- **ROS 2 基本概念** · 话题 / 服务 / 参数的设计逻辑，能读懂接口文档
- **机器人本体参数** · 自由度、关节扭矩、臂展、负载、续航等指标的工程含义
- **仿真与训练** · URDF / MJCF 模型、强化学习训练管线的基本概念
- **文档能力** · 技术方案、招投标参数表、配置清单的撰写

## 关注领域 · Areas of Interest

- **Embodied AI** · 人形机器人从实验室走向教学与产业场景
- **Education Robotics** · 高职与本科具身智能实训体系的设备与课程配套
- **BCI × Robotics** · 脑机接口作为人形机器人输入端的可行性边界
- **Teleoperation** · VR / XR 遥操作在动作示教与数据采集中的作用

---

---

## 客户方案 · Solutions

面向教育、科研与产业客户的具身智能落地方案。以下为方案框架与思路，**具体配置与报价按客户需求单独提供**。

| 方案 | 解决什么问题 | 核心思路 |
|---|---|---|
| **高职具身智能综合实训室** | 高职院校要开具身智能专业，但缺设备、缺课程、缺师资 | 10 套教学单元（机器人 + 灵巧手 + 遥操作 + 机械臂）+ 96 学时六门课程 + 一次性整体交付 |
| **高校具身智能科研实验室** | 科研团队需要可二次开发的硬件平台，而不是封闭产品 | 全栈开源平台，硬件、ROS 2 接口、仿真环境、训练管线全开放，支持自定义课题 |
| **RPO × 脑机接口联合方案** | 脑机接口算法缺标准化执行端，各家自建平台导致结果不可比 | 三层解耦架构：意图层（解码）→ 任务层（桥接）→ 执行层（机器人平衡控制），统一 ROS 2 接口与时间同步 |
| **VR 遥操作教学单元** | 遥操作与动作示教需要低门槛、可量化的教学工具 | 消费级 MR 一体机 + 体感追踪器，通过标准接口对接机器人，仿真优先、实机仅做低风险动作 |

### 方案设计原则

- **能力边界写清楚**：能做和不能做分开列，不承诺做不到的事
- **仿真优先**：高风险动作先在仿真验证，再上真机
- **分层解耦**：上层算法出问题，下层控制仍能守住安全
- **可迁移**：学生在校掌握的工具链，与产业界当前技术路线一致

---

## 参与的工作 · Work

| 项目 | 说明 |
|---|---|
| **具身智能实训室方案** | 面向高职院校的完整建设方案：机器人 + 灵巧手 + 遥操作 + 机械臂 + 配套课程 |
| **RPO × 脑机接口联合方案** | 侵入式脑机接口作为人形机器人输入端的系统架构与实施路径 |
| **客户场景落地** | 教育与科研机构的设备选型、参数对齐与交付 |

更多公开仓库会随项目开放陆续补充 · See my [public repositories](https://github.com/yanglin8899?tab=repositories).

---

## 联系方式 · Contact

- **Email** · [yanglin@roboparty.com](mailto:yanglin@roboparty.com)
- **Phone / WeChat** · +86 138-1831-3261
- **Company** · [上海萝博派对科技有限公司](https://roboparty.cn)
- **开源社区** · [github.com/Roboparty](https://github.com/Roboparty)

Open to conversations about **humanoid robot deployment in education and research**. 如果你正在评估人形机器人是否适合自己的教学或科研场景，欢迎直接聊 —— 包括它做不到的地方。
