# The Little Book of Quant (量化实战手册)

[![Deploy mdBook to GitHub Pages](https://github.com/alin-ap/the_little_book_of_quant/actions/workflows/deploy.yml/badge.svg)](https://github.com/alin-ap/the_little_book_of_quant/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **从因子挖掘到 AI 交易的实战指南**
> 
> A practical guide to quantitative trading, from factor mining to deep learning alpha.

## 📖 关于本书 (About)

这本书致力于构建一个从经典理论到现代工程实践，再到前沿 AI 技术的完整量化知识体系。它不仅包含 Fama-French 等经典理论，更深入探讨了 Transformer、GNN 等深度学习模型在量化领域的 SOTA 应用。

👉 **在线阅读 (Read Online)**: [https://alin-ap.github.io/the_little_book_of_quant/](https://alin-ap.github.io/the_little_book_of_quant/)

## 🏗️ 核心内容 (Contents)

- **Philosophy (量化之道)**: 从 CAPM 到 Fama-French 再到机器学习的范式演进。
- **Engineering (工程架构)**: 数据清洗、去噪、中性化与回测系统的流水线设计。
- **Factors (因子军火库)**: 
  - **Time Series**: 动量、反转与波动的时序逻辑。
  - **Fundamental**: 质量、成长与估值的基本面逻辑。
  - **Alternative**: 情绪与资金流分析。
- **AI Frontier (前沿战法)**: 
  - Transformer & Mamba 在时序预测中的应用。
  - Graph Neural Networks (GNN) 捕捉产业链传导。

## 🛠️ 本地构建 (Build Locally)

本项目使用 [mdBook](https://rust-lang.github.io/mdBook/) 构建。如果你想在本地运行或贡献代码，请按以下步骤操作：

### 1. 安装 mdBook

**MacOS (Homebrew):**
```bash
brew install mdbook
```

**Windows / Linux:**
请参考 [mdBook 官方安装指南](https://rust-lang.github.io/mdBook/guide/installation.html)。

### 2. 克隆仓库

```bash
git clone https://github.com/alin-ap/the_little_book_of_quant.git
cd the_little_book_of_quant
```

### 3. 运行服务

```bash
# 启动本地实时预览服务器
mdbook serve --open
```

运行后，浏览器将自动打开 `http://localhost:3000`。

## 🤝 贡献 (Contributing)

欢迎提交 Issue 或 Pull Request 来改进内容！

1. Fork 本仓库
2. 新建分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
