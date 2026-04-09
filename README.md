# 🚀 深度强化学习：最新前沿算法与工业级落地算法学习笔记
**一份面向 DRL 最新前沿 + 工业落地算法的学习笔记**

---

## 📘 项目简介
本笔记基于经典 DRL 底层基石（DQN 系列、AC 架构、PG、DP/MC/TD 等）进一步向上延伸，聚焦**下一代范式跃迁**与**工业级可用算法**。

内容覆盖：
- 离线强化学习（Offline RL）
- 世界模型与基于模型的 RL（World Models & MBRL）
- 多智能体 RL（MARL）
- 元学习与分层控制（Meta-RL & HRL）
- 工业级 PPO / SAC / TD3 家族
- 安全约束 RL + 传统控制融合
- Sim2Real 虚实迁移
- 分布式训练架构

---

## 🧠 笔记整体结构

## 大类一：前沿理论流派与范式跃迁
定位：解决经典算法（DQN/PPO/SAC）的理论瓶颈，主攻**样本效率、长程规划、多机协同、泛化能力、数据驱动**。

### 1. 离线强化学习 (Offline RL)
解决痛点：真实物理系统试错成本极高，仅用历史数据学习策略
- 价值保守与隐式约束
  - CQL、IQL、TD3+BC、EDAC、Cal-QL、ReBRAC
- 序列建模与生成式架构
  - Decision Transformer、MAGE、PRGS、MoGE

### 2. 世界模型与基于模型的强化学习 (World Models & MBRL)
解决痛点：学习环境模型进行虚拟试错，样本效率提升 10–100 倍
- MBRL 基础：PILCO、PlaNet、MBPO
- Dreamer 家族：DreamerV2 / V3、R2-Dreamer、ResWM
- 规划与协同：MuZero、TD-MPC2、SeqWM、TrajTok、JOWA

### 3. 多智能体强化学习 (MARL)
解决痛点：集群协同、非平稳环境、信用分配
- 价值分解：VDN、QMIX、QPLEX
- CTDE 架构：MADDPG、MAPPO、HAPPO、COMA
- 前沿范式：S-MADRL、MATWM、LOGO

### 4. 元学习与层级控制 (Meta-RL & Hierarchical RL)
解决痛点：快速自适应、长视距任务拆解
- MAML、ProMP、PEARL、VariBAD
- HIRO、ITMP

---

## 大类二：工业级落地算法与核心增强机制
**Industrial-Grade & Deployment**
定位：**稳定、安全、可部署、可真机验证**，工程化即插即用模块。

### 1. 工业级主力算法演进
- PPO 工业家族：PPO-Clip、DPPO、APPO、PPO-LSTM/Transformer、GRPO
- SAC / TD3 工业家族：SAC-LSTM、FlashSAC、AE-TD3

### 2. 高效学习机制插件
- 稀疏奖励与探索：HER、AHER、RND、ICM、MaxInfoRL
- 样本效率：PER、REDQ、DroQ
- 视觉表征：CURL、MAE+RL

### 3. 安全约束与经典控制融合
- 安全 RL：CMDP、CPO、Lagrangian 系列、Safety Layer、Recovery RL
- 混合控制：RL+PID、RL+MPC、RL+LQR

### 4. 虚实迁移与分布式架构
- Sim2Real：Domain Randomization、RMA、MOTO、RLinf-Co
- 分布式：IMPALA、SEED RL、Sample Factory、Ray / RLlib

---

## 📁 开源说明
你可以自由：
- 使用本笔记用于**学习、科研、教学、工作**
- 转发、分享、修改、扩展
- 用于论文综述、报告、答辩材料
**使用时请注明来源即可**

---

## 📩 后续计划
- 逐篇发布**算法笔记**


---

## 🌟 如果对你有帮助，欢迎 Star 支持！
