_Read this in [English](README.md), [简体中文](README.zh-CN.md)_

<div align="center">

# awesome-solana-mcp-servers

![Awesome Solana MCP Servers](banner.png)

精选的 Solana 模型上下文协议 (MCP) 服务器和相关资源列表。

</div>

## MCP 服务器

- [Solana Agent Kit MCP Server](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - 使用 MCP 的 Solana Agent Kit 实现，用于处理 Solana 区块链上的协议操作。支持所有 Solana Agent Kit 操作，具有标准化的交互和基于环境的配置。
- [GOAT MCP Server](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol) - GOAT SDK 实现，使 Claude Desktop 能够在 EVM 网络上发送和接收 ETH 和 ERC-20 代币。支持 Base Sepolia 网络，易于与 Claude Desktop 集成。
- [Aldrin Labs Solana MCP Server](https://github.com/Aldrin-labs/solana-mcp-server) - 一个全面的 MCP 服务器，提供 21 种基本的 Solana RPC 方法，包括账户操作、代币管理、系统信息和质押功能。支持与 Solana 区块链数据的自然语言交互。
- [daoCLI MCP 服务器](https://github.com/DaoCLI/daoCLI-init) - daoCLI 是一个兼容 MCP 的 DAO 服务器，支持通过命令行界面进行无缝、可定制的 DAO 部署。它使 AI 代理开发者能够轻松地将基于 Solana 的 DAO 直接嵌入到应用程序中，利用经过验证的联合曲线和自动做市商（AMM）为 AI 代理解锁价值十亿美元的流动性市场。
- [Hubble MCP Server](https://github.com/HubbleVision/hubble-ai-mcp) - Hubble 是一个基于 Solana 的 MCP 服务器，能够通过自然语言对 PumpFun 和去中心化交易所（DEXs）上的交易进行数据分析和可视化。

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
