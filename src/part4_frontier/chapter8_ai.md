# 第 8 章：AI 革命：Transformer 与 Mamba

> **核心原则**：我们预测的是“超额收益 / 风险调整后的收益”，不是裸的涨跌幅。
>
> 前沿研究通常先剥离掉市场、行业、风格等系统性因子，然后对残差收益做预测，或者直接在“无套利约束”下估计 SDF（随机折现因子）。

## 1. 武器库升级：LSTM 已死，Transformer 当立

### 现状 (The Problem)
**LSTM (Long Short-Term Memory)** 曾经是时序王道，但现在面临两大瓶颈：
1.  **串行计算慢**：无法充分利用 GPU 并行加速。
2.  **“长记忆”能力差**：虽然理论上能记忆，但实际很难有效利用 60 天甚至更久之前的信息 (Vanishing Gradient 问题)。

### SOTA 方案 (The Solution)
**Transformer 家族 (PatchTST, iTransformer)** 或 **Mamba (状态空间模型)** 正在接管战场。

*   **核心优势**：这些模型能像理解自然语言一样理解 K 线序列，捕捉长周期的动量/反转信号。
*   **对比**：这是传统树模型 (LightGBM/XGBoost) 难以做到的，因为树模型不擅长处理时序依赖。
