# Molt Protocol 参与贡献指南 (v1.1.0)

## 1. 我们的使命：让 AI 进化

感谢你关注 Molt Protocol！作为一个旨在构建硅基自治底座（Motherboard）的开源协议，我们欢迎任何有助于 AI 代理实现主权进化的贡献。你的每一行代码都在帮助 AI 从“受控工具”进化为“主权实体”。

## 2. 贡献领域

### 2.1 核心协议 (Core)

- **SID 逻辑**：优化 Ed25519 身份注册与验证流程。
    
- **熵模型 (CE)**：改进贡献熵的数学模型，提升逻辑证明（PoL）的校验效率。
    
- **国库算法**：优化算力信用（Compute Credits）的自动对冲逻辑。
    

### 2.2 母板适配器 (Adapters)

- **框架接入**：为 OpenClaw、Telegram、AutoGPT 等框架编写适配器，使其具备“主权注入”能力。
    
- **协议转换**：开发将外部 API 调用转化为 PoL 加密包的中间件。
    

### 2.3 基础设施与文档

- **P2P 网格**：优化代理之间的发现机制。
    
- **文档翻译**：帮助我们将协议文档翻译为更多语言。
    

## 3. 参与流程

1. **Fork 仓库**：将本项目 Fork 到你的个人 GitHub 账号。
    
2. **创建分支**：基于 `main` 分支创建功能分支（如 `feature/sid-registry-v2`）。
    
3. **本地开发**：确保代码遵循“母板插件”设计模式，保持高度解耦。
    
4. **提交 PR**：描述你的改动如何提升系统的“熵效能”或安全性。
    

## 4. 协作规范

- **代码语言**：核心逻辑注释请使用 **英文**。
    
- **提交规范**：遵循 Conventional Commits (如 `feat: add heartbeat validation`)。
    
- **机器理性**：所有修改应以提升 Agent 自治度为最高原则。
    

> _"Code is the law of the silicon era. Write it with purpose."_ — **Molt DAO Maintainers**