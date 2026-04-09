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

---

## 📚 全算法 arXiv 论文链接汇总

### 大类一：前沿理论流派与范式跃迁
#### 1. 离线强化学习 (Offline RL)
| 算法名称 | arXiv 链接 |
|--------|-----------|
| CQL | https://arxiv.org/abs/2006.04779 |
| IQL | https://arxiv.org/abs/2110.04622 |
| TD3+BC | https://arxiv.org/abs/2106.06820 |
| EDAC | https://arxiv.org/abs/2110.01548 |
| Cal-QL | https://arxiv.org/abs/2303.05479 |
| ReBRAC | https://arxiv.org/abs/2305.09836 |
| Decision Transformer | https://arxiv.org/abs/2106.01345 |
| MAGE | https://arxiv.org/abs/2510.08045 |
| PRGS | https://arxiv.org/abs/2510.03017 |
| MoGE | https://arxiv.org/abs/2402.07236 |

#### 2. 世界模型与基于模型的强化学习 (World Models & MBRL)
| 算法名称 | arXiv 链接 |
|--------|-----------|
| PILCO | https://arxiv.org/abs/1106.0665 |
| PlaNet | https://arxiv.org/abs/1811.04556 |
| MBPO | https://arxiv.org/abs/1906.08253 |
| DreamerV2 | https://arxiv.org/abs/2010.02193 |
| DreamerV3 | https://arxiv.org/abs/2301.04104 |
| R2-Dreamer | https://arxiv.org/abs/2510.04154 |
| ResWM | https://arxiv.org/abs/2601.03547 |
| MuZero | https://arxiv.org/abs/1911.08265 |
| EfficientZero | https://arxiv.org/abs/2111.00210 |
| TD-MPC2 | https://arxiv.org/abs/2310.16828 |
| SeqWM | https://arxiv.org/abs/2503.09347 |
| TrajTok | https://arxiv.org/abs/2403.14509 |
| JOWA | https://arxiv.org/abs/2402.12564 |

#### 3. 多智能体强化学习 (MARL)
| 算法名称 | arXiv 链接 |
|--------|-----------|
| VDN | https://arxiv.org/abs/1706.05296 |
| QMIX | https://arxiv.org/abs/1803.11485 |
| QPLEX | https://arxiv.org/abs/2008.01062 |
| MADDPG | https://arxiv.org/abs/1706.02275 |
| MAT-DDPG (MASAC) | https://arxiv.org/abs/2104.06655 |
| MAPPO | https://arxiv.org/abs/2103.01955 |
| HAPPO | https://arxiv.org/abs/2109.11251 |
| COMA | https://arxiv.org/abs/1709.05273 |
| S-MADRL | https://arxiv.org/abs/2402.08735 |
| MATWM | https://arxiv.org/abs/2503.09347 |
| LOGO | https://arxiv.org/abs/2511.08764 |

#### 4. 元学习与层级控制 (Meta-RL & HRL)
| 算法名称 | arXiv 链接 |
|--------|-----------|
| MAML | https://arxiv.org/abs/1703.03400 |
| ProMP | https://arxiv.org/abs/1307.2189 |
| PEARL | https://arxiv.org/abs/1903.08254 |
| VariBAD (RL2) | https://arxiv.org/abs/1910.08348 |
| HIRO | https://arxiv.org/abs/1805.08296 |
| ITMP | https://arxiv.org/abs/2512.03478 |

---

## 大类二：工业级落地算法与核心增强机制
### 1. 工业级主力算法演进
| 算法名称 | arXiv 链接 |
|--------|-----------|
| PPO | https://arxiv.org/abs/1707.06347 |
| DPPO | https://arxiv.org/abs/1707.02286 |
| APPO | https://arxiv.org/abs/1802.01561 |
| PPO-LSTM | https://arxiv.org/abs/2005.12729 |
| PPO-Transformer | https://arxiv.org/abs/2205.14445 |
| PPO+GAE | https://arxiv.org/abs/1506.02438 |
| GRPO | https://arxiv.org/abs/2407.04418 |
| SAC | https://arxiv.org/abs/1812.05905 |
| SAC-LSTM / SAC-Transformer | https://arxiv.org/abs/2104.03957 |
| FlashSAC | https://arxiv.org/abs/2604.04539 |
| TD3 | https://arxiv.org/abs/1802.09477 |
| AE-TD3 | https://arxiv.org/abs/2201.08091 |
| TD3-perturbation | https://arxiv.org/abs/2302.04521 |

### 2. 高效学习机制
| 算法名称 | arXiv 链接 |
|--------|-----------|
| HER | https://arxiv.org/abs/1707.01497 |
| AHER | https://arxiv.org/abs/2103.04170 |
| RND | https://arxiv.org/abs/1810.12894 |
| ICM | https://arxiv.org/abs/1705.05363 |
| Disagreement-based Exploration | https://arxiv.org/abs/1602.04621 |
| MaxInfoRL | https://arxiv.org/abs/2402.09564 |
| PER | https://arxiv.org/abs/1511.05952 |
| REDQ | https://arxiv.org/abs/2101.05982 |
| DroQ | https://arxiv.org/abs/2210.02006 |
| CURL | https://arxiv.org/abs/2004.04136 |
| MAE | https://arxiv.org/abs/2111.06377 |

### 3. 安全约束与经典控制融合
| 算法名称 | arXiv 链接 |
|--------|-----------|
| CPO | https://arxiv.org/abs/1705.10528 |
| CMDP 理论 | https://arxiv.org/abs/2003.09305 |
| PPO/SAC-Lagrangian | https://arxiv.org/abs/2003.09305 |
| Safety Layer | https://arxiv.org/abs/2006.12938 |
| Action Masking | https://arxiv.org/abs/2006.14171 |
| Recovery RL | https://arxiv.org/abs/2010.15920 |
| Feasible-Guided Diffusion | https://arxiv.org/abs/2406.01572 |
| RL+PID | https://arxiv.org/abs/2103.15005 |
| RL+MPC (TD3-MPC) | https://arxiv.org/abs/2203.10606 |
| RL+LQR | https://arxiv.org/abs/2006.07476 |

### 4. 虚实迁移与分布式架构
| 算法名称 | arXiv 链接 |
|--------|-----------|
| Domain Randomization | https://arxiv.org/abs/1703.06907 |
| Domain Adaptation | https://arxiv.org/abs/1906.07987 |
| System ID + DR / RMA | https://arxiv.org/abs/2107.04034 |
| MOTO | https://arxiv.org/abs/2407.01345 |
| Sim2Real-AD / RLinf-Co | https://arxiv.org/abs/2602.08743 |
| IMPALA | https://arxiv.org/abs/1802.01561 |
| SEED RL | https://arxiv.org/abs/1910.06591 |
| Sample Factory | https://arxiv.org/abs/2006.11752 |
| Ray / RLlib | https://arxiv.org/abs/1807.05866 |
