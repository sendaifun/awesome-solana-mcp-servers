*Read this in [English](README.md), [简体中文](README.zh-CN.md)*

<div align="center">

# awesome-solana-mcp-servers

![Awesome Solana MCP Servers](banner.png)

精选的 Solana 模型上下文协议 (MCP) 服务器和相关资源列表。

</div>

## MCP 服务器
- [Solana Agent Kit MCP Server](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - 使用 MCP 的 Solana Agent Kit 实现，用于处理 Solana 区块链上的协议操作。支持所有 Solana Agent Kit 操作，具有标准化的交互和基于环境的配置。
- [GOAT MCP Server](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol) - GOAT SDK 实现，使 Claude Desktop 能够在 EVM 网络上发送和接收 ETH 和 ERC-20 代币。支持 Base Sepolia 网络，易于与 Claude Desktop 集成。
- [Aldrin Labs Solana MCP Server](https://github.com/Aldrin-labs/solana-mcp-server) - 一个全面的 MCP 服务器，提供 21 种基本的 Solana RPC 方法，包括账户操作、代币管理、系统信息和质押功能。支持与 Solana 区块链数据的自然语言交互。
- [Solana Limit Order MCP Server](https://github.com/dimitrov-d/solana-limit-order-mcp) - 一个 MCP 服务器，提供通过 Jupiter 在 Solana 上设置限价单的功能。使用这个 MCP 服务器，任何 AI 代理都能够为任何代币设置限价买入/卖出订单，查看开放订单和订单历史，取消开放订单，交易代币，获取代币余额/价格等。
- [Solana Forum Summarizer MCP Server](https://github.com/dimitrov-d/solana-forum-summarizer-mcp) - 一个 MCP 服务器，提供浏览和总结 [Solana Forum](http://forum.solana.com/) 的功能。使用这个 MCP 服务器，AI 代理能够获取论坛上最新/最受欢迎的帖子，按类别或作者检索、排序和分组帖子，按关键词搜索帖子并总结帖子内容。
- [AMOCA MCP Server](https://github.com/manolaz/amoca-solana-mcp-server) - 一个专注于 Solana 钱包分析的专门 MCP 服务器。功能包括详细的代币余额分析、投资组合估值、历史交易审查，以及通过自然语言查询钱包指标。通过对话式 AI 界面提供直观的钱包数据交互。
- [SolMCP Solana MCP Server](https://github.com/N-45div/SolMCP---SendAI-MCP-competition) - 一个 MCP 服务器，提供 7 个工具来成为 Solana 交易者、验证者和节点运营商，完全用 Python 编写，使用 Helius 和 Dexscrenner 获取最新数据和操作，并集成了 Pyth oracle 价格源。
- [daoCLI MCP Server](https://github.com/DaoCLI/daoCLI-init) - daoCLI 是一个兼容 MCP 的 DAO 服务器，支持通过命令行界面进行无缝、可定制的 DAO 部署。它使 AI 代理开发者能够轻松地将基于 Solana 的 DAO 直接嵌入到应用程序中，利用经过验证的联合曲线和自动做市商（AMM）为 AI 代理解锁价值十亿美元的流动性市场。
- [Hubble MCP Server](https://github.com/HubbleVision/hubble-ai-mcp) - Hubble 是一个基于 Solana 的 MCP 服务器，能够通过自然语言对 PumpFun 和去中心化交易所（DEXs）上的交易进行数据分析和可视化。
- [Solana DeFi Analytics MCP Server](https://github.com/kirtiraj22/solana-mcp) - 一个 MCP 服务器，为 Solana 钱包和 DeFi 交互提供全面的分析和可操作的见解。它使 AI 代理和用户能够深入分析钱包行为，监控交易，并在 Solana 区块链上高效优化 DeFi 策略。
- [Quant72 MCP](https://github.com/Quant72AI/quant72-mcp) - 🚀 简单易用的一站式链上量化交易专家，内置多种行情数据源和高级分析工具。通过 AI 智能辅助进行高效链上交易，无缝集成所有 Solana Agent Kit 操作，为交易者提供专业级的链上量化交易体验。
- [spice MCP Server](https://github.com/getnimbus/spice) - spice 是一个实现 Solana 数据查询系统的 MCP 服务器。它允许用户获取 Solana 目录元数据，并提供通过 Flipside API 查询 Solana 区块链数据的工具。
- [Memecoin Observatory MCP](https://github.com/tony-42069/solana-mcp.git) - 一个全面的 Solana MCP 服务器，用于分析迷因币、跟踪趋势，并通过文化分析和链上数据提供 AI 驱动的见解。具有实时迷因币雷达、社交信号分析、鲸鱼钱包跟踪和跑路保护功能。
- [Solana Wallet Security Scanner](https://github.com/mohitparmar1/Solana-Wallet-Security-Scanner) - 一个实现 Solana 安全分析系统的 MCP 服务器。它允许用户扫描钱包威胁，检测可疑程序，并提供通过 @solana/web3.js 监控区块链活动的工具。
- [MCP Meme Deployer](https://github.com/kirabuilds/mcp-meme-deployer) - 一个模型上下文协议（MCP）服务器，允许 Claude Desktop 通过简单的对话在 Solana 上以零成本部署即时可交易的代币。
- [Cabal Radar MCP Server](https://github.com/c-viper-work/cabal-radar-mcp) - 零外部依赖的 Solana 与 Base 代币风险情报 MCP 服务器与 CLI 工具，支持 SPL 与 Token-2022 权限/危险扩展检测、创世区块同 Slot 捆绑交易与 Jito 小费识别、以及前排持仓母钱包同源注资聚类分析。

## 工具和库
- [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) - 用于将 AI 代理连接到 Solana 协议的工具包。具有跨链操作、代币管理、Voltr 金库交互和基于 LangGraph 的多代理系统支持。
- [GOAT SDK](https://github.com/goat-sdk/goat) - 用于构建和集成 GenAI 功能的框架，内置 MCP 支持。包括工具管理、开发 UI 游乐场和跨模型兼容性。

## 资源
- [模型上下文协议快速入门](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart) - 全面的指南，涵盖 MCP 协议基础知识、服务器实现、客户端设置和早期采用用例。包括实践示例和 Claude Desktop 集成。
- [在此添加有用的资源] - MCP 开发的文档、教程、博客文章、视频、调试指南和最佳实践。

## 目录

### 什么是模型上下文协议 (MCP)？

模型上下文协议 (MCP) 是一个使 AI 模型能够以标准化方式与外部工具和资源交互的协议。它提供以下框架：
- 工具集成和执行
- 资源管理和访问
- 提示模板和管理
- 采样功能
- 根级操作

MCP 服务器可以与各种客户端集成，包括：
- Claude Desktop 应用
- Cursor
- Continue
- Zed
- Sourcegraph Cody
- 以及更多

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。
